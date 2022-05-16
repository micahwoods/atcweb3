---

title: "Soil water content turf hacks"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- water
- irrigation
- turf hacks
categories: []
date: 2021-06-25T14:33:57+07:00
lastmod: 2021-06-25T14:33:57+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true
---

{{< figure src="irrigation_hanoi.jpg" >}}

An easy way to relate inches of irrigation or inches of evapotranspiration (ET) to changes in volumetric soil water content (VWC)---that is something I could never figure out. 

I was thrilled to see [the calculations](https://twitter.com/PGRBill/status/1405549770651938817) shared by Bill Kreuser. It turns out this is incredibly simple.

{{< tweet user="PGRbill" id="1405549770651938817" >}}

Take the depth of water added (or lost) and divide by the depth of the rootzone and you are now in units of VWC. It's that simple, and doing this provides a straightforward way to convert between units of soil VWC and ET and irrigation amounts.

---

I've been using a different hack for this, and I find it even easier. I use a rootzone of fixed depth---a slice of soil to a depth of 10 cm (4 inches). When working with a portion of the soil fixed at this depth, 1 liter of water added or lost to each square meter is 1 mm and changes the VWC by 1%. Water added (or lost) by a volume of 1 can also be expressed as a depth of 1 and changes the soil water content by 1 unit. One to one to one.

I find the fixed rootzone depth useful because we never really know two important things when making these calculations and estimations:

1. We are never sure about VWC to the exact depth of the roots.

2. We can expect water use from the soil to be something like the 40-30-20-10 rule: plants obtain 40% of the water they use from the top 25% of the rootzone, 30% from the next 25%, then the remaining 30% of water use comes from the bottom 50% of the rootzone. But this is never certain.

Because of these uncertainties, I like to work with a 10 cm depth and think of managing or changing the VWC within that depth. Even with the unknowns 1 & 2 above, there is an expectation that those uncertainties cancel themselves out when measuring VWC over time, so the change simplifies to mm, L, and VWC, all on the same 1:1:1 scale.

This is one of the things we've been discussing on the [atc-turf Discord channel](https://discord.gg/K8tWApB5ME). 

And it is something that I think in-ground soil sensors are likely to be even better at than the portable ones used at the surface. Those sensors measure change at fixed depth over time, so the calculations about water requirement can be precise.
