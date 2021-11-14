---

title: "Temperature, seasonal changes in growth, and figuring out the optimum amount of growth"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- ClipVol
- growth potential
- turfgrass speedo
- growth ratio
categories: []
date: 2021-11-14T14:41:28+07:00
lastmod: 2021-11-14T14:41:28+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

This can seem a bit abstract, the whole growth ratio thing. In this post, I go step-by-step through the reasoning behind this, and explain exactly which problem this solves.

There's a common question that people have when they start measuring the exact amount of clipping volume. To paraphrase, it's something like "can anyone share with me what your optimum/ideal/target clipping volumes are?" And then there are various follow-up questions, like how does this optimum/ideal/target vary by season, and by grass species.

I've shared quite a bit of information about this; see the appendices of [*One Bucket at a Time*](https://micahwoods.github.io/buckets/) to get some idea of what normal ClipVol is and how it varies by season with different grasses. But the very general answer I give, which is basically figure out when your grass is performing how you want it, and now you know a useful ClipVol number for your site and time of year, and by the way look at the appendices of my book for a hodgepodge of background data from around the world---that's not quite the specific answer that people are looking for.

Jason Haines came up with the growth ratio, which he has also called the turfgrass speedo, as a way to standardize the ClipVol across seasonal changes. In winter the grass probably won't have as much ClipVol as in summer. Dormant warm-season grass is expected to have a ClipVol of 0 and that is how it should be when dormant. So the target amount for dormant turf is 0 but the target rate in peak growing season cannot be 0.

The growth ratio is a convenient way to express this, and to find an approximate optimum/ideal/target amount for any day of the year, at least as a starting point. 

Let's take three years of air temperature data at Keya GC in Fukuoka, Japan. I'm showing a 30 day moving (trailing)[^1] average on all of these charts to smooth out the daily variability.

[^1]: This is calculated as the average of today and the previous 29 days.

{{< figure src="temperature_3y.svg" >}}

There are seasons at that location, with a winter and a summer having distinct temperatures, and grass is expected to grow at different rates depending on the season. 

I find it useful to convert the temperature data to a temperature-based growth potential (GP) on a scale of 0 to 1. This GP will also be used to adjust the expected optimum/ideal/target ClipVol.

{{< figure src="gp_3y.svg" >}}

Jason uses 625 cm<sup>3</sup>/m<sup>2</sup>/month as the maximum ClipVol. That is, 625 corresponds with a GP of 1 on a monthly basis, and a ClipVol of 20.5 corresponds with a GP of 1 on a daily basis. I don't show that chart, because it would be a duplicate of the GP above, only with a y-axis range from 0 to 20.5

Then there is the actual growth. The chart below shows the 30 day moving average ClipVol. There's no ClipVol in winter and it peaks in the summer. 

{{< figure src="clip_3y.svg" >}}

This ClipVol is not going to be the same everywhere, because of differences in weather and grass types and the way turf needs to be managed. A notably useful result of using the growth ratio, which is taking the actual ClipVol and dividing it by the GP-adjusted maximum ClipVol, is that all of a sudden there is a number that is pretty close to 1.

{{< figure src="ratio_3y.svg" >}}

Obviously there is something happening in spring where the grass is producing from 5 to 10 times more ClipVol than the GP-adjusted maximum is predicting. For summer and autumn, however, the ratio stabilizes to something closer to 1. 

I've written about the [genki level]({{< relref "/publication/woods2019-genki" >}}) as a way to communicate how much one is using nitrogen to push the grass to grow or how much one is withholding nitrogen while trying to restrict growth. The growth ratio goes a step beyond that, by showing exactly what is happening. 
