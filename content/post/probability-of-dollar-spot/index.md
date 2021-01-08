---
date: "2018-05-30T00:00:00Z"
share-media: https://c1.staticflickr.com/3/2655/3756330585_e9a1b6f28b_o_d.jpg
subtitle: The Smith-Kerns Dollar Spot Prediction Model uses air temperature and relative
  humidity to give a probability that dollar spot disease will occur on turfgrass.
  Here's how it works.
tags:
- disease
- weather
- science
title: The probability of a dollar spot epidemic
---

I've written about [reactive greenkeeping](https://www.asianturfgrass.com/2018-04-01-is-reactive-better-than-proactive/) being at least a viable option, and have implied that it is preferable to proactive greenkeeping. With a little effort, one can get information (data) about the weather, the amount of water in the soil, the quantity of nutrients in the soil and the quantity of nutrients used by the grass, the growth rate of the grass, and so on. Even if one doesn't have an exact number, one can estimate these and other pieces of useful information.

An exciting addition to the turfgrass manager's toolkit in this regard is the [Smith-Kerns Dollar Spot Prediction Model](https://tdl.wisc.edu/dollar-spot-model/). For cool-season grasses, I've always recommended a proactive approach to dollar spot prevention. Specifically, I've looked at the long-term average of air temperatures, identified those months at a location during which the average temperature is above the optimum---that is, when the grass is expected to suffer from heat stress---and have suggested that preventative fungicides be applied during those months. 

But the weather isn't the same as the average conditions. It would be *inefficient* to be proactive in these preventative applications when the weather is not conducive to dollar spot, and it would be *ineffective* to rely on this proactive approach based on averages when the weather conditions stray from the averages, as is sure to happen.

Here's a brief [description of the model](https://tdl.wisc.edu/dollar-spot-model/) from the University of Wisconsin:

> "The Smith-Kerns Dollar Spot Prediction Model is a logistic-based model that uses a 5-day moving average of daily relative humidity and daily average air temperature to create a probability that dollar spot will occur on a given day. The model was created by [Dr. Damon Smith](http://www.plantpath.wisc.edu/users/dsmith99) and [Dr. Jim Kerns](https://plantpath.cals.ncsu.edu/people/faculty/jim-kerns/) and has been validated through years of additional field research conducted primarily in Wisconsin but also in Oklahoma, Pennsylvania, Mississippi, Tennessee, Connecticut, and New Jersey. The model can be used by golf course superintendents to more accurately time control measures to suppress dollar spot."

This is a link to the [full article: "Development and validation of a weather-based warning system to advise fungicide applications to control dollar spot on turfgrass."](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194216) Use of this "weather-based warning system" is a great way to be reactive to the actual conditions. If one wants to think of that as being proactive, I can go along with that too!

I recently made some calculations of dollar spot probability using the Smith-Kerns model. The model takes as inputs the 5 day average of air temperature, and the 5 day average of relative humidity, and based on those inputs it produces a probability that a dollar spot outbreak will occur. In the validation trials for this model, application of fungicide when the probability was 20% or higher provided effective control of dollar spot. Note that this 20% level is only a starting point, and one can evaluate the model and dollar spot pressure at one's site, with the grass varieties and management practices that one uses, to find an appropriate site-specifc threshold.

One of the things I looked at was historical data for Chicago. In the past 70 years, [1966 had the lowest](https://c2.staticflickr.com/2/1742/40645369410_096ece6315_b_d.jpg) probability of dollar spot.

![dollar spot probability in Chicago in 1966](https://c2.staticflickr.com/2/1742/40645369410_096ece6315_b_d.jpg)

I also looked at when the model probability exceeded 20% in the spring. On average in Chicago, [that happens on May 28](https://c2.staticflickr.com/2/1737/40645367990_8d60600216_h_d.jpg).

![70 years of dollar spot probability in Chicago](https://c2.staticflickr.com/2/1737/40645367990_8d60600216_h_d.jpg)

The calculations are easy once one has put the equations into a file, or written a script to make the calculations, or has put the data into files available at the [Wisconsin TDL page](https://tdl.wisc.edu/dollar-spot-model/). Getting historical data, however, [can be complicated](https://flic.kr/p/J2ud48).

<a data-flickr-embed="true"  href="https://www.flickr.com/photos/asianturfgrass/27583804437/in/dateposted-public/" title="command line weather data"><media src="https://farm2.staticflickr.com/1731/27583804437_37cf256061_b.jpg" width="1024" height="576" alt="command line weather data"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

I was running that script to get hourly data from Guelph, Ontario. After downloading eleven years of data---that's a lot of hours---I then ran the temperature and humidity through the model to generate a dollar spot probability. I wanted to look especially at September and October---those months are highlighted on [this chart](https://www.flickr.com/photos/asianturfgrass/42403786232/sizes/h/)---to see what type of disease probability tends to occur. 

![11 years of Smith-Kerns dollar spot prediction model output for Guelph, Ontario](https://c2.staticflickr.com/2/1736/42403786232_687a30aa81_h_d.jpg)

Relative humidity has a big impact on the model probability. When the humidity is 100%, even at low temperatures, the probability of a dollar spot epidemic is nearly 50%. However, when the humidity is 20% or below, even when air temperature is extremely high, the probability of dollar spot is less than 10%.

![relative humidity has a big impact on the model probability as shown in this chart](https://c2.staticflickr.com/2/1727/40645377050_964dc0cf2c_b_d.jpg)

More information about the model, and some spreadsheets to get started, are available from the [University of Wisconsin Turfgrass Diagnostic Lab](https://tdl.wisc.edu/dollar-spot-model/).











