---
title: Maybe those that soil test are just more likely to fertilize in general?
authors: [admin]
type: post
date: 2016-12-30T13:29:02+00:00
lastmod: 2021-05-30
tags:
  - fertilizer
  - soil test
math: true
image:
  preview_only: true
---

Ryan Goss made a good point in the discussion about how much fertilizer is applied on golf courses.[^1]

[^1]: The original blog post was [That's not how it is supposed to work]({{< relref "/post/thats-not-the-way-it-is-supposed-to-work" >}}).

{{< tweet "814615557756440576" >}}

There are two basic scenarios. 

The first scenario is no soil testing, in which it makes sense to apply the same amount of fertilizer, $F$, as the grass can use, $G$. One doesn't know how much is in the soil, one can assume the soil will supply nothing, and as an equation this can be represented as $F$ = $G$. Maybe add just a little more to be sure. Call it $F = G + 10\\%$. I'd think of this as a hydroponic situation, where the soil can supply nothing.

The second scenario is with soil testing. In this case, the amount of fertilizer to apply should be the amount that the grass will use that cannot be supplied by the soil, $S$. Any amount that is supplied from the soil is not required as fertilizer. In this scenario using soil testing to find what the soil can supply, the amount to apply as fertilizer becomes $F = G - S$. Maybe add just a little more to be sure. Call it $F = G - S + 10\\%$. If the soil can supply nothing, then $S$ is 0 and the equation simplifies to the hydroponic situation described in the first scenario.

With these simple equations, it is apparent that the amount of fertilizer to apply, represented as the value $F$, will always be lower in the second scenario, with soil testing. 

Ryan is correct that those who soil test are probably more likely to fertilize in general. But there is something interesting if we look at the data in [Table 7 from Gelernter et al. (2016)](http://dx.doi.org/10.2134/cftm2015.0225). Phosphorus and potassium are often recommended based on soil tests, but turfgrass nitrogen rates are not based on soil tests. Therefore, I'm going to use the amount of N applied as a baseline estimate of how much more likely soil testers are to fertilize than non-testers.

I use the log percentage (L%) to show the relative changes. More about log percentage at the end.

{{< figure src="featured.png" >}}

I took the average L% increase across all areas of the golf course for each nutrient. A typical 18 hole golf course that soil tests will have an 18 L% increase in nitrogen rate compared to a typical golf course that doesn't soil test. Because nitrogen is not based on soil tests, I'll pick that number and say that the overall increase in fertilizer from those who soil test is likely to be 18 L% more than those who don't soil test, based on what Ryan pointed out. 

Then I move to phosphorus and potassium and compare them to the 18 L%. Phosphorus and potassium recommendations are based on soil tests, so if they increase by about 18 L% too, then we can't say soil tests have anything to do with it. Phosphorus fertilizer (shown as P<sub>2</sub>O<sub>5</sub>) was variable. The average was a 19 L% increase when soil testing, but there was a wide uncertainty interval around that estimate. 

Potassium had an average increase of 39 L%. Even if the typical golf course that soil tests is already likely to apply 18 L% more fertilizer in general, that baseline increase does not explain the 39 L% increase in potassium fertilizer. 

---

Why **log percentage (L%)**? This is described in [Törnqvist et al. (1985)](https://dx.doi.org/10.1080/00031305.1985.10479385) as "the only symmetric, additive, and normed indicator of relative change."

I didn't want to compare the absolute amounts of N, P, and K applied, because it is normal that one will apply more N than K, and more K than P. Saying the soil testing sites used half a pound more N (it was 0.4875 lbs more, to be exact) than the sites that didn't soil test is fine. Then I can also say that the soil testing sites used 0.16 pounds more P<sub>2</sub>O<sub>5</sub> than did the sites that didn't soil test. Both those statements are correct. But that's not exactly what I want to compare. I don't want the absolute difference. I can't compare the half pound of N to the 0.16 pound of P. What I'm interested in is the relative change.

I could use the usual percentage, but that has problems too. The sites that soil tested used 3 lbs of N on average. $\frac{3}{2.5} = 1.2$. 3 is 120% more than 2.5. A 20% increase. So is that also a 20% decrease? 20% of 3 is 0.6. That's not symmetric. And $\frac{2.5}{3} = 0.833$. So is it a 17% decrease then? Or a 17% increase? It is confusing.

The log percentage solves this. $\log_e(\frac{3}{2.5}) = 0.182$. An 18.2 L% increase. $\log_e(\frac{2.5}{3}) = -0.182$. An 18.2 L% decrease. Very convenient.
