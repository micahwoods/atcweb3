---
date: "2020-03-03T00:00:00Z"
tags:
- MLSN
- potassium
- web/tech
- soil test
- rturf
title: Updated K calculator
authors: [admin]
image:
  preview_only: true
---

I made a few small updates to the [MLSN K calculator](https://asianturfgrass.shinyapps.io/mlsn_K/). This was the first Shiny app I made, back in 2014. You can see all of them---the Turf Twitter ones, the Hargreaves ET calculator, irrigation requirement demos, PACE Turf's GP avatar generator, and more, at the [ATC Shiny apps page]({{< relref "/shiny-apps" >}}).

With the K calculator, you select the grass species and the soil test K and choose how much N you intend to apply. The calculator then determines an annual K rate that will keep the soil above the MLSN guideline.

{{< figure src="mlsn_k_calculator.jpg" >}} 

There is a diagonal dashed blue line displayed on the chart. The annual K fertilizer recommendation is displayed at some point on that line, depending on the selected grass type, soil test K, and annual N. The line itself goes down with increasing soil K, and up with decreasing soil K.

The line shows how the K fertilizer requirement will change with soil K, given a particular grass species and annual N application. 
