---

title: "A tour of the Global DLI app"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- light
categories: []
date: 2021-09-26T13:06:59+07:00
lastmod: 2021-09-26T13:06:59+07:00
featured: false
draft: false
image:
  caption: ""
  focal_point: ""
  preview_only: true
---

The NASA POWER agroclimatology dataset provides information on a global grid of 0.5° by 0.5°. The [Global DLI app](https://asianturfgrass.shinyapps.io/global_dli/) uses the [`nasapower`](https://docs.ropensci.org/nasapower/index.html) R package to get global solar radiation data from NASA POWER. The app then converts those data to photosynthetically active radiation (PAR) units of daily light integral (DLI), and it produces a chart that summarizes the past year of DLI for the selected location.

{{< figure src="featured.jpg" >}}

In [this video tour of the app](https://youtu.be/6kPkHRVIAww), I show a few things that I often check when I am using it. These include:

* finding the app from the search page on the ATC website
* adjusting the map tiles to find exactly the location I am looking for
* not worrying much about what I see on the screen, and downloading the formatted chart
* often checking the table with the summed number of weeks in the past year within certain DLI ranges
* being aware that data can be downloaded directly from the [NASA POWER data access viewer](https://power.larc.nasa.gov/data-access-viewer/)

{{< youtube "6kPkHRVIAww" >}}

<br>

For more reading about this topic, and to put these numbers into context, I recommend:

* [How much light is enough? Daily light integral requirements for warm-season grasses](https://www.usga.org/content/usga/home-page/course-care/green-section-record/59/16/how-much-light-is-enough--daily-light-integral-requirements-for-.html) by Wherley et al.

* [What the tech? Measuring light for healthier turf](https://www.gcmonline.com/course/environment/news/turfgrass-light-requirements) by Richardson et al.

* [**Light**](https://www.asianturfgrass.com/tag/light/)-tagged posts at asianturfgrass.com
