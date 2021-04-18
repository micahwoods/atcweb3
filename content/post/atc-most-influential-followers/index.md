---
date: "2017-07-30T00:00:00Z"
subtitle: These are the accounts that themselves have the most followers and that tweet the most
tags:
- data analysis
- rturf
categories: 
- rturf
title: "A chart of asianturfgrass's most influential Twitter followers"
authors: [admin]
image:
  preview_only: yes
---

Yesterday I read [this post](https://blog.codecentric.de/en/2017/07/combining-social-network-analysis-topic-modeling-characterize-codecentrics-twitter-friends-followers/) by Shirin Glander about social network analysis and topic modeling. 

She showed a chart of number of followers and number of tweets per day, with both axes on a log<sub>2</sub> scale. That is a much cleaner display than anything I've made previously (for example, [this](http://www.asianturfgrass.com/2017-07-12-more-followers-as-supt-suggestion/) on how to get more followers as a superintendent). 

Dr. Glander described this type of analysis:

> "We can also try to identify our most influential followers. These would be followers with a big network (i.e. who have many followers) and who also tweet/re-tweet a lot. If we capture these followers’ interests with one of our tweets, they are a) more likely to re-tweet and b) will reach a bigger audience by doing so!"

This morning, based on [her code from GitHub](https://github.com/ShirinG/blog_posts_prep/blob/master/twitter/twitter_codecentric.Rmd), I made the same type of chart for [asianturfgrass](https://twitter.com/asianturfgrass) followers on Twitter. The code for the charts I made is [here](https://gist.github.com/micahwoods/ba86d8779e087cc1c91ba2078ec7c425).

First I looked at all the accounts that follow asianturfgrass. I added labels to show the 25 accounts with the most followers themselves (2<sup>nd</sup> degree followers) and the 25 accounts with the highest tweet rate (tweets per day, calculated as total number of tweets divided by the number of days since account opening).

{{< figure src="atc_followers.svg" >}}

It's apparent that some of these accounts are not related to turfgrass. I thought of ways to extract only those accounts that were probably really interested in golf course management, and chose to filter all my followers down to those accounts that follow me and also follow the [GCSAA](https://twitter.com/GCSAA), [BIGGA](https://twitter.com/BIGGALtd), and the [AGCSA](https://twitter.com/AGCSA2).

When I do the same analysis on that subset of followers that also follow those three industry associations, I get this.

{{< figure src="atc_followers_assoc.svg" >}}

And where would the asianturfgrass account be if it were plotted on this chart also? I checked that and it is keeping good company somewhere between [MikeFidanza](https://twitter.com/MikeFidanza) and [BarenbrugGroup](https://twitter.com/BarenbrugGroup).
