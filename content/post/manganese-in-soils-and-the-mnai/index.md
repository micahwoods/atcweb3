---

title: "Manganese in soils and the MnAI"
subtitle: "The manganese availability index (MnAI) integrates the soil pH and the Mehlich 3 manganese into a single value"
summary: ""
authors: [admin]
tags: 
- soil test
- manganese
- micronutrients
categories: []
date: 2023-05-12T15:55:25+07:00
lastmod: 2023-05-12T15:55:25+07:00
featured: false
draft: false
math: true

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

Once upon a time, I presented the manganese availability index (MnAI) on soil reports. I also put a line at 45. When the MnAI was less than 45, I recommended Mn application. When the MnAI was above 45, I did not recommend Mn fertilizer.

Then one day I was doing some exploratory data analysis with manganese soil test data and I plotted the Mehlich 3 extractable Mn against the calculated MnAI.[^1]

[^1]: The equation to calculate MnAI takes two variables, pH and the manganese test result from a Mehlich 3 soil test, in ppm. The MnAI is unitless. The equation is: $$\text{MnAI} = 101.7 - 15.2(pH) + 3.75(M3Mn)$$ You can read more about this in [Heckman et al. (2003)](https://doi.org/10.2135/cropsci2003.1395) and in [Mascagni & Cox (1985)](https://doi.org/10.2136/sssaj1985.03615995004900020022x).

{{< figure src="mn_mnai.png" >}}

"Hmm," I thought, "that's a bit more correlated than I thought. Am I providing any extra information by reporting the MnAI instead of the Mn?" For a while, I stopped including the MnAI chart, and switched to the Mn soil test result, applying the [PACE Turf adjustment](https://www.paceturf.org/memberedition/manganese-and-take-all-patch-again) for classifying soil Mn status based on different minimum values depending on soil pH.[^2]

[^2]: Those minimum values range from Mehlich 3 Mn of 8 ppm at soil pH of 5.6 up to Mehlich 3 Mn of 18 ppm at a soil pH of 8.

Some of the soil Mn and MnAI values can be really high! Plotting the full range of the data is misleading---that makes it look like an almost perfectly linear relationship between Mn and MnAI. 

What if I zoom in on the section of the chart above where the MnAI could be less than the recommended level of 45?

{{< figure src="mn_mnai_cut50.png" >}}

Zoomed in like that things look a lot more interesting, and not nearly so linear. Now the effect of soil pH can be seen. Each of these points is a single soil test result with a combination of soil test Mn and soil pH that results in a specific MnAI value. For the exact same soil test Mn value, one can get a different MnAI value, and the reason for that is soil pH. 

Actually, the chart above has multiple soil test results overplotted on the same points. The chart below adds some jitter to the point locations to show these same data in another way, by moving each point slightly to reduce overplotting.

{{< figure src="featured.png" >}}

Now in the next [ATC soil report](https://www.asianturfgrass.com/project/soil-tests/) update, I'm thinking to show both the Mn *and* the MnAI. It helps me to understand soil Mn status by looking at both of these.





