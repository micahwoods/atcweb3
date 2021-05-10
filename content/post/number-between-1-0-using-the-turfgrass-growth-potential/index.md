---
title: 'A number between 0 and 1: using the turfgrass growth potential'
authors: [admin]
date: 2014-07-29T14:59:00+00:00
lastmod: 2021-05-10
tags:
  - China
  - Climate
  - Fertilizer
  - Growth potential
  - Temperature
image:
  preview_only: true
math: true
---

Every turf manager knows that temperature has a huge influence on the growth rate of the grass. Consequently, mowing, fertilizing, overseeding, winter dormancy, heat stress of cool season grasses, and much more are all directly influenced by temperature.

I find it especially convenient to make use of the turfgrass growth potential (GP), a number between 0 and 1 that represents the proximity of the actual temperature to the optimum temperature for growth. The turfgrass GP was developed by Wendy Gelernter and Larry Stowell at [PACE Turf](https://www.paceturf.org/) and their 2005 *GCM* article about GP is on my list of [5 articles every greenkeeper should read]({{< relref "/post/five-articles-every-greenkeeper-should-read" >}}).

{{< figure src="gcm_china_gp.png" >}}

The turfgrass GP was the topic of my turfgrass talk column in the July/August 2014 issue of *GCM China*. In the article, I explained what GP is:

> By expressing the temperature as a number between 0 and 1, we can get an idea of how much the grass has the potential to grow based on how close the actual temperature is to the optimum temperatures for growth ... At frst glance it might look complicated, but it is actually quite simple. There is a minimum value of 0 if the actual temperature is very different from the optimum growth temperature. A maximum value of 1 means the actual temperature is the same as the optimum growth temperature. The GP value, then, is simply a number that says how close the actual temperature is to the optimum temperature.

Download **Turf growth and temperatures** [in Chinese](https://www.files.asianturfgrass.com/201407_gcmchina_cn.pdf) or [in English](https://www.files.asianturfgrass.com/201407_gcmchina_en.pdf).

{{< figure src="gp_chart.png" caption="The growth potential (GP) of cool-season (C3) and warm-season (C4) grasses varies between 0 and 1 based on the optimum growth temperatures." >}}

You can get the equation to calculate GP from temperature by downloading the [PACE TURF climate appraisal forms](https://www.paceturf.org/public/ipm_planning_tools), or make the calculation yourself using the growth potential equation:

$GP = e^{-0.5(\frac{t-t_o}{var})^2}$

where, $GP$ is growth potential, a value from 0 to 1; $e$ is the base of the natural logarithm, approximately 2.71828; $t$ is the actual mean temperature; $t_o$ is the optimum temperature, typically set at 20°C for C<sub>3</sub> grass and $\ge$ 31°C for C<sub>4</sub> grass; and $var$ is the variance which adjusts the shape of the curve, 5.5 for C<sub>3</sub> species and 7 for C<sub>4</sub> species when using °C.

An alternative expression of the equation generates the same result.

$GP = \frac{1}{e^{{0.5}(\frac{t-t_o}{var})^2}}$
