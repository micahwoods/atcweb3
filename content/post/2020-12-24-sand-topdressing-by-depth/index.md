---
date: "2020-12-24T00:00:00Z"
share-media: https://www.asianturfgrass.com/media/sand_by_depth.jpg
tags:
- sand
- topdressing
- turfhacks
title: 'Sand topdressing by exact depth: how to work it out'
---

Today I explained the same calculation about sand topdressing for the third time, so I need to write a blog post on this topic. 

This is following the method of [David Robinson](https://twitter.com/drob/status/928447584712253440?s=20), who says when you've written the same code 3 times, write a function; when you've given the same advice 3 times, write a blog post; and when you've done the blog post 3 times, write a book.

The [best way to express sand topdressing amount](https://www.asianturfgrass.com/2019-08-08-three-reasons-sand-depth/), standardized so it makes sense to anyone in the world, is as a depth. I've generally figured that out by taking the volume of sand applied, divided by the area to which it was applied, and making a correction for overthrow.

The USGA has produced [this video](https://youtu.be/7tPilHP5QiA) showing an exact way to measure sand topdressing application rate, with no need for the overthrow correction, and this measures in mass. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/7tPilHP5QiA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You could, of course, figure out the volume by looking at the volume displacement when the sand is added to a known amount of water. But we can also assume that the sand has a bulk density (when dry) of about 1.5 g/cm<sup>3</sup>. I generally use 1.5. That's a common conversion factor for sand-based rootzones used in turfgrass. In civil engineering I think sand is often assumed to have a bulk density of 1.63 g/cm<sup>3</sup>. Whether you use 1.5 or 1.63 or something close to either of those, we are going to be within about 10% of the real number.

If one measures the mass of sand applied to a known area, the depth calculation is simple. I do this in metric units, because I want to express the depth in mm, which is going to give a number between 0 and about 35; I've never met a turfgrass manager who applies more than 35 mm of sand per year (about 115 ft<sup>3</sup>/1000 ft<sup>2</sup>). 

You have a collection container of known dimensions. Let's say it happens to be 2,000 cm<sup>2</sup>, and in that container you've collected 400 g of sand.

To express that in mm, we want to convert the mass to a volume, and then divide by the area. Volume divided by area gives depth. I'm going to work with a bulk density of 1.5.

$$ 10(\frac{\frac{400}{1.5}}{2000}) = $$ sand depth of 1.3 mm

Take the mass in grams, divide by the bulk density and the area to which the sand was applied in cm<sup>2</sup>, and multiply by ten. That gives the depth in mm. You can adjust the equation as necessary if you wish to use other units.
