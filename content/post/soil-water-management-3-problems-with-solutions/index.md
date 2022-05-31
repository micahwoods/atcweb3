---

title: "Soil and water management: 3 primary problems, with solutions"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- irrigation
- water
- salinity
- fertilizer
categories: []
date: 2022-05-31T17:09:33+07:00
lastmod: 2022-05-31T17:09:33+07:00
featured: false
draft: false

math: true

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

Here are three primary things to be concerned with when considering soil and water: salinity, the sodium hazard, and nutrient deficiencies. I explain solutions for each of these problems in this post, which was originally a handout for a seminar I gave on this topic some years ago.[^1]

[^1]: I gave a presentation entitled *Soil and Water Management: 3 problems, 3 solutions* on 10 March 2014 at the Sustainable Turfgrass Management in Asia conference in Pattaya, Thailand. I've had this handout up on a sub-domain of the ATC website but I refer to it occasionally and wanted to put this onto the main site.

{{< figure src="featured.jpg" caption="Water pressure and irrigation coverage---that's another thing that one needs to get right, but I don't discuss that in this post." >}}

### Salinity

Warm-season grasses such as bermudagrass (*Cynodon* spp.), seashore paspalum (*Paspalum vaginatum*), and zoysiagrass (*Zoysia* spp.) are relatively tolerant of salt in applied irrigation water. However, if the salt applied through the irrigation water accumulates in the soil, the grass can fail. 

The amount of salt in a solution is reported in two ways - as the electrolytic conductivity (EC, in units of decisiemens per meter, dS/m), or as the total dissolved solids (TDS, in units of parts per million, ppm). There is an empirical relationship between these two units. Each unit increase in EC of 1 dS/m will be roughly equivalent to an increase of about 640 ppm in TDS units.

The salinity of two different solutions must be evaluated. First, one needs to know the salinity of the irrigation water. This is represented as EC$_w$, for the EC of *water*. Grass can tolerate a wide range of EC$_w$, but each grass plant is actually growing in the soil. To assess the amount of salt in the soil, a saturated paste extract is taken from the soil, and the salinity of that solution extracted from the soil is measured and reported as EC$_e$, for *extract* from the soil.

There is no cutoff point for EC$_w$, but when EC$_e$ is too high, even the most salt-tolerant of warm-season grasses will die. The initial effect of increasing EC$_e$ is reduced turfgrass growth. There will be difference among turfgrass varieties within these species, but salt tolerance (safe levels) for *Cynodon* spp., *Zoysia* spp., and *Paspalum vaginatum* are sometimes given as 8, 8, and 12 dS/m, respectively.

That is, we can expect those grasses to tolerate levels of soil salinity (EC$_e$) up to those levels, but above those levels, there will be some risk of turfgrass damage. The objective in turf management, then, is to manage the soil salinity at or below those levels. This is done by leaching. In irrigated turf, leaching can be accomplished by applying more water than the grass can use. If turfgrass consumptive water use is represented as ET (evapotranspiration) in units of mm/day, then any addition of water in excess of the amount used will cause water to leach below the rootzone, with that extra water containing some dissolved salts.

There is a two step process to calculate the amount of water that must be applied in order to manage the EC$_e$ at a safe level. First, calculate the leaching requirement using this equation.

\begin{equation}
LR = \frac{EC_w}{5EC_e - EC_w}
\end{equation}

where ...

**LR** is leaching requirement, **EC$_w$** is electrolytic conductivity of the irrigation water, and **EC$_e$** is electrolytic conductivity of the soil extract at a level the grass can tolerate.

Second, relate that leaching requirement (LR) to the grass's use of water (ET), and calculate the water requirement, using this equation:

\begin{equation}
Water Requirement = \frac{ET}{1 - LR}
\end{equation}

For more information, see [Leaching for Maintenance](http://arizona.openrepository.com/arizona/bitstream/10150/146964/1/az1107-1999.pdf) from the University of Arizona.

As an example, let's consider an irrigation water with a TDS of 1280 ppm (EC$_w$ of 2 dS/m). Let's imagine we are growing bermudagrass (*Cynodon*), so we want to keep EC$_e$ at 8 dS/m or below. And let's say the ET in our case is 5 mm/day. 

Calculating the LR using the first equation, we get 0.05. Then, using the second equation, we can calculate the water requirement as 5.3 mm. That is, when the ET is 5 mm, using an irrigation water with EC$_w$ of 2 dS/m, we would need to apply 5.3 mm/day in order to maintain the soil (EC$_e$) at or below 8 dS/m. 

Leaching of salts is much easier in sand rootzones.

### Sodium hazard

When soils contain too much sodium, the soil structure can be destroyed through the deflocculation of clay particles. This is not a problem on sand rootzones, but it is a concern on soils containing clay. Soils with more than 15% of the cation exchange sites occupied by sodium (exchangeable sodium percentage, or *ESP*) are termed *sodic* soils. These soils may exhibit hardness, poor water infiltration, and bare areas free of plants.

The solution to this problem is through the addition of calcium, usually in the form of gypsum (calcium sulfate dihydrate, $CaSO_4∙2H_2O$). The calcium replaces the sodium on the exchange sites, which improves the soil structure, and excess sodium can then be leached from the soil.

To calculate how much gypsum must be applied, one must consider how much sodium is on the exchange sites, and how much must be replaced by calcium. Let's imagine a situation where the cation exchange capacity (CEC) of a soil is 100 mmol$_c$/kg. That is, the soil is able to reversibly adsorb 100 millimoles of charge of cations for each kg of dry soil.

And let's imagine that the ESP of this soil is 15%, which is undesirably high. That is, sodium occupies 15% of the soil's cation exchange sites, or 15 mmol$_c$/kg. If we would like to reduce the ESP to 5%, how much gypsum must be applied?

First, we calculate that changing the ESP from 15% to 5% in a soil with CEC of 100 mmol$_c$/kg represents a change of 10 mmol$_c$/kg. So we want to apply that amount of calcium to exchange with and replace the sodium.

Calcium sulfate dihydrate ($CaSO_4∙2H_2O$) has a molecular weight of 172 grams per mole, or 172 g/mmol. But with a +2 charge for calcium, adding 5 mmol of calcium will provide 10 mmol of charge. So we need to add 5 mmol (860 mg) of gypsum for each kg of soil. 

Let's say we want to modify the soil to a depth of 15 cm, and let the soil have a bulk density of 1.5 g/cc. That amount of soil, in an area of 1 square meter, will have a mass of 225 kg. We would need to apply 860 mg of gypsum to each 1 kg, so for the 225 kg in 1 square meter, 194 g of gypsum are required. 

### Nutrient deficiencies

Nutrient deficiencies can be avoided by applying [just what the grass requires](http://bit.ly/1dYlG4I). [This article](http://bit.ly/1dYlG4I) from the January 2014 issue of *GCM* explains how soil tests can be used to ensure the grass is supplied with all the required nutrients.

If soil testing is not done, nutrient deficiencies can be avoided by applying the amount of nutrients that are used by the grass. For a look at how to estimate these, see [Nutrient Requirements of Tropical Turfgrass](http://www.files.asianturfgrass.com/20130311_woods_handout_nutrient_requirements_tropical_turfgrass.pdf).

Adding what the grass uses, without considering the soil nutrient levels, will invariably result in overapplication of some nutrients.

### Additional reading

For irrigation water quality, a concise guide is Harivandi's [Interpreting Irrigation Water Test Results](https://turfgrass.ucr.edu/reports/cal_turf_culture/ctc49_1234.pdf).

A more detailed guide is [Water Quality for Agriculture](http://www.fao.org/docrep/003/t0234e/T0234E00.htm#TOC) by Ayers and Westcot.

Nitrogen requirements can be estimated by growth potential. [This guide](https://files.asianturfgrass.com/201306_growth_potential.pdf) explains how, and the [PACE Turf Climate Appraisal Form](https://www.paceturf.org/journal/climate) works through the calculations for your location. 
