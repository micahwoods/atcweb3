---

title: "The inexorable rise of soil organic matter"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- OM246
- topdressing
date: 2021-08-10T17:19:00+07:00
lastmod: 2021-08-10T17:19:00+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true
---

One of the many valuable things I utilize from OM246 testing is what I call the *organic matter accumulation rate*. I'm actually referring to the *net* accumulation rate---how the total organic material in the rootzone would change if no topdressing had been applied.

{{< figure src="hngc_green_profile.jpg" caption="'Penn A4' creeping bentgrass greens and putting green profile at Hazeltine National Golf Club in Minnesota during June 2019." >}}

It's essential to manage the organic material at the surface, for both biological and playability reasons. With OM246 test results, one can manage this with precision, adjusting the work with confidence, because with the time series testing one gets both the gross organic matter accumulation rate, which I usually refer to as the *change over time*, and the net accumulation rate which accounts for the quantity of sand applied.[^1]

[^1]: And for the organic material removed, which I have calculated manually but have not put the code into the OM246 calculator yet. 

[Carley et al.](https://doi.org/10.2134/agronj2010.0335) collected a chronosequence of organic matter samples from creeping bentgrass putting greens in North Carolina and found that the gross accumulation rate, what I would typically call change over time, was rapid at first and then declines to about 1 g/kg/year (0.1%) on greens that are more than 10 years old. 

{{< figure src="carley_fig3.jpg" >}}

The data from Carley et al. are the change over time from greens where "the golf course superintendents used a suite of management practices, including periodic top-dressing, two or three aerations per year ... and nitrogen was added at 151 to 252 kg N ha<sup>-1</sup> yr<sup>-1</sup>."

All the aeration and topdressing and growth and decomposition effects are combined in the change over time. I find it really useful to account for the topdressing and then look at how OM changed with that sand effect already accounted for.

{{< figure src="keya_kbc_green.jpg" caption="Practice putting greens of manilagrass (*Zoysia matrella*) at Keya Golf Club in Fukuoka during the KBC Augusta Tournament." >}}

I have time series of OM246 data from the courses pictured here. All have different grass species on the greens and range from tropical Thailand to transition zone Japan to Minnesota.

{{< figure src="nikanti_roll.jpg" caption="Rolling a Tifeagle putting green at Nikanti Golf Club in December." >}}

The data from North Carolina on change over time showed that with all the maintenance work, the organic matter in the top inch still accumulates, but it does so at a rate decreasing to about 1 g/kg/year.

{{< figure src="net_om_accumulation_rate.png" >}}

The data from these courses shows that if the effect of the sand topdressing is taken away, the organic matter in the top 2 cm of the rootzone was accumulating at average rates ranging from 18 g/kg/year on bentgrass in Minnesota up to 37 g/kg/year on Tifeagle in a tropical climate.

What that means is without the topdressing and other maintenance work that was done, the organic matter in the top 2 cm at Nikanti GC would have been expected to go up by 37 g/kg (3.7%) in one year.

Knowing this accumulation rate makes it possibly to make precise adjustments to the work. The [OM246 Shiny App](https://asianturfgrass.shinyapps.io/om246/) has a calculator for this.

The data shown in the net organic matter accumulation rate chart is more consistent for Hazeltine and Nikanti than at Keya. Hazeltine has greens constructed at the same time with the same rootzone material across the course---and so does Nikanti. At Keya, the greens are of different ages and different materials, so there is naturally more variation in the rate; Keya's data is also shown for multiple greens across multiple years. Based on these data, I expect the organic matter accumulation rate for most golf courses to range from less then 0 (in rare cases) to more than 50 g/kg/year.
