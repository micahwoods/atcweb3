---
title: 'Simulating irrigation frequency at the world famous "snake" course'
authors: [admin]
date: 2017-03-09T21:53:09+00:00
lastmod: 2021-07-05
tags:
  - Thailand
  - water
image:
  preview_only: true
---

Many of you will have seen the Kantarat Golf Course when flying into Bangkok. Maybe you've played it. It sit between the two runways at Don Mueang International Airport in Bangkok.

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d8643.256527325497!2d100.5998513!3d13.9094423!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xcbce5ec116cefd14!2sKantarat%20Golf%20Course!5e1!3m2!1sen!2sth!4v1625467161717!5m2!1sen!2sth" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>

It is commonly called the snake course, and I can confirm there are a lot of snakes out there.

{{< figure src="snake_tee.jpg" >}}

And then there are the planes, and the crossing of active taxiways.

{{< figure src="landing_747.jpg" >}}

{{< figure src="micah_thai_taxiway.jpg" >}}

### More about irrigation frequency

I've [written previously]({{< relref "/post/deep-and-infrequent-or-light-and-frequent-irrigation-which-is-better" >}}) about whether it is better to do deep and infrequent irrigation, or whether it might actually be better to irrigate frequently in small amounts. I applied the daily soil water balance to work through this for a location at DMK.

Let's say we are growing grass at DMK and have a 10 cm rootzone depth and then the weather happens as it did every day at that location in 2015. 

I'll have some plan of how I'm going to irrigate, too. Let's say there is a field capacity of 25%, and I expect the grass may wilt when the volumetric water content (VWC) is less than 10%. I will try to irrigate to keep the soil from dropping below 12%, and every time I irrigate, I will fill the soil back to field capacity. When I do that, for example using a crop coefficient (K<sub>c</sub>) of 0.7 and a lower quartile distribution uniformity (DU<sub>LQ</sub>) of 0.75, I can then simulate the soil water content day by day through the year. I do that by stepping through each day of the year, with the evapotranspiration and precipitation as it happened, adding irrigation as required by the rules I've set. Doing that for 2015, the irrigation requirement is 1011 mm and the median VWC through the year is 19.7%.

{{< figure src="sim1.png" >}}

I can also simulate the soil water content and irrigation required for a different set of rules, but for the same soil and weather. I did that, for those same 2015 weather data, now irrigating at 14% rather than at 12%, but instead of supplying enough water to raise the soil back to field capacity, I only add enough to increase the soil water to 18%. When I do this, the irrigation requirement drops to 970 mm, and the median VWC goes to 15.5%.

{{< figure src="sim2.png" >}}

I checked this for 2016 data, and the results were similar: a total 949 mm of irrigation required and median VWC for the year of 20.2% using deep and infrequent rules, 889 mm irrigation and a median VWC of 15.6% with light and frequent irrigation. 

{{< figure src="sim3.png" >}}

{{< figure src="sim4.png" >}}
