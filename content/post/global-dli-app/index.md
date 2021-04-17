---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A global DLI app"
subtitle: "This app produces a summary chart of photosynthetically active radiation (PAR) expressed as the daily light integral (DLI) for anywhere in the world"
summary: ""
authors: [admin]
tags: 
- light
- climate
- web/tech
- rturf
categories: []
date: 2021-01-28T15:39:14+07:00
lastmod: 2021-01-28T15:39:14+07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Downloadable app summary chart for Ithaca, New York"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

I made a [Global DLI app](https://asianturfgrass.shinyapps.io/global_dli/) to generate summary charts of DLI for anywhere in the world. 

This app uses the [`nasapower`](https://docs.ropensci.org/nasapower/index.html) R package to get satellite data from the [NASA POWER Agroclimatology dataset](https://power.larc.nasa.gov/).

Some results are shown within the app, but they are not formatted for perfect display on a phone or computer. I did attempt to add some formatting for the downloadable summary charts which you get to at the end of the app. 

That was my objective, to make a downloadable summary chart (like these representative ones shown below for Cairo, Cape Town, New York City, and Tokyo). I hope you'll find this useful. And I hope there aren't too many bugs!

{{< figure library="true" src="cairo_dli.jpg" >}}

{{< figure library="true" src="cape_town_dli.jpg" >}}

{{< figure library="true" src="nyc_dli.jpg" >}}

{{< figure library="true" src="tokyo_dli.jpg" >}}





