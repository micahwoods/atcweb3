---
date: "2019-05-02T00:00:00Z"
share-media: https://live.staticflickr.com/5567/15144360552_41f44e77b7_b_d.jpg
tags:
- mowing
- environment
- sustainability
- data analysis
title: Of conventional mowers, electric mowers, and electricity generation
---

Yesterday I responded to two questions related to carbon emissions associated with electricity generation. This was part of a broader discussion started by [Jason Haines](https://twitter.com/PenderSuper) about small electric autonomous mowers.

[Mike Richardson](https://twitter.com/ArkansasTurf) asked, "If I have to use the local electric company to charge the batteries and their power source is coal or natural gas, does it change the C footprint?"

[Chuck Barber](https://twitter.com/chuck_stccc) asked "How is burning coal to power robots better?"

I suggested to Richardson that the answer is yes, and one can find the calculations and reasoning behind that in David MacKay's [Sustainable Engery---Without the Hot Air](http://withouthotair.com/), specifically in chapter 20 where he discusses that very question. And I told Barber that electricity, even generated from coal, is better because the efficiency of the mowers is better. I've worked through some calculations to check this for myself, and to better explain my answers.

I'm going to describe how I made these calculations, trying to express in the same units what the expected CO<sub>2</sub> emissions would be to mow 1 hectare (2.47 acres) of golf course fairways for a month. And I'll make the calculations for diesel fairway mowers, and then for small autonomous mowers with a range of different electricity generating sources. This takes a few steps to work through and get everything in the right units.

## CO<sub>2</sub> emissions from diesel fairway mowers

I've calculated that the average fairway mower will use 3 liters of diesel to mow 1 hectare. I base this on the median of five numbers. Those numbers come from a 2013 Toro Reelmaster 3550-D brochure with fuel efficiency given in acres mown per gallon; the Reelmaster 3550-D mows 3.5 acres per gallon, Competitor A mows 3.1, and Competitor B mows 2.9. Converted to L/ha, those range from 2.7 to 3.2 L/ha. The other two numbers come from Tidåker et al.'s article on [Energy use and greenhouse gas emissions from turf management of two Swedish golf courses](https://doi.org/10.1016/j.ufug.2016.11.009), where fairway mowing used 3 L/ha at one course and 3.2 L/ha at the other.

Burning one liter of diesel [produces 2.7 kg of CO<sub>2</sub>](https://www.epa.gov/energy/greenhouse-gases-equivalencies-calculator-calculations-and-references).

## Electricity use by a small autonomous mower

Pirchio et al. reported that a Husqvarna model 310 automower modified to mow at 12 mm [used 0.86 kWh/week](https://journals.ashs.org/horttech/view/journals/horttech/28/4/article-p509.xml) to mow an area of 300 m<sup>2</sup>. That includes the electricity used to power the boundary wire and the electricity used to charge the batteries. The model 310 manual I found with a Google search states that the mower uses 8 kWh/month at maximum use to maintain 1,000 m<sup>2</sup>. 

I'm going to use the Pirchio et al. number in these calculations. It comes to 12.3 kWh/month (for a 30 day month) for 1,000 m<sup>2</sup>. That's a bit more electricity use than reported by the manual, but the Pirchio et al. number is also from a study in which "autonomous mowing produced a superior turf quality compared with the reel mower" for "the entire duration of the trial." I'm going to need a fleet of these small mowers, because each will be set to mow 1,000 <sup>2</sup> or less (assuming this is the model I choose).

In total, the electricity use to mow 1 ha for 1 month would be 123 kWh/month. 

At this point, we don't yet have directly comparable numbers between diesel fairway mowers and small electric autonomous mowers, but we are close. 

## CO<sub>2</sub> emissions from electricity generation

This was what Richardson and Barber were getting at in their questions. If one is using electricity from coal-powered power plants, is it true to say "I'm reducing emissions" just by using electric equipment? After all, the electricity generation---at least if it was coal or natural gas---produced some amount of CO<sub>2</sub>. I've had this question myself too. MacKay's [Sustainable Energy---Without the Hot Air](http://withouthotair.com/) is an excellent reference about this.

I'm going to use a conversion factor based on where the electricity was generated. The carbon intensity of electricity production, also called a greenhouse gas conversion factor, or an [emission factor](https://www.epa.gov/energy/greenhouse-gases-equivalencies-calculator-calculations-and-references), or [greenhouse gas intensity of electricity generation](https://www.neb-one.gc.ca/nrg/sttstc/lctrct/rprt/2017cndrnwblpwr/ghgmssn-eng.html), all do the same thing. They express the mass of CO<sub>2</sub> produced per unit of electricity generated, typically in units of g CO<sub>2</sub> per kWh of electricty.

Now we are close to an answer. For diesel mowers, we already know the CO<sub>2</sub> produced by mowing. For the small autonomous mower, we know the kWh used by mowing. The question we need to answer now is how much CO<sub>2</sub> was produced in the generation of that electricity?

### Recent conversion factors in a few places

The CO<sub>2</sub> emission factor for electricity production varies widely depending on the location and the makeup of the electricity generation in that area. I'll make this calculation for a few regions to show the differences.

* The entire United States, in 2017, had an average emission factor of 458 g CO<sub>2</sub>/kWh and the primary energy source was natural gas. That's from the [U.S. Energy Information Administration](https://www.eia.gov/electricity/state/unitedstates/), as are the data for specific U.S. states below. 
* The state of Arkansas in 2017 had a primary energy source of coal and an average emission factor of 548 g CO<sub>2</sub>/kWh.
* The state of California had a primary energy source of natural gas with an average emission factor of 215 g CO<sub>2</sub>/kWh.
* The state of Oregon had a primary energy source of hydroelectric with an average emission factor of 127 g CO<sub>2</sub>/kWh.
* In Canada, now with data from the [National Energy Board](https://www.neb-one.gc.ca/nrg/sttstc/lctrct/rprt/2017cndrnwblpwr/ghgmssn-eng.html), the nationwide average is 140 g CO<sub>2</sub>/kWh. 
* British Columbia, with most generation coming from hydroelectric, has an emission factor of 12.9 g CO<sub>2</sub>/kWh.

For the places I've mentioned, the emission factor ranges from 12.9 to 548 g CO<sub>2</sub>/kWh. Now let's see how that works out when those kWh are used to mow fairways.

## Direct comparison of CO<sub>2</sub> from different approaches to fairway mowing

With a conventional mower, let's mow fairways 15 times a month. That's 3 L of diesel for each ha, and 2.7 kg of CO<sub>2</sub> for each L. This works out to 121.5 kg of CO<sub>2</sub> per ha per month.

With an autonomous mower, let's start with the average U.S. emission factor from 2017: 458 g CO<sub>2</sub>/kWh. Our autonomous mowers use 123 kWh/ha/month, and production of that much electricity produced 56.3 kg of CO<sub>2</sub>.

In Arkansas, with a slightly higher emissions factor of 548, the production of 123 kWh for the autonomous mowers would produce 67.4 kg of CO<sub>2</sub>.

In British Columbia, the low emissions factor of 12.9 means the production of 123 kWh to power the small autonomous mowers would produce only 1.6 kg of CO<sub>2</sub>.

**Conventional mowing of 1 ha at 15 times a month: 121.5 kg of CO<sub>2</sub>.**

**Continuous mowing of 1 ha for 1 month by small autonomous mowers: from 1.6 to 67.4 kg CO<sub>2</sub>.**

Based on these calculations, the CO<sub>2</sub> reduction ranges from a factor of 2 to a factor of 75 with small autonomous mowers, depending on the source of electricity. And the reason for this, as I stated above, is the better efficiency of electric mowers compared to diesel mowers.

Let's say one only mows fairways twice a week. Let's mow fairways with a conventional mower 8 times in a month. Now the CO<sub>2</sub> emissions are 64.8 kg CO<sub>2</sub> per ha per month. Now the CO<sub>2</sub> emissions from fairway mowing are comparable to the highest CO<sub>2</sub> emissions from a primarily coal-powered grid. But that's also with the fairways still getting mown daily with the electric mower.

## In conclusion

I would appreciate corrections to any of my calculations here. This is my first time to work through this in such detail, so please be kind if I have made any glaring errors. 

I haven't made calculations for any other electric machines, but after working through this, am now intrigued to know what the electricity use is of the many other machines available to turfgrass managers.

The [improved turf quality](https://www.asianturfgrass.com/2018-12-08-produced-higher-quality-turf-autonomous/) reported by Pirchio is intriguing also.












