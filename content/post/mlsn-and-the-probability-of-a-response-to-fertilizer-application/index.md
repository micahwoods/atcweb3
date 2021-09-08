---
title: MLSN and the probability of a response to fertilizer application
authors: [admin] 
date: 2016-09-02T10:46:02+00:00
lastmod: 2021-09-08
tags:
  - fertilizer
  - MLSN
image:
  preview_only: true
---

In a series of [quotes about BCSR](https://twitter.com/i/events/990126939061940224?s=20), this conversation ensued.

Allan Dewald asked about MLSN, and [Travis Shaddox brought up the probability of response](https://twitter.com/TravisShaddox/status/770057081869205505).

{{< figure src="tweet.jpg" >}}

We won't provide a response probability for MLSN because it is not a fertilizer calibration. 

### What MLSN *is*

MLSN is a method for interpreting turfgrass soil test results, based on an analysis of thousands of soil samples in which turfgrass is producing a good surface. MLSN is developed from thousands of soil test results in which turfgrass performance was fine.

This is a paraphrase of what we wrote in the [MLSN preprint](https://peerj.com/preprints/2144/):

> Traditional soil test calibration for turfgrass is impossible and will never be done. It is impossible because turfgrass is a global crop, with many species and varieties used, in thousands of soil types, in every possible climate, across a range of turfgrass performance requirements. MLSN is a method which allows turf managers to ensure their turf is always supplied with enough nutrients.

For the full details of what MLSN is, and to see the data supporting it, please read the paper.

### Turfgrass and traditional fertilizer calibration

Now to elaborate on why I think probability of a fertilizer response is not the right way to do calibration for turfgrass, and why MLSN works even though it is not a traditional fertilizer calibration.

{{% callout note %}}

I gave a presentation about this topic at the European Turfgrass Conference in 2018. You can watch my [recorded screencast video](https://youtu.be/D-jgOUcgglY) of the presentation, or scroll through the [slides](https://speakerdeck.com/micahwoods/turfgrass-fertiliser-recommendations-with-or-without-soil-tests). 

{{% /callout %}}

Calibration is based on classifying soils with different levels of nutrients into categories based on probability of yield response. For full details, see Chapter 14 by Douglas Beegle, _Interpretation of Soil Testing Results_, in [Recommended Soil Testing Procedures for the Northeastern United States](https://www.udel.edu/content/dam/udelImages/canr/pdfs/extension/factsheets/soiltest-recs/CHAP14.pdf).

The classification into probability of response, according to Beegle, involves three categories. In the _below optimum_ category, also called very low, low, or medium, "the nutrient is considered deficient and will probably limit crop yield. There is a high to moderate probability of an economic crop yield response to additions of the nutrient."

In the _optimum_ category, also called sufficient or adequate, "the nutrient is considered adequate and will probably not limit crop growth. There is a low probability of an economic crop yield response to additions of the nutrient."

The third category is _above optimum_, also called high, very high, or excessive. In this category, "the nutrient is considered more than adequate and will not limit crop yield. There is a very low probability of an economic crop yield response to additions of the nutrient."

In turfgrass management, one is not trying to maximize economic crop yield. Rather, one is trying to produce the desired surface performance, and does that by modifying the growth rate of the grass.

{{< figure src="kawana_15_16.jpg" caption="The 15th and 16th greens at the Kawana Hotel Fuji Course in Shizuoka, Japan.">}}

I wrote about this in [A Short Grammar of Greenkeeping](https://leanpub.com/short_grammar_of_greenkeeping).

When modifying the growth rate of the grass, one is often trying to _minimize_ the growth rate. Let's try anyway to apply these probabilities of response to turfgrass.

### Applying response probabilities to turfgrass

If we take the categories for probability of response, as defined by Beegle, we notice that he has referred to _crop yield_ and to an _economic crop yield response_. Let's drop that and substitute _turfgrass performance_ and _turfgrass performance response_. Now we have a definition that makes sense for turfgrass.

**Below optimum**: The nutrient is considered deficient and will probably limit turfgrass performance. There is a high to moderate probability of a turfgrass performance response to additions of the nutrient.

**Optimum**: The nutrient is considered adequate and will probably not limit turfgrass performance. There is a low probability of a turfgrass performance response to additions of the nutrient.

**Above optimum**: The nutrient is considered more than adequate and will not limit turfgrass performance. There is a very low probability of a turfgrass performance response to additions of the nutrient.

I think it is impossible to do soil test calibrations for every grass, climate, soil, and turfgrass use combination. So how can we figure out some way to interpret turfgrass soil tests and assign the results into one of those three categories? That's where MLSN comes in.

What we did with MLSN was look at thousands of soil test results from the optimum and above optimum categories. The turf was performing well at the time the sample was collected, so the soil was unlikely to be in the below optimum category.

Then we studied the distribution of the nutrient levels in those soils, threw away the bottom 10% to make sure we have some buffer against being too low, and identified the MLSN guideline as the level in the soil that we don't want to drop below. Nutrient recommendations are then made to ensure the soil doesn't drop below that minimum.

Because the soils used to identify the MLSN guidelines were already in the optimum or above optimum category, there is an implied probability in the MLSN recommendations. That is, keeping the soil from dropping below the MLSN guideline is the same as keeping the soil at a level with a low to very low probability of a turfgrass performance response to additions of the nutrient. 

Although such probabilities are implicit in the MLSN approach, we do not use those terms or classify soils into categories. With MLSN, we have just two categories---enough, and not enough. Turfgrass is a perennial crop, and soil nutrient levels go down as the turf harvests nutrients from the soil. The MLSN fertilizer recommendations consider how much of an element is in the soil now, how much of that element the grass will use over time, and then makes a recommendation to provide enough of that element to meet all the grass requirements.

### If you want probabilities, try the SI calculator

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.1/iframeResizer.min.js"></script>
<style>
  iframe {
    min-width: 100%;
  }
</style>
<iframe id="myIframe" src="https://asianturfgrass.shinyapps.io/turfsi/" scrolling="no" frameborder="no"></iframe>
<script>
  iFrameResize({
   heightCalculationMethod: 'lowestElement'
  });
</script>

