---

title: "N input accounting"
subtitle: ""
summary: ""
authors: [admin]
tags:
- Fertilizer
- Organic matter
- Nitrogen
- ClipVol
categories: []
date: 2021-03-12T12:45:46+07:00
lastmod: 2021-03-12T12:45:46+07:00
featured: false
draft: false

image:
  caption: "Organic material added as topdressing will eventually supply N to the turf."
  focal_point: ""
  preview_only: false

---

Phil Collinson [asked an interesting question](https://twitter.com/PhilColl_ICL/status/1368208113719971851): when calculating N inputs, do greenkeepers account for N added outside of fertilizer?

{{< tweet user="PhilColl_ICL" id="1368208113719971851" >}}

Phil mentioned possible N addition from fensoil or compost topdressings, and possible N addition from irrigation water treatments.

This is something that I've written about a few times, in relation to the N in precipitation and to mineralized N from soil organic matter. The amount of N added from the different sources will be site specific, and at a lot of sites certain sources will be negligible and can be ignored. But it makes sense to check all these to determine which are negligible at a site, and which are not.

Possible sources of N include:

* N added as fertilizer
* N in precipitation[^1]
* N in the irrigation water
* N from organic material (fensoil, compost, etc.) added as topdressing
* N mineralized from soil organic matter

[^1]: The measurements of this will often include atmospheric deposition of N.

Are there other ones that I've missed? This turns out to be pretty simple, because at a lot of locations most of the possible N sources are negligible and can be ignored. However, if an N source is meaningful, then it is worth the effort to figure out the amount being added.

### How I'd go about checking the sources of N addition

I recommend keeping records of N added as fertilizer, which at most locations will be the largest source of N. I like units of mass of N per area to which it was applied, and am particularly fond of the g/m<sup>2</sup> unit.

N in precipitation (and atmospheric deposition of N) is something you can check for your location. See [how much N is in rain and snow](https://www.blog.asianturfgrass.com/2017/06/how-much-n-is-in-rain-and-snow.html) and [post-rain growth flush]({{< relref "/post/nitrogen-in-rain-or-nitrogen-from-the-soil" >}}) for more about this and links to data sources. In general, this number is pretty low, usually less than 2 g N/m<sup>2</sup>/year.

The N in the irrigation water is easily calculated from the average N concentration of irrigation water and the amount of water applied. I recommend testing irrigation water once a year, prior to the start of the peak irrigation season, primarily to find out the salt content of the water (TDS & EC) and the sodium adsorption ratio (SAR), and also to check the N content of the water. For sites with poor water quality, I would test more often. For sites with good water, I skip a year or two between tests with no concern. If one is adding nitric acid or other water treatments with N in them, then naturally those sources of N should be accounted for.

The addition of N in organic material through topdressing is something that might not need to be accounted for directly, because it could fall into the next category---mineralized N. If there happens to be inorganic N in the topdressing material, then I'd want to account for that. For the organic N in a topdressing, I'd assume that is going to be part of the soil organic matter, and I can track that with organic matter measurements of the soil.

The N mineralized from soil organic matter depends on soil moisture and soil temperature (climate) and soil pH, and on how much organic matter is in the soil. Generally, one can assume that soil organic matter is 5% N and that from 1 to 4% of the soil organic matter will be mineralized in a year. Taking the middle of that range, and assuming a soil bulk density of 1.5 g/cm<sup>3</sup>, one can expect mineralized N to be about 2 g N/m<sup>2</sup>/year for every 1% OM in a soil to 10 cm depth. This can be estimated through the year and adjusted to site temperatures and soil moisture by various methods; I've been using the method of [Gilmour and Mauromoustakos](https://dx.doi.org/10.2136/sssaj2010.0123) and wrote about that in [nitrogen, rain, and starting point estimates]({{< relref "/post/nitrogen-rain-starting-point-estimates" >}}).

For the N mineralized from organic matter, keep in mind that one wants to measure the humus in the soil, after all the living and dead undecomposed plant material has been removed from the soil. I explained this at length in [A Tale of Two Tests]({{< relref "/post/tale-two-tests-soil-organic-matter" >}}) and I recommend reviewing that to understand what is being reported as organic matter on soil tests.

### How this works for me

I've found that for the majority of sites, the N added as fertilizer is the largest amount. N in precipitation can usually be ignored but it is something to check. N in irrigation water is usually negligible but this can vary *a lot*, to the extreme point where N added in irrigation water is more than the plant could possibly use. I don't usually see N added in topdressing, and that is something that should be picked up with the soil organic matter measurements. And N mineralized from soil organic matter is usually small but not negligible for sand-based rootzones, and is substantial and sometimes even excessive for soils with relatively high organic matter. I also find it useful to measure the [clipping volume]({{< relref "/project/clipvol" >}}) to assess the growth and to make adjustments to N supply based on plant response.

