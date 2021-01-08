---
date: "2020-05-26T00:00:00Z"
share-media: https://www.asianturfgrass.com/media/sampling_tublamu.jpg
tags:
- mlsn
- fertilizer
- salinity
- irrigation
title: MLSN and salinity
---

When this question arrived, I thought I could respond by showing a blog post I'd written in the past with the answer.

> "What kind of adjustments would you recommend to do when trying to use the MLSN on a Calcareous sand green profile and irrigation with water saline water with 1500 ppm and Pure Dynasty Sea Shore Paspalum and pH 8????"

But I didn't find a blog post with the answer in any detail, so here's a new one, with the answer to that specific question. This answer is broadly applicable to the question of MLSN and salinity in general.

![salinity damage on the 17th green of the Tublamu GC in Phang Nga, Thailand in September 2005](/media/sampling_tublamu.jpg)
<small><strong>Salinity stress on bermudagrass at Tublamu Royal Navy GC in Phang Nga, Thailand, in September 2005. The course was under renovation after the December 2004 tsunami.</strong></small>

What kind of adjustments would I recommend?

### 1. Manage the salinity 

Salt accumulation in the soil, beyond the tolerance level of the grass, can kill the grass. So that needs to be dealt with. To do that, start by calculating the [leaching requirement](http://www.seminar.asianturfgrass.com/water_and_soil_handout.html).

$$ LR = \frac{EC_w}{5EC_e - EC_w} $$

**LR** is leaching requirement, \\(EC_w\\) is electrolytic conductivity of the irrigation water, and \\(EC_e\\) is electrolytic conductivity of the soil extract at a level the grass can tolerate.

The \\(EC_w\\) in this case is 2.3 dS/m. To convert between total dissolved solids (TDS) and electrolytic conductivity, remember that TDS of 640 ppm \\(\approx\\) 1 dS/m. Thus we get \\(\frac{1500}{640} = 2.3\\) dS/m.

For seashore paspalum, I usually use an \\(EC_e\\) threshold of 12 dS/m. See Harivandi's concise guide to [Interpreting Turfgrass Irrigation Water Test Results](https://anrcatalog.ucanr.edu/pdf/8009.pdf) for more about this.

The leaching requirement in this case is 0.04.

$$ \frac{2.3}{5(12) - 2.3} = 0.04 $$

Use the leaching requirement to find the irrigation water requirement as:

Water Requirement $$ = \frac{ET}{1 - LR} $$.

Let's say the evapotranspiration (ET) in a month is 150 mm. The water requirement would be \\( \frac{150}{1 - 0.04} = 156.25 \\).

That's not too bad, because 1,500 TDS is relatively low salt content for seashore paspalum.

### 2. Next consider the nutrients

One is deliberately leaching salts from the rootzone. I'm not too concerned with soil nutrient levels in this case, and I'd start with disregarding the soil and applying 100% of plant use. This is the [precision fertilisation approach](https://www.blog.asianturfgrass.com/2015/04/2-similar-approaches-to-fertilisation-with-1-notable-difference.html). 

This is almost certainly more than is required, but it is a starting point that guarantees ample nutrients are supplied. That's the basic approach I suggested in the [MLSN cheat sheet](https://www.asianturfgrass.com/2018-02-03-new-mlsn-cheat-sheet/).

[![media of salinty section mlsn cheat sheet](/media/salinity_mlsn_cheat_sheet.png)](https://www.asianturfgrass.com/2018-02-03-new-mlsn-cheat-sheet/)

Adding 100% of plant use is more than required because 1) it disregards the nutrients in the soil completely and 2) it disregards the probably substantial amount of K and Mg and Ca and etc. in the irrigation water. It's likely that the irrigation water, with 1,500 TDS, has [a lot of plant available nutrients in it](https://www.asianturfgrass.com/2020-02-23-before-next-calcium-app-read-this/).

After you've gotten to this point, with the salts being leached systematically, and with a baseline nutrient supply set at 100% of plant use, then I would start reducing the nutrient supply. 

I'd now look at specific ion supply in the irrigation water, and I'd look at soil test data. I'd make the calculations about nutrient supply as described in the [MLSN cheat sheet](https://www.asianturfgrass.com/2018-02-03-new-mlsn-cheat-sheet/), and I'd gradually reduce the nutrient supply to whatever those levels calculated by MLSN are, all the while observing carefully the turfgrass conditions. If the turf performance ever declines while reducing the nutrient supply, then stop, increase nutrient supply a little bit, and there you have the optimum amount for your site and that grass and irrigation water combination.


### 3. I wouldn't worry about calcareous sand

That means there is a lot of calcium in the soil. Seashore paspalum should grow fine. If the grass lacks vigor, you might check the P in the soil and the P in the irrigation water. If both are low, then you might add some P. If the grass is chlorotic, you might look at Fe and Mn or a complete micronutrient fertilizer.


