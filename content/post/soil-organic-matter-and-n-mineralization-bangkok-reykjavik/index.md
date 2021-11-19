---
title: "Soil organic matter and N mineralization"
subtitle: "I calculated 5x more mineralization in Bangkok than in Reykjavik"
summary: ""
authors: [admin]
tags: 
- nitrogen
- organic matter
- Thailand
- Iceland
- soil test
categories: []
date: 2021-11-19T15:18:26+07:00
lastmod: 2021-11-19T15:18:26+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

I've been making estimates of N mineralization from soil organic matter for the past few years using the method described by Gilmour and Mauromoustakos in [Nitrogen mineralization from soil organic matter: a sequential model](https://doi.org/10.2136/sssaj2010.0123). I use these estimates as an approximate value for how much N may be mineralized at a particular time of year.

I recently saw some soil test measurements for putting greens at Ness Golf Club in Reykjavik, and I was struck by how high the soil organic matter was. For putting greens, the average value[^1] for soil organic matter to a 10 cm depth is 1.6%. The samples from Ness GC had an average greater than 3%.

[^1]: The average for the 100 putting green samples in the [Global Soil Survey](https://osf.io/rg49p/) was 1.6%.

{{< figure src="ness_birds_may.jpg" caption="Birds at Ness Golf Club in Reykjavik, May" >}}

Ah, I thought, this is really interesting. The low temperatures in that climate would lead to low mineralization rates. I thought it would be interesting to run the N mineralization model for Reykjavik temperatures and for a tropical climate like Bangkok. So I did.

{{< figure src="featured.jpg" caption="A deer (on a day with multiple birdies) at Bangkok Golf Club, January" >}}

I used daily temperatures for 2020 at both locations. I simulated the mineralization assuming the soil started with 3% organic matter (30 g/kg). 

There was 5.3 times[^2] more mineralization predicted at Bangkok GC than at Ness GC. From a starting OM of 30 g/kg at both locations, the model calculated an ending OM of 29.7 g/kg at Ness and 28.2 g/kg at Bangkok. I get the N numbers from assuming 5% N content of soil organic matter. Note that the calculation here is the mineralization in isolation, without adding any soil organic matter from plant growth. 

[^2]: Calculated from these rounded numbers it appears to be 6 times more, but the exact value when I include more decimal points is 5.3.

You can get rough--very rough--estimates of N mineralization by the expectation that from 1.5 to 4% of the total soil organic matter (SOM) will be mineralized each year. In this example, the temperatures are such that the model I used has 1% of the SOM mineralized at Reykjavik in a year and 6% of the SOM mineralized at Bangkok. For climates with temperatures cooler than Bangkok and warmer than Reykjavik, the annual value will often be in that textbook 1.5% to 4% range.

To get the actual N, one must account for soil bulk density and can assume that the SOM is 5% N. For example, a soil with 3% SOM to a depth of 10 cm and a bulk density of 1.4 g/cm<sup>3</sup> would have a mass of 140 kg in 1 square meter to a 10 cm depth. 

Of that 140 kg, 3% is SOM, or 4,200 g. Of those 4,200 g of SOM, 5% is N, or 210 g. Then figure perhaps 2.75% of that is mineralized in a year. That's 5.8 g N/m<sup>2</sup> (about 1.2 lbs N/1000 ft<sup>2</sup>) expected to be mineralized in a year.

