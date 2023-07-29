---

title: "Hourly evapotranspiration, soil water content, and crop coefficients"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- water
- irrigation
- evapotranspiration
categories: []
date: 2023-07-29T11:42:42+07:00
lastmod: 2023-07-29T11:42:42+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true
  
math: true  

projects: []
---

On June 9, 2023, I was at Keya Golf Club in Fukuoka, Japan. The final round of the Landic Challenge 10 tournament was played that day.

{{< figure src="morning_keya_10.jpg" caption="A morning view down the 10<sup>th</sup> hole at Keya Golf Club prior to the final round of the Landic Challenge 10 tournament." >}}

The weather was pleasant, with cloudy skies at sunrise giving way to partly sunny skies by 08:00 and then almost full sun from 10:00 to 15:00. I made my [usual measurements](https://youtube.com/shorts/agKu3tpr_xY?feature=share) of playing conditions and growing conditions. 

{{< youtube "agKu3tpr_xY" >}}
<br>

Those measurements included volumetric water content (VWC) of the 4<sup>th</sup> and 11<sup>th</sup> greens. I took nine measurements across each green and consider the mean value as that green's VWC. The 4<sup>th</sup> green is surrounded by pine trees, has partial shade, and some restricted air movement. The 11<sup>th</sup> green is at the top of a hill, is in full sun, and has plenty of air movement.

{{< figure src="hourly_et_june9_plot1.png" >}}

The reference evapotranspiration (ET<sub>o</sub>) on June 9 looks like this. Summing the hourly ET<sub>o</sub> gives a daily total of 4.1 mm (0.16 inches). 

{{< figure src="natty_dread_lunch.jpg" caption="Lunch at Natty Dread while the golf course is occupied by tournament golfers." >}}

After getting those morning data, and making some calculations, I went for lunch at Natty Dread.[^1]

[^1]: It's a tradition to eat one meal per tournament week at this classic jerk chicken/hamburger restaurant in Itoshima. Get there early if you want a parking spot or a table.

{{< figure src="afternoon_keya_4.jpg" caption="The 4<sup>th</sup> green at Keya GC at 12:54 p.m. on June 9. This green is in full sun at midday but is in partial shade in mornings and afternoons because of the pine trees to the left, at back, and to the right of the green site." >}}

After my delicious lunch, and after the final group had played the holes I measured in the morning, I went back on the course with my tools and took the same playability and growing condition measurements I had made prior to play. This included another measurement of VWC. 

There had been some ET<sub>o</sub>, and I am going to look at how the ET<sub>o</sub> in the 6.5 hours between the morning and the early afternoon measurement is related to the change I measured in VWC from morning to afternoon. There was no rain and no irrigation applied in the 6.5 hours between the morning and afternoon measurements.

{{< figure src="featured.png" >}}

If you use the model that I do of a 10 cm deep rootzone, then a 1% change in VWC is equal to 1 mm of water added, or 1 mm of water lost. You can see more about this, and a way to do this in inches as well, in the [soil water content turf hacks]({{< relref "/post/soil-water-content-turf-hacks" >}}) post. I find it easier to do the math in my head by doing this in metric---there are no fractions of inches to deal with---and I'll use mm for the remainder of this explanation.

The ET<sub>o</sub> is a really useful number, but it is of course the output of an equation. The ET<sub>o</sub> is not what really happened. What really happened in terms of water use is the change in soil water content. For example, if there is no rain, and no irrigation applied, and if the VWC was 18% at 08:00 and if the VWC remains at 18% at 14:00, then no water was lost---no water was used---and that's the reality. It wouldn't matter if the ET<sub>o</sub> for those 6 hours was 2 mm. If the VWC did not change, then that is the reality.

Of course the ET<sub>o</sub> equation is really good, and it gets remarkably close to how much water the grass really does use. We just need to adjust the ET<sub>o</sub> by the crop coefficient (K<sub>c</sub>) to get the amount of expected water use by the grass for the grass and growing conditions at our site.

Because I know the VWC at known times of the day, and because I calculated the hourly ET<sub>o</sub> on the same day, I can get an estimate of what the K<sub>c</sub> is for those two greens at Keya GC. 

The accumulated ET<sub>o</sub> from the morning VWC measurement time to the afternoon VWC measurement time was 2.3 mm. If the K<sub>c</sub> were 1, then I'd expect the VWC to go down by 2.3%. 

For warm-season turf---the greens at Keya GC are korai (*Zoysia matrella*)---it is customary to use a K<sub>c</sub> of somewhere around 0.6 or 0.7. The VWC went down on #4 green by 1.49%. That's an apparent K<sub>c</sub> for #4 green of $\frac{1.49}{2.3}=0.64$. 

On #11, which is in full sun and has more air movement, the VWC went down from the morning to the afternoon measurement by 1.95%. That's a water loss of 1.95 mm, and an apparent on-course K<sub>c</sub> of $\frac{1.95}{2.32}=0.84$. 

There was more water in the 11<sup>th</sup> green that morning than there was on the 4<sup>th</sup>. That difference in starting VWC is expected to have an effect on the grass water use rate as well. When the soil gets drier, the grass will use less water.

Obviously, two half-day measurements don't provide much information, and I wouldn't assume that the K<sub>c</sub> should be 0.64 for the 4<sup>th</sup> and 0.84 for the 11<sup>th</sup>. This post is to show how easy it is to switch between soil VWC measurements and ET<sub>o</sub> calculations and water use rate assumptions and from those to calculate a site-specific (K<sub>c</sub>). Do this for a few more greens, however, for a few more days, and you'll quickly get a reliable number that you can work with.







