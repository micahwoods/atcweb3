---
date: "2018-01-09T00:00:00Z"
share-media: https://farm3.staticflickr.com/2495/3810887415_53768f0494_b_d.jpg
tags:
- web/tech
- rturf
categories:
- rturf
title: Turfgrass Twitter Analysis
authors: [admin]
image:
  preview_only: true
---

I used the [rtweet](https://cran.r-project.org/web/packages/rtweet/index.html) package to collect turfgrass community tweets from 2017. I had learned of this package from [Bob Rudis' blog post about rtweet](https://rud.is/b/2017/10/22/a-call-to-tweets-blog-posts/).

At the end of the year, I had a bit of time, and a lot of curiosity, so I finally tried it. I wondered if I could find which turfgrass industry accounts had the most impact, or influence. To figure that out, I looked at these data:

* the number of followers
* how often the account tweeted (tweet creation rate)
* how many times the account was mentioned by others
* how many of the tweets sent from the account had a large number of retweets
* how many of the tweets sent from the account had a large number of favorites
* an overall ranking of the accounts, based on a combination of the ranks in those categories

The results of the calculations are in this searchable and sortable [Turfgrass Twitter 2017](https://asianturfgrass.shinyapps.io/turf_twitter/) Shiny app.

The code I used is in the [turf_twitter_2017](https://micahwoods.github.io/turf_twitter_2017/) repository on GitHub, so you can see exactly what I did.

The 6,271 accounts I studied as "turf twitter" in this analysis were selected using these criteria.

First, I got the list of followers of seven turf scientists. I wanted to study accounts that are interested in new developments in turfgrass, and I figured that almost everyone interested in that topic would be following at least one of these accounts.

```r
# get id of accounts following 
atc <- get_followers("asianturfgrass", n = 20000, retryonratelimit = TRUE)
pace <- get_followers("paceturf", n = 20000, retryonratelimit = TRUE)
unl <- get_followers("unlturf", n = 20000, retryonratelimit = TRUE)
tomy <- get_followers("striturf_tomy", n = 20000, retryonratelimit = TRUE)
jyri <- get_followers("Amplify_Turf", n = 20000, retryonratelimit = TRUE)
jk <- get_followers("iTweetTurf", n = 20000, retryonratelimit = TRUE)
unruh <- get_followers("jbunruh", n = 20000, retryonratelimit = TRUE)
```

Then I checked to see if the accounts identified in the previous search were also following one of the golf or sports turf industry associations. 

```r
# get accounts following industry organizations, which I'll use as a confirmation
# that the account is probably interested in turf
gcsaa <- get_followers("gcsaa", n = 20000, retryonratelimit = TRUE)
bigga <- get_followers("BIGGAltd", n = 20000, retryonratelimit = TRUE)
canada <- get_followers("GolfSupers", n = 20000, retryonratelimit = TRUE)
agcsa <- get_followers("AGCSA2", n = 20000, retryonratelimit = TRUE)
iog <- get_followers("the_iog", n = 20000, retryonratelimit = TRUE)
stma <- get_followers("FieldExperts", n = 20000, retryonratelimit = TRUE)
```
I identified the unique accounts in each list, and then did an intersect of the two lists to identify the accounts that followed at least one of the turf scientists *and* followed at least one of the industry associations.

```r
# that's a lot of accounts, and many are duplicates
# to get the accounts to check, first select all those that are following one of the
# turf scientists

followers <- unique(rbind.data.frame(atc, pace, unl, tomy, jyri, jk, unruh))

# make list of unique accounts following the associations
assocations <- unique(rbind.data.frame(gcsaa, bigga, canada, agcsa, iog, stma))

# use the intersect function to select only those accounts that are in both follow lists
followers_assoc <- as.data.frame(base::intersect(followers$user_id, assocations$user_id))

colnames(followers_assoc) <- "user_id"
followers_assoc$user_id <- as.character(followers_assoc$user_id)
```

Then I removed the accounts that were set to private. I also cut those with less than 50 tweets. And I removed the accounts that were following 10,000 or more accounts themselves, as those appeared to be automated to increase followers.

```r
# get basic data on these accounts
turf_follower <- lookup_users(followers_assoc$user_id)

# this removes the private accounts, also the least active ones
turf_follower2 <- subset(turf_follower, protected == FALSE & statuses_count >= 50)

# this attempts to remove those that seem to have automated follow/follower system
# in order to get a large audience, few removed here are turf related
turf_follower3 <- subset(turf_follower2, friends_count < 1e4)
```

That left 6,271 accounts for the further analysis.
