---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Shiny Apps"
summary: "Web applications for `R` that make calculations or show data."
authors: []
tags: 
- R
- rturf
categories: [rturf]
date: 2021-01-03T14:39:56+07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: Smart
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com/asianturfgrass
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

[Shiny](https://shiny.rstudio.com/) is a web application framework for R. These Shiny apps make calculations, or generate charts, to provide answers or comparisons about fundamental turfgrass management practices.

### [Evapotranspiration (ET) calculator](https://asianturfgrass.shinyapps.io/ET_calculator/)

Returns the reference and crop evapotranspiration for a day given inputs of latitude, maximum and minimum air temperatures, and crop coefficient. Based on the Hargreaves equation.

### [Sustainability index](https://asianturfgrass.shinyapps.io/turfsi/)

Returns the sustainability index (SI) based on soil test inputs. This is a direct comparison of input soil test results to the MLSN data.

### [MLSN K fertilizer calculator](https://asianturfgrass.shinyapps.io/mlsn_K/)

Calculates the fertilizer K requirement given inputs of grass species, soil test K, and annual N rate. A diagonal line on the chart displays how the fertilizer K will change based on the amount of K in the soil.

### [Turf Twitter in 2019](https://asianturfgrass.shinyapps.io/turf_twitter_2019/)

This app shows searchable calculations and rankings related to turfgrass industry Twitter accounts in calendar year 2019.

### [Turf Twitter in 2018](https://asianturfgrass.shinyapps.io/turf_twitter_2018/)

This app shows searchable calculations and rankings related to turfgrass industry Twitter accounts in calendar year 2018.

### [Turf Twitter in 2017](https://asianturfgrass.shinyapps.io/turf_twitter/)

This app shows searchable calculations and rankings related to turfgrass industry Twitter accounts in calendar year 2017.

### [Irrigation requirement at Manila, Cebu, and Baguio: 2013 to 2016](https://asianturfgrass.shinyapps.io/irr_ph/)

Calculates the daily soil water balance using precipitation and evapotranspiration data for three locations in the Philippines, matching a user-specified set of irrigation *rules*.

### [Irrigation requirement by daily soil water balance](https://asianturfgrass.shinyapps.io/irrigation/)

Calculates the quantity of irrigation water required to satisfy a user-selected set of soil and irrigation conditions.

### [Sunshine and temperature in Japan](https://asianturfgrass.shinyapps.io/jp_sun_temperature_chart/)

Plots the combination of climatological normal sunshine and temperature for 11 cities in Japan. This combination of sun and temperature gives an indication of the growing environment for turfgrass at different locations.

### [PPFD by time, date, and location](https://asianturfgrass.shinyapps.io/ppfd_by_time/)

Returns the expected photosynthetic photon flux density (PPFD) for a second within any specified minute, given inputs of latitude, longitude, date, and time. Also returns expected daily light integral (DLI) at that location if it is sunny all day.

### [ET（蒸発散値: 標準 ETと特定作物 ET）計算機](https://asianturfgrass.shinyapps.io/et_calc_jp/)

このプログラムは、標準蒸発散値(ETo) を、年月日、緯度、その日の最高気温と最低気温を基にしてmm 単位で計算します。算出された ETo に、作物係数を乗算すると、 その作物の蒸発散値（ETc）が求められます。これらの計算はHargreaves の ETo

### [MLSN ガイドラインからK要求量を求める](https://asianturfgrass.shinyapps.io/jp_mlsnK/)

ここでの計算は、持続可能な最低栄養 （MLSNガイドライン） をベースとしています。

### [Make a GP avatar for your location](https://paceturf.shinyapps.io/GPAvatar/)

This app from [PACE Turf](https://www.paceturf.org/) generates a downloadable avatar that shows two lines -- blue and red. Blue is the cool-season growth potential through the year, and red is the warm season growth potential. 
