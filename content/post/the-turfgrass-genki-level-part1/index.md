---
date: "2019-02-03T00:00:00Z"
share-media: https://www.asianturfgrass.comstandard_n.png
tags:
- growth potential
- nitrogen
- fertilizer
- genki level
title: 'The turfgrass genki level, part 1: from temperature to standard N'
---

This is one I've been thinking about for a long time, and have discussed with many turf managers, but I don't think I've explained it on the blog yet. So here goes. This is what I call the turfgrass **genki level**.

### Background, or why I think this is useful

Sometimes I get questions like this:

> "For someone that would like to begin utilizing Growth Potential with more consistency, what are you general guidelines for Nitrogen applications for Ultradwarf greens? What would those same recommendations be for Bermudagrass grown on Tees/Fairways? 

> I've seen a reference of .8 lbs N per month when max GP. Is that a good number on greens or is that too high? I know that I can always raise or lower based on what I’m seeing or what golfers are expecting with speeds, but just curious about a starting point."

To answer that question, I want to give some idea about not only the *standard* amount for max GP, but also I want to express what turf managers are doing at any given time. The ratio of what is applied, compared to the *standard* amount, is what I call the **genki level**.

And I often want to discuss the intensity of pushing the grass to grow at a given time, or the intensity of pulling on the reins by restricting N, and to do that, I find it useful to communicate in terms of the genki level.

Here's an excerpt from an email I sent last year, explaining this:

> "About the 'predicted' [or standard] amount, that is somewhat arbitrary. That's what I think is about normal for the way bentgrass is typically managed today. The predicted amount can flip between N supply as fertilizer, and N use by the grass. Basically I tend to think of the predicted amount as what I expect for use, and if the soil will supply that amount, then the amount as fertilizer can be negligible. That's something to do, probably, with why your fairways in August didn't require N.

> Also related to the predicted amount is the relationship or ratio between the N supply and the predicted amount. This seems intuitive to me, but I have a feeling that for most golf course superintendents it would be confusing as hell---at least at first.

> The idea is that there is a predicted amount that is pretty normal. The amount you supply, in relation to the predicted amount, is something that I don't think there is a word for. I want to call it 'genki level'---genki being a Japanese word meaning good or healthy or how are you---or GL which could also be growth level for those who prefer a more straightforward description."

### Getting started, considering 3 locations

I used the [Dark Sky](https://darksky.net/poweredby/) API to get daily temperature data from each day in 2018 from three locations. That is, I took the latitude and longitude of Hazeltine National GC in Chaska, Minnesota (creeping bentgrass); Keya GC in Itoshima, Japan (manilagrass); and Van Tri GC in Hanoi, Vietnam (seashore paspalum); I then obtained the observed weather conditions from those locations.

![temperature 3 locs 2018](genki_level_temps.png)

Those are the daily high and low temperature data. From those I calculated the daily average temperature, and from that one can calculate the temperature-based turfgrass growth potential (GP) of PACE Turf.

Temperatures are useful. So is the GP, to quickly express on a scale of 0 to 1 the relative distance between the actual temperature and the optimum temperature for shoot growth.

![genki level gp](genki_level_gp.png)

The GP makes it easy to compare locations. And it is also straightforward to make an estimate of growth and N use. By multiplying a maximum amount of N by the GP, one gets an expected N use. Based on the way creeping bentgrass, manilagrass, and seashore paspalum are managed as fine turfgrass today, I like to use a standard maximum of 3 g N m<sup>-2</sup> month<sup>-1</sup>.

![standard N](standard_n.png)

I think it is useful to use the same *standard* N for the calculations, and then to express differences in the way turf is managed as the **genki level**. That makes it easy to compare the relative amount of pushing the grass, or pulling on the grass, between different seasons at the same location, or between different locations.

I've shown here how the temperature can be expressed as a GP and how that GP can be expressed as a *standard* amount of N. Coming up in part 2 and part 3, I'll show the genki level and how much the grass actually did grow. And I'll relate this to the [turfgrass speedo](https://www.turfhacker.com/2018/12/turfgrass-speedo.html) explained by Jason Haines.

### More reading

If you just can't get enough of this stuff, or want more details and examples about these type of calculations, please have a look at:

* [Using temperature to predict turfgrass growth potential and to estimate turfgrass nitrogen use](http://www.files.asianturfgrass.com/201306_growth_potential.pdf)
* [Nutrient requirements of tropical turfgrass](http://www.files.asianturfgrass.com/20130311_woods_handout_nutrient_requirements_tropical_turfgrass.pdf)
* [What fertilizer should I use?](http://www.files.asianturfgrass.com/20130313_woods_handout_fertilizer_choice.pdf)
* [Turfgrass speedo](https://www.turfhacker.com/2018/12/turfgrass-speedo.html)
* [*A Short Grammar of Greenkeeping*](https://leanpub.com/short_grammar_of_greenkeeping) 




