---
title: Shade and sun
authors: [admin]
date: 2016-05-17T20:20:13+00:00
tags:
- light
image:
  preview_only: true

---

Shade from trees will often reduce the photosynthetically active radiation (PAR) by about 80%. For example, the area in full sun on this green had a photosynthetic photon flux density (PPFD) of 749 micromoles of photons per square meter per second.

{{< figure src="featured.jpg" >}}

An adjacent area on the same green, but in tree shade, had a PPFD of 139.

{{< figure src="p2.jpg" >}}

It is possible to make a good estimate of the effect of shade, and to know just how much PAR is reaching the turf, without using a meter. Take this putting green, for example, with part of it in sun and part in tree shade.

{{< figure src="p3.jpg" >}}

The PPFD in sun (with no clouds) can be estimated by knowing the day of the year, the time of the day, the latitude, and the longitude. [This Shiny app](https://asianturfgrass.shinyapps.io/ppfd_by_time/) makes the calculation based on those inputs. The calculated PPFD by that app is pretty close to the measured PPFD. Here are some calculated PPFDs compared with measured PPFDs from sites in full sun, unobstructed by clouds.

{{< figure src="ppfd_predicted_vs_measured.png" >}}

If you are in full sun with no clouds, then you can get a good estimate of PPFD [from the app](https://asianturfgrass.shinyapps.io/ppfd_by_time/).

If there is tree shade, I'd assume that the PPFD in shade is 20% of that in full sun.

If there are clouds, I'd look for my shadow and look for the sun, to get an estimate of how much the clouds are reducing the PAR, [as described here]({{< relref "/post/rule-of-thumb-for-cloud-effect-on-par" >}}).
