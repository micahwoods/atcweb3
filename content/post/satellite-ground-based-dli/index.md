---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Comparing satellite and ground-based measurements of DLI"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- Light
categories: []
date: 2021-02-03T17:05:23+07:00
lastmod: 2021-02-03T17:05:23+07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Micah Woods and Tom Cook on a sunny late August day in Corvallis, Oregon"
  focal_point: "Top"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

You've seen the [Global DLI app](https://asianturfgrass.shinyapps.io/global_dli/) that uses satellite data from the [NASA POWER Agroclimatology dataset](https://power.larc.nasa.gov/docs/methodology/communities/ag/) to show a summary of photosynthetically active radiation---expressed as the daily light integral, or DLI---for the past year at any location.

{{< figure library="false" src="corvallis_dli.jpg" title="A year of satellite-based DLI for the 0.5° latitude by 0.5° longitude grid encompassing the [USCRN site just south of Corvallis, OR](https://www.atdd.noaa.gov/u-s-crn-groups-map/northwest_group_map/or-corvallis/)." >}}

Have you wondered how the satellite measurements of DLI compare with ground-based measurements of the same thing? I looked up data for some locations in the USA.

The NASA POWER data are on 0.5° by 0.5° grid, while the ground-based measurements are at a single weather station within a grid. I downloaded daily measurements for the year 2020 from six [US Climate Reference Network (USCRN) stations](https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/us-climate-reference-network-uscrn) and also got the NASA POWER daily measurements for the grid section containing each station. 

{{< figure library="true" src="dli_daily_2020.jpg" title="DLI for six locations in the USA in 2020 measured by satellite and by ground-based sensors." >}}

The root mean square error (RMSE) in 2020 at these six locations ranged from 3.8 mol m<sup>-2</sup> d<sup>-1</sup> at Yuma to 5.7 mol m<sup>-2</sup> d<sup>-1</sup> at Everglades City. 

On a monthly basis in 2020, the RMSE ranged from 1.5 in Ithaca to 3.5 in Corvallis. 

{{< figure library="true" src="dli_monthly_2020.jpg" title="Monthly average DLI for six locations in the USA in 2020 measured by satellite and by ground-based sensors." >}}

There is a slight bias with the satellite measurements to report a higher DLI at these locations. 

The satellite measurements look pretty accurate to me. On a daily basis, I expect the satellite-based DLI for the encompassing grid will be, more often than not, within 5 mol m<sup>-2</sup> d<sup>-1</sup> of the actual DLI on the ground at a single location within that grid. And when looking at the average over time, the DLI by satellite is going to be even more accurate.



