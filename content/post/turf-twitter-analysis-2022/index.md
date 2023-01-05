---
date: "2023-01-05"
authors: [admin]
tags:
- turf Twitter
- web/tech
- rturf
title: "An analysis of turfgrass industry Twitter accounts in 2022"
image: 
  preview_only: true
projects: ["turf-twitter"]
---

For the sixth year in a row, I've taken a look at "turfgrass Twitter" to find some of the most influential and active accounts from the previous year. 

I cast a broad net to find the industry accounts, and I minimize manual intervention of account addition and removal. For a description of the inclusion and exclusion criteria, see the footnote.[^1] 

[^1]: I've described the criteria in the *More information & code* tab of the Turf Twitter 2022 [Shiny app](https://asianturfgrass.shinyapps.io/turf_twitter_2022/) and in the README of the [turf_twitter_2017](https://micahwoods.github.io/turf_twitter_2017/) Github repository; the code for this year's analysis is [at GitHub here](https://github.com/micahwoods/turf_twitter_2022). In short, I first found accounts following at least one of me, PACE Turf, Bill Kreuser, John Dempsey, Envu Turf Australia (maybe that's Jyri Kaapro?), John Kaminski, or Bryan Unruh. I then found accounts following at least one of GCSAA, BIGGA, ASTMA, GMA, SFMA, or CGSA. Then I intersect those lists, so I find all the accounts that are following at least one of those turf scientists and at least one of those industry associations. Then I exclude all the accounts that are set to private, and I exclude all the accounts that have fewer than 50 total tweets. Then I do a further exclusion, removing those accounts that are following 10,000 or more accounts, because those are often automated and not related to the turf industry. Of the accounts that meet those criteria---following at least 1 of the aforementioned turf scientists, following at least 1 of the industry associations, public account, more than 50 tweets, following less than 10,000 accounts---I then select only those that sent 12 or more tweets during 2022. In this way, I get active accounts that are usually involved directly or indirectly in the turfgrass industry around the world.

{{< figure src="all_around_2022.svg" >}}

The chart above shows the top 50 accounts in 2022 using the combined rankings from six categories: number of followers, tweet creation rate, an assessment of favorites, an assessment of retweets, an assessment of quoted tweets, and a count of the times the account was mentioned. This ranking looks at both the quantity of tweets, the reaction of others to the tweets, and the number of people who could have seen the tweets. 

Note that this ranking is only one of many ways in which the "influence" could be assessed. I've put the summary results into the [Turf Twitter 2022](https://asianturfgrass.shinyapps.io/turf_twitter_2022/) Shiny App, so you can check accounts and summary statistics if you like. That app is also embedded below.

As an example of an alternative ranking, I like this one that omits the tweet creation rate and the mentions, thus devaluing the quantity of tweets sent, and includes the ratio of accounts following to accounts followed. 

{{< figure src="new5rank_2022.svg" >}} 

This approach brings some new accounts into the top 50. Hello, [PGRBill](https://twitter.com/PGRBill), [John Ledwidge](https://twitter.com/johnledwidge), [GreenkeeperMiss](https://twitter.com/GreenkeeperMiss), [Karl Standley](https://twitter.com/karl_standley), [TurfMow](https://twitter.com/turfmow), and [Kyle Callahan](https://twitter.com/callahan_kyle).

I recommend Garrick Aden-Buie's [Tweets of the Year](https://gadenbuie.shinyapps.io/tweets-of-the-year/) app for a look at any account's year on Twitter. 

Below you'll find the summary [Shiny app for 2022](https://asianturfgrass.shinyapps.io/turf_twitter_2022/). You can also check out the [#TurfTwitter](https://twitter.com/hashtag/TurfTwitter?src=hashtag_click) hashtag for more charts and discussion.

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.1/iframeResizer.min.js"></script>
<style>
  iframe {
    min-width: 100%;
  }
</style>
<iframe id="myIframe" src="https://asianturfgrass.shinyapps.io/turf_twitter_2022/" scrolling="no" frameborder="no"></iframe>
<script>
  iFrameResize({
   heightCalculationMethod: 'lowestElement'
  });
</script>



