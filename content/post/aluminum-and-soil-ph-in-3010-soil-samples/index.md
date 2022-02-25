---
title: "Aluminum and soil pH in 3,010 soil samples"
authors: [admin]
date: 2017-03-25T16:13:10+00:00
tags:
- soil test
- pH
image:
  preview_only: true

---

Even though high quality turfgrass can be produced below a soil pH of 5.5, for standard situations I will recommend keeping soil pH at 5.5 or above. Soluble aluminum will be negligible above pH 5.5. Below pH 5.5, there is a lot more soluble aluminum, and this can damage roots. A second reason for keeping the pH at 5.5 or above is to make sure the growth of fungi and bacteria in soil proceeds [without too much restriction](https://dx.doi.org/10.1128/AEM.02775-08). These fungi and bacteria decompose organic matter, and I'd rather not restrict that too much with low pH.

I was writing an article about this, and I wanted to make a chart to show how the aluminum is high at pH less than 5.5 and how aluminum is almost 0 above that pH. I wanted a quick set of data to make this chart, and I remembered that I had [a file with 3,101 soil test results](https://github.com/micahwoods/2016_mlsn_paper/tree/master/data#atc-data) as [part of the MLSN project](https://micahwoods.github.io/2016_mlsn_paper/). Of those samples, 3,010 had 1 _M_ KCl extractable aluminum data, and all had pH. So I plotted the relationship between pH and aluminum, and I did it in two different ways.

The soil pH was measured in the standard way, with 1 part of soil mixed with 1 part of deionized water, the solution is stirred, and then the pH is measured in the solution. The pH is the negative logarithm (base 10) of the hydrogen ion activity in the solution. If the hydrogen ion activity is 10<sup>-1</sup>, or 0.1, the pH is 1. If the hydrogen ion activity is 10<sup>-5</sup>, or 0.00001, the pH is 5. The higher the pH, the lower the hydrogen ion activity.

I wanted to see how the soil aluminum changed when plotted against {H<sup>+</sup>} directly.

{{< figure src="soil_ph_aluminum.jpg" >}}

That's not especially clear. But it is when those same data are plotted not as {H<sup>+</sup>} directly, but as pH. 

{{< figure src="featured.png" >}}

Now with that chart it is clear that when pH is 5.5 or less, the aluminum might be high. When the soil pH is above 5.5, the aluminum will almost never be high, and thus will almost never be a problem.
