---
title: 'GP and GDD: are they comparable?'
authors: [admin]
date: 2016-01-19T13:19:40+00:00
lastmod: 2021-04-24
tags:
  - Australia
  - climate
  - growth potential
  - rturf
image:
  preview_only: true
---
Someone asked me at the Northern Green Expo if the temperature-based growth potential (GP) and temperature-based growing degree days (GDD) are comparable. They sort of are, with a couple of exceptions. Comparable, yeah, kind of. But they are *not* interchangeable.

I downloaded the weather data for every day in 2015 from the international airports at London (Heathrow), Minneapolis, Sydney, and Tokyo (Haneda). Then I calculated the GP, and the GDD, and I made the charts shown in this post. The script to produce the charts is  [here](https://gist.github.com/micahwoods/79dd2b8f22bf7f4fc441).[^1] I’ll try to explain this, but I think it is easiest to see how GP and GDD are similar, and how they differ, by making some comparisons yourself.

[^1]: The WeatherUnderground downloads were convenient, back in the day when that worked. But those downloads that worked in 2016 won't work now. 

First, here are the mean daily temperatures in 2015. The points are daily mean temperatures for each day of the year, and the lines are a moving average. Sydney and Tokyo are both hot in the summer, Minneapolis is coldest in the winter and hotter than London in the summer, and London is coolest in the summer but has winter temperatures close to those of Tokyo.

{{< figure src="temperature.svg" >}}

Those cities have fairly diverse temperature ranges and variation in temperature from winter to summer. One expects a different growing environment in each. The GP<sub>3 </sub> is a value with a minimum of 0 and a maximum of 1, showing the expected limitation (or potential) of temperature on growth.

{{< figure src="gp.svg" >}}

What do we see there? It’s a bit different than the temperature. Looking at the moving average for each city, we see Tokyo has a big drop in mid-summer because it is too hot, and Sydney has a substantial drop too, and Minneapolis has a slight drop in GP during the hottest summer temperatures, and London has peak GP in mid-summer because the average temperature rarely exceeds the optimum growth temperatures.

In the winter, the GP<sub>3 </sub> drops to almost 0 at Minneapolis, London, and Tokyo, but at Sydney it drops just below 0.5 in mid-winter, indicating that C<sub>3 </sub> grasses should still be able to grow, albeit slowly.

That was GP through the year. Now we can look at GDD<sub>0 </sub> . That is, for each day with an average temperature above 0°C (32°F), I take that temperature and call that the GDD. In this case, I would be using a  _base temperature_ of 0°C. This is the basis for the  [growing degree day model of Kreuser](http://turf.unl.edu/research/PGR_GDD/GDDCropSci.pdf) for the reapplication of plant growth regulators.

{{< figure src="gdd0.svg" >}}

That’s not exactly like the GP plot above. It is like zooming in on the temperature chart, but only showing the portion of the chart with temperatures above 0°C. Compared to the GP chart, one notices that with GDD  <sub>0 </sub> there is no drop in mid-summer when it is too hot, and the GDD<sub>0 </sub> does not drop all the way to 0 in winter at Tokyo and London.

So far it seems the GP and GDD are sort of the same, and sort of different. Both are based on temperature. But GDD is a measure of heat accumulation. GP is generating a value with a minimum of 0 when temperatures are far from an optimum for photosynthesis, and then generating a value that gets closer to 1 as the temperatures get progressively closer to 1.

There are various ways to calculate the heat accumulation through growing degree days. The GDD<sub>10 </sub> only counts the degrees on those days when the average temperature is above 10°C (50°F). This is GDD with a base temperature of 10°C. That makes sense for some things, and this chart of GDD<sub>10 </sub> is similar to the GDD<sub>0 </sub> chart in that it is as if the temperature chart were cropped to omit all values less than 10°C.

{{< figure src="gdd10.svg" >}}

That’s what GDD<sub>10 </sub> is showing. Now we are looking only at the days in the year when the average temperature was above 10°C, and we can see how much heat accumulation there would be each day.

The big difference between GP and GDD is evident, because Sydney and Tokyo are peaking in GDD when temperatures are at their hottest, but GP would produce a value less than 1 when GDD was highest in those places, because the temperatures are considered too hot for optimum growth of C<sub>3 </sub> grass.

GDD is heat accumulation. GP is optimum growth temperature accumulation. Let’s look at the accumulation explicitly, by adding together the GP for every day of the year in order to get these lines showing the cumulative sum of GP in 2015.

{{< figure src="cumsumGP.svg" >}} 

Sydney with the year-round growth, although with a dip in winter and also a dip in summer, has the highest sum of GP. Then Tokyo, and Minneapolis and London are similar.

We can do the same type of chart for GDD<sub>0 </sub> .

{{< figure src="cumsumGDD0.svg" >}}

Sydney still has the highest sum, then Tokyo, but there is less of a distance between these two cities than with GP, because GDD is using all of Tokyo’s hot summer days, but GP in Tokyo drops when it is hot. London and Minneapolis are similar again, but notice that Minneapolis accumulates almost all its GDD<sub>0 </sub> from April to October, while the milder winter in London allows the GDD<sub>0 </sub> to accumulate slowly year-round.

The cumulative sum of GDD<sub>50 </sub> is just a little different.

{{< figure src="cumsumGDD10.svg" >}} 

Now Tokyo catches and exceeds Sydney in the northern hemisphere autumn, but Sydney catches up quickly as summer approaches. And when counting the heat accumulation now only above 10°C, Minneapolis now has a lot more of that than does London.

The GP and GDD with various base temperatures (0 and 10°C are two of the standard ones) can be used for different things. GDD is good for things that are heat dependent. Growth regulators, insects, diseases, weeds – certainly the growth of certain plants in the range of temperatures from the minimum temperature required for growth up to the optimum temperature for growth. The GP is formulated in a different way, where it decreases when it is too cold or too hot for optimum growth.

We can look at that a little more closely. Now let’s just look at 2 cities to reduce the overlap: London and Minneapolis. Here is the GDD<sub>0 </sub> for every day of 2015.

{{< figure src="tVsGdd0.svg" >}} 

That’s a linear increase in GDD<sub>0 </sub> for every increase in temperature above 0°C. If we would plot GDD<sub>10 </sub> , there would also be a linear increase with temperature, but the line would start going up at a mean daily temperature of 10 rather than at 0.

The GP for that same range of temperatures at London and Minneapolis looks completely different.

{{< figure src="tVsGp.svg" >}} 

That’s because the GP has a minimum of 1 and a maximum of 0, and the value is dependent on how close the temperature is to the optimum temperatures for photosynthesis.

Now to get back to the original question, after all those examples, are GDD and GP comparable? For them to be comparable, there would have to be a linear relationship (or almost linear relationship) between the accumulated GP and the accumulated GDD through the year.

Here I’ve plotted just that; the cumulative sum of GP for 2015 is on the x-axis, and the cumulative sum of GDD<sub>0 </sub> is on the y-axis.

{{< figure src="gpVsGDD0.svg" >}}

Well, that is sort of linear, but has a few weird curves or shifts. London’s GDD goes up in winter when the GP is still low, and Tokyo’s GDD goes way up in mid-summer when the accumulated GP is increasing slowly. And the line for Sydney looks pretty straight by comparison, but we can take a closer look at that by checking GP vs GDD<sub>10 </sub> .

{{< figure src="gpVsGDD10.svg" >}}

Now we are looking at how GP accumulates through the year, and comparing that to how GDD<sub>10 </sub> accumulates. At some times of the year it is linear, but as temperatures get low or high, the slope of that line changes.

If you would make these calculations for data at your location, I think you would see the same thing and would see how GP and GDD are similar and how they are different.
