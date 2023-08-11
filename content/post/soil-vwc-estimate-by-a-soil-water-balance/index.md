---

title: "Soil VWC estimate by a soil water balance"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- water
- irrigation
- turf hacks
categories: []
date: 2023-08-11T18:38:49+07:00
lastmod: 2023-08-11T18:38:49+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

How would I think of soil water content if I did not have a soil moisture meter? I'd think of it in volumetric water content, the same as if I did have a soil moisture meter. That's how I did it when I was a golf course superintendent, and I didn't use any type of meter to measure the soil water content.[^1]

[^1]: One benefit of my long (a 1,955 line plain text file, as of today) list of possible blog topics is I can turn up some that I forgot about. This is one of them. With some recent discussion of soil VWC turf hacks and turf math on the [ATC Doublecut](https://doublecut.asianturfgrass.com/), this one suddenly seemed timely. A golf course consultant from SE Asia commented on one of my YouTube videos that some facilities might not have access to, or might not be able to afford, a soil moisture meter. That reminded me of the water balance method that I have often used to estimate the water content of the soil.

Instead, I used a crude daily soil water balance that worked like this. I assumed the field capacity of the rootzone was 25% VWC. I assumed the wilting point was 8%. After a precipitation event that brought the soil to field capacity, I would assume that there were 17% (or 17 mm) of plant available water in the rootzone. But I only wanted to let the grass use 15 mm of that, and then I would want to bring the soil back to field capacity.

{{< figure src="featured.jpg" caption="The practice putting green at Habu CC in August 2001." >}}

I would estimate the daily evapotranspiration in summer as being about 5 mm per day. That would give the grass 3 days of water, and I would try to stretch it another day if I could by hand-watering or running the heads for a light irrigation at the end of the day.

{{< figure src="green9irr.jpg" caption="An early evening irrigation of the ninth green at Habu CC." >}}

That was my mindset. That's what I was trying to do. I always had some idea of approximately how much water was in the rootzone. This is possible because when one works with a 10 cm rootzone depth (a 4 inch depth), 1 mm of water equals 1% of volume of the rootzone, and 1 liter of water applied to 1 square meter also equals 1 mm. Thus, whether it is evapotranspiration loss of water, or irrigation, or rainfall, one can express the numbers in the same units, and add and subtract them. They will balance, like a checkbook does. Thus, the daily water balance. 

Here's another turf hack for those without soil moisture meters. You can wait until a time when you know the soil is at field capacity. Then don't irrigate until you see visual signs that you need to supply water. That's the effective wilting point. Now sum the accumulated evapotranspiration[^2] that has been calculated from the time the soil was at field capacity until the time the soil is as the effective wilting point. 

[^2]: I recommend using a crop coefficient of 0.8 for cool season grass and 0.6 for warm-season grass to adjust the reference ET.

That sum of ET is the plant available water in your rootzone, simultaneously the exact same number whether you express it in mm, L, and VWC%. 

Based on soil type, you can estimate what your wilting point is, but it really doesn't matter. Once you know the quantity of plant available water, you can determine when you will need to irrigate again when the soil is at field capacity. You will also know how much water the soil can hold, so you can know how much water to add. And if you keep track of this daily---something like "it rained enough to soak the soil two days ago, and I know the soil can hold 15 mm of plant available water, and there has been 8 mm of ET since then, so we must be about 7 mm away from the wilting point. No need to worry about adding water tonight."


