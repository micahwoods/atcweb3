---

title: "Turfgrass growth ratio, nitrogen harvest, and fertilizer adjustment"
subtitle: ""
summary: ""
authors: [admin]
tags: [growth ratio, nitrogen, tissue test]
categories: []
date: 2024-02-10T14:57:49+07:00
lastmod: 2024-02-10T14:57:49+07:00
featured: false
draft: false

math: true

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

Is there a way to estimate how much nitrogen is harvested in clippings? Is there an equation to use to adjust a nitrogen fertilizer rate based on the turfgrass growth ratio? Yes, there are ways to do both of these. I described them during an ATC Office Hours episode with Bjarni Hannesson and Jason Haines.

* [Watch the episode](https://youtube.com/live/Q1AX13lkU38?feature=share)
* [Listen to the episode](https://share.transistor.fm/s/0cf2b0ea)

These are the equations, or calculations, I described.

## Estimating nitrogen harvest in clippings

When you have clipping volume, this is a straightforward estimate. 

On average, the dry weight of the clippings will be 6% of the uncompressed fresh weight.[^1] That is, for every 1,000 cm<sup>3</sup> of fresh clippings, you can expect them to have a mass of about 60 g. 

{{< figure src="featured.jpg" caption="One can calculate the estimated amount of N that is in the clippings in this bucket." >}}

[^1]: For data about this conversion, which works for creeping bentgrass, see the data in the supplemental information published along with [Zhou et al., 2021](https://doi.org/10.3389/fpls.2021.749854). My research on this gets a similar value for creeping bentgrass and for Tifeagle bermudagrass. For *Zoysia matrella* I've calculated a conversion factor of about 10%.

Then, you can estimate the N percentage of the clippings. It is reasonable to use a value of 4% for N content of the clippings.[^2] You can adjust this if you have some data from your own site. The 60 g of dry clippings that we have estimated from the 1,000 cm<sup>3</sup> of fresh clippings will be 2.4 g of N. 

[^2]: It's reasonable to assume 4% for most species on putting greens. I have been checking leaf nutrient content for multiple species and have found the value for bentgrass to be above 4% in samples collected from 2019 through 2023. Using 4% may be a slight underestimation for creeping bentgrass. I'd use 4% for bermudagrass, 4 or 5% for *Poa annua*, 3% for seashore paspalum, 2% for zoysia, and I don't know for fine fescue---I'd guess about 3% at the time of writing.

I have recommended for a long time to make this calculation [in reverse](/post/flipping-things-around/), starting with a N application rate of say 1 g/m<sup>2</sup>. That much N could produce about $\frac{1}{0.04}=$25 g of dry clippings, and 25 g of dry clippings would be about $\frac{25}{0.06}=$420 mL/m<sup>2</sup>. I find it useful to think of how many clippings one might want to have over a given time period, and then think about how much N should be applied to produce that.

## Adjusting nitrogen rate using the growth ratio

In our conversation, Jason made the good point that if the grass is growing faster than his desired growth ratio, he won't apply N. If the grass is growing slower than his desired growth ratio, he will apply N. That's a simple approach and there's a lot to be said for making adjustments in that way. 

I have the idea that if the [standard N rate](/post/monthly-maximum-n-or-annual-maximum-n/) is appropriate---and by that I mean low enough---then one can apply that rate adjusted by the ratio of desired growth ratio to actual growth ratio. Chris Tritabaugh shared that equation in one of the comments, and I discussed it, and I wanted to explain that a bit more here as well.

Let $N_{o}$ be the standard amount of nitrogen that one would apply in an application. Now this can be figured out in various ways. For example, one might apply the same rate every time, but adjust the spacing between applications. Or one might have a daily amount that gets summed based on past or forecast GP. Or one might estimate N harvest and replace it. Whatever the method is, there is some amount of N that one would be planning to apply in an application.

I'm suggesting that $N_{o}$ can be adjusted based on the ratio between the desired growth ratio, expressed as $gr_{o}$, and the actual growth ratio, $gr_{a}$. You decide what you want $gr_{o}$ to be, and then use a trailing average[^3] of $gr_{a}$ to tell you what the actual growth ratio is.

That adjustment can be expressed in this equation, adjusting the standard amount of N to get the actual amount of N to apply in this application---call $N_{a}$ the actual to apply---based on whether the actual growth ratio is above or below the desired growth ratio.

$$N_{o}(\frac{gr_{o}}{gr_{a}}) = N_{a}$$

When the desired growth ratio is higher than actual, then the nitrogen rate gets adjusted up. When the grass is growing more than the desired growth ratio, then the nitrogen rate gets adjusted down.

[^3]: I have suggested in the past to use trailing 14 day average. This value is a compromise. A trailing 30 day average seems too far into the past for me. I'm not sure I want my fertilizer application tomorrow to be influenced by how the grass was growing 23 days ago. But I want to get a little bit of history in there too. If I only mowed four times in the past week, and the temperatures fluctuated a lot, is the trailing 7 day average stable enough for this purpose? There's some flexibility with how one can do this. At the time of writing, I'm going with 14 days as my recommendation.



