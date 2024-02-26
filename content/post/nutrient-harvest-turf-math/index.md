---

title: "Nutrient harvest turf math"
subtitle: ""
summary: ""
authors: [admin]
tags: [clipvol, MLSN]
categories: []
date: 2024-02-26T11:51:57-05:00
lastmod: 2024-02-26T11:51:57-05:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
---

A correspondent wrote with this inquiry related to estimating the value "a" in the MLSN fertilizer rate equation.[^1] Specifically, the "a" value is the expected plant use of the element over the time period for which the fertilizer recommendation is being made. 

[^1]: That equation takes the amount of an element that we need, subtracts the amount we have, and the difference between *need* and *have* is the amount that needs to be added as fertilizer. The amount needed is composed of two parts, and I express them algebraically as "a" and as "b". The "a" amount is the expected plant use---we need to ensure the grass gets the amount the grass uses. The "b" amount is the extra amount to keep in the soil. The "c" amount is the amount we have, which is the current soil test value for that element. For more about this, see the [MLSN cheat sheet](/post/new-mlsn-cheat-sheet/).

Here's the inquiry:

> I am having trouble wrapping my head around the "a" variable in the equation a + b - c = Q

> I read through your [MLSN] [cheat sheet](/post/new-mlsn-cheat-sheet/) but have been getting weird numbers when calculating the ppm value for "a".

This is how I replied:

> Hmm, there are a lot of different ways to come up with an answer.

> I usually don't add and subtract ppm. My end goal is to make a fertilizer recommendation in mass of element per area of land, so I generally convert ppm to mass/area units and add and subtract those.

> If I do that, I know how much area my 1 L of clippings has come from. That puts the K use already in units of mass/area.

> You've done it correctly to get 1.26 g of K in 1 L of clippings. At that point, however, rather than expressing back into the 1 L of clippings, I would be dividing the 1.26 g of K by the area from which the 1 L was harvested from

> For example, let's say my annual harvest of clippings was 2.2 L per square meter.

> That is estimated to have a dry mass of 2.2 L * 0.063 = 0.1386 kg = 139 g.

> I expect the leaves to be about 2% K, so that will be 139 * 0.02 = 2.8 g of K

> And this is from one square meter. So my "a" value if calculating this for a time duration of one year is 2.8 g per square meter, or approximately 0.6 pounds per 1000 square feet.

> As far as expressing that in ppm, the way that I'd do it is express not as ppm in the clippings, but as ppm in the soil. The soil mass of 1 square meter of a sandy rootzone to a 10 cm depth I estimate to be 150 kg. This amount of K, then, would be, in soil ppm units, a 2800 mg/150 = about 19 mg/kg = 19 ppm.

> That is, the K in those clippings would have reduced soil K by about 19 ppm.

> It takes a bit of practice but once the conversions have been done a few times, I trust it will make sense and be repeatable for you. 



