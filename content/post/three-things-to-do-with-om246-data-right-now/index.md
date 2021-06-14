---
title: "Three things you can do right now with OM246 data"
subtitle: ""
summary: ""
authors: [admin]
tags: 
- organic matter
- OM246
- sand topdressing

categories: []
date: 2021-06-14T10:47:11+07:00
lastmod: 2021-06-14T10:47:11+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

---

You can use OM246 test results to learn how total organic matter compares to general recommendations; better yet, you can evaluate how maintenance practices, growth, weather, and decomposition are changing total organic matter at a single site; and then there is what I call the killer feature of this testing: you can make a precise and site-specific calculation of organic matter accumulation rate and sand topdressing requirement.

Frank Rossi and Roch Gaussoin talked about this on the [Cornell Turfgrass Show](https://youtu.be/DkydFXvoZD8?t=1015) and suggested that these tests are going to be really useful, presumably at some time in the future. When Rossi says "I'm not presuming [the test results] can tell us anything yet" and Gaussoin says "I don't think the data is clear on that yet," they are underselling the utility of these data **right now**. 

If you have this information---total organic material, or total organic matter, from a known depth below the soil surface---here are three incredibly effective things you can do right now.

### Adjust maintenance work to move OM closer to generalized target ranges

[Glasgow et al.](https://tic.msu.edu/tgif/flink?recno=106346) have recommended maximum total organic material[^1] of 6% at the 0 to 2 cm depth, 4% at the 2 to 4 cm depth, and 3% at depths below that. These recommendations were based on a survey of golf greens in New Zealand, and the maximum values were determined "based on the correlation between organic matter content and other parameters, in particular hydraulic conductivity."

[^1]: This total organic material is distinct from soil organic matter. Soil organic matter by definition excludes undecomposed living and dead plant material. In the case of managing the organic matter at the surface of turf swards, the total organic material is something we want to look at.

{{< figure src="isaac_presentation_om2.jpg" caption="Four slides from Steve Isaac's presentation on Sustainable Golf Course Maintenance." >}}

These same maximum levels have been used with success in the UK as well. 

{{< figure src="isaac_om2_slide.jpg" caption="The target range for OM2 (total organic material from the surface to 2 cm below the surface) at links courses is 4 to 6%." >}}

Steve Isaac, in a series of seminars I saw in 2016 and 2017, shared composite data from Open Championship venues where the OM2 data were moved into the target range. And desired playing conditions followed.

That's one thing you can do, trying to manage the total organic material in these recommended ranges.

Bob Carrow did extensive research on organic matter in sand-based rootzones and recommended an upper limit of [4% OM in the top 2 inches](https://usgatero.msu.edu/v02/n17.pdf) of the rootzone. One can also use the OM246 data to check the value at that depth too; I do this by making the exact calculation down to 4 cm and then doing a linear estimate for OM from 4 to 5.08 cm (the 2 inch depth) based on the slope between OM4 and OM6 measurements.

### Evaluate the effect of maintenance work (and everything else that affects OM dynamics) at your site

One can consider those recommended maximum levels as a guide, and then evaluate how the grass is performing at a site before trying to adjust the OM. If the surface firmness and the water holding characteristics of a rootzone are fine, then it makes sense to keep the OM constant at approximately that level, rather than trying to change it to a general target range.

{{< figure src="keya_11_om246.jpg" caption="Example data from a golf green showing an increase in OM2 and OM4 over three growing seasons. It's clear from these data that the organic material is accumulating faster at these depths than it is being removed, diluted, or decomposed." >}}

If the surfaces have the desired level of firmness (ball reaction) and water holding characteristics, then one would like to keep OM constant over time. If the surfaces need to be softer and to hold more water, let the OM go up. If the surfaces need to be firmer and drier, adjust the work to make the OM go down.

I'd use the guidelines for OM246 maxima and the Carrow 2 inch maxima as starting point levels, but then get more site specific.

### Calculate the site-specific OM accumulation rate and sand topdressing requirement

I made a calculator[^2] that will find the organic matter accumulation rate for site-specific conditions, and given a desired organic matter level to a particular depth at some date in the future, will use that accumulation rate to make a sand topdressing recommendation.

[^2]: The [OM246 Shiny App](https://asianturfgrass.shinyapps.io/om246/)

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.1/iframeResizer.min.js"></script>
<style>
  iframe {
    min-width: 100%;
  }
</style>
<iframe id="myIframe" src="https://asianturfgrass.shinyapps.io/om246/" scrolling="no" frameborder="no"></iframe>
<script>
  iFrameResize({
   heightCalculationMethod: 'lowestElement'
  });
</script>

The point of all this is to make sure one is doing enough work to manage the surface conditions, without doing a single bit of unnecessary surface disruption. There is certainly more to be learned from ongoing research, but one can make better decisions right now with these data.
