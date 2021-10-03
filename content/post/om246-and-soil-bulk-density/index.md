---

title: "Sand and organic matter have different bulk densities"
subtitle: "Therefore, one must adjust for bulk density when combining or averaging across depths"
summary: ""
authors: [admin]
tags: 
- OM246
categories: []
date: 2021-10-03T14:39:53+07:00
lastmod: 2021-10-03T14:39:53+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
math: true
---

Organic material measurement by mass loss on ignition is reported on a mass basis. 

For OM246 testing, I prefer doing a burn at 440 °C.[^1] The equation for loss on ignition (LOI) as a percentage takes the mass of sample dried at 105 °C ($m_{105}$), subtracts the mass of the sample after burning at 400 °C ($m_{440}$), divides by the original mass, and multiplies that by 100.

[^1]: I prefer doing a burn at 440 °C because that temperature does a complete ashing of the stems, rhizomes, and stolons in the sample. See my post on [temperature for loss on ignition in turfgrass soils]({{< relref "/post/measuring-organic-matter-ignition-temperature" >}}) for more about this. A burn at 360 °C returns almost the same number---there is not a big difference between the mass loss from a 360 and a 440 °C burn. But I prefer the way stolons and rhizomes and stems and roots---the grass plants themselves---look after they have been completely ashed at 440 °C.

$$ \text{LOI (%)} =  (\frac{m_{105} - m_{440}}{m_{105}}) \times 100 $$

That's the equation for LOI as a percentage. 

I recorded [a video about understanding an OM246 report](https://youtu.be/wUtpJC1YPU0), and Kyle Marshall wrote with a great question about something I mentioned:

> So the end of your video you talk about adjusting for bulk density when you look at all 6 cm together, what equation do you use to adjust for bulk density?

I'll explain here with one example, showing the equations and explaining what's happening as I go through it.

# An inches example

Kyle sent some recent results where the top 1 inch was 4.8% OM and from a depth of 1 to 2 inches there was 3.1% OM.

## The wrong way

At first glance, it seems like we could find the OM in the top 2 inches by taking the average of the measurement from the top inch and the second inch. That would be 3.95%.

{{% callout warning %}}
This average of the two depths is incorrect because it does not account for the different mass of each depth.

$$ \frac{4.8 + 3.1}{2} = 3.95\text{%} $$
{{% /callout %}}

That would be incorrect, however, because the top inch of the rootzone, and the second inch of the rootzone, don't have the same mass. 

{{< figure src="featured.jpg" >}}

Organic matter is light. Soil, sand, those are heavy. Six or seven times heavier than the same volume of organic matter. In order to make a more accurate calculation, one can adjust by bulk density.

## Finding bulk density

To find the bulk density ($\rho_{i}$) for depth $i$ of the rootzone, I use this equation that assumes[^2] the organic material at depth $i$, represented as ($OM_{i}$), has a bulk density of 0.22 kg/m<sup>3</sup> and the sand at depth $i$ has a bulk density of 1.56 kg/m<sup>3</sup>.

[^2]: I believe these are the same values used in McCoy's [organic matter management tool](https://buckeyeturf.osu.edu/organicmattertool).

$$\rho_{i} = \frac{100}{\frac{OM_{i}}{0.22} + \frac{100 - OM_{i}}{1.56}} $$

Note that the bulk density for the depth of interest, $\rho_{i}$, is in units of kg/m<sup>3</sup> which is equivalent to units of g/cm<sup>3</sup> which I'll use for convenience in the examples here.

For the example of the top inch of the rootzone at an organic matter content of 4.8%, that means there are 48 g of material lost on ignition[^3] for each 1 kg of soil. And there are 31 g/kg in the second inch.

[^3]: It is common to call this *organic matter*, but to be exact it is the mass loss on ignition---whatever has burned off. For convenience we can consider this to be the mass of organic matter in the soil.

Here's how I'd adjust for the different bulk densities to find the organic matter content of the top two inches.

First, find the bulk density of the top inch and of the second inch. Because the organic matter is known, this is straightforward using the equation for $\rho_{i}$.

$$ \rho_{\text{inch1}} = \frac{100}{\frac{4.8}{0.22} + \frac{100 - 4.8}{1.56}} = 1.2 $$

For the second inch layer, the bulk density is a little higher.

$$ \rho_{\text{inch2}} = \frac{100}{\frac{3.1}{0.22} + \frac{100 - 3.1}{1.56}} = 1.3 $$

## Getting mass by depth

At this point, we know the depth of the layers, which in this case are in inches. And we know the OM content of each layer, and we have now calculated the estimated bulk density of each layer, given that they have a known amount of organic matter present.

Now it is possible to calculate the OM on a mass basis for the two layers combined.

The way I do this is to work with a base unit of one square meter (1 m<sup>2</sup>). 

One inch is 2.54 cm. The mass (in grams) of the top inch in 1 m<sup>2</sup> will be $100 \times 100 \times 2.54 \times 1.2$. That's 100 cm on each side, 2.54 cm down, which gives us the volume of that slice of the rootzone in cm<sup>3</sup>, and then multiplying by the bulk density of 1.2 g/cm<sup>3</sup> gives a mass of 30,480 g. We know that 4.8% of that is organic matter, so the OM in the top inch of one square meter weighs 1,463 g.

The mass of the second inch of the rootzone, using the same calculation and plugging in the different bulk density and organic matter content of that depth, gives a mass of 33,020 g and an organic matter mass of 1,024 g.

## OM calculation for two (or more soil layers)

Now it is possible to combine the two layers. The total organic matter in the top two inches is the OM in the top inch plus the OM in the second inch, so this is 1,463 + 1,024 = 2,487 g.

This quantity of OM is in soil with a mass of those two layers combined. This is 30,480 + 33,020 = 63,500 g.

The OM percentage of these layers combined is thus $\frac{2487}{63500} \times 100 = 3.92$%.

## Does this even matter?

"3.95% calculated the simple way, and 3.92% calculated this way, does it even matter?" you might be asking. It does matter if you want to get the correct answer, and these values happen to be relatively close, but with other possible values of soil organic matter, there can be a larger difference between the correct and incorrect calculation.

For example, take the OM2 and OM4 and OM6 data shown [in the video](https://youtu.be/wUtpJC1YPU0), in the example data from April 2021. Those were 12.7, 3.8, and 2.4% respectively, by depth. The average of those without correcting for bulk density is 6.3%. The actual value is 5.7% after accounting for bulk density.

If you want to get the correct answer, the calculation must be made correctly. You don't have to work through this yourself. As I showed in the video, I make these calculations already so that the correct values are shown on the report. The McCoy/Dryject [organic matter management tool](https://buckeyeturf.osu.edu/organicmattertool), also implemented in [Greenkeeper app](https://greenkeeper.blog/2021/04/21/soil-organic-matter-models-aid-cultivation-scheduling/), is making these calculations behind the scenes also, I believe. And in the [OM246 calculator](https://asianturfgrass.shinyapps.io/om246/) that finds both the OM accumulation rate and a sand topdressing requirement for any depth of the rootzone that you wish to work with, these calculations are also being made by the software.






