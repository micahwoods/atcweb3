---

title: '"I have always heard deep and infrequent was the way to go"' 
subtitle: ""
summary: ""
authors: [admin]
tags: []
categories: []
date: 2022-01-09T18:14:38+07:00
lastmod: 2022-01-09T18:14:38+07:00
featured: false
draft: false

image:
  caption: ""
  focal_point: ""
  preview_only: true

projects: []
---

This question about irrigation arrived and I think it's worth explaining more about irrigation amounts and frequency.

> I was listening to the end of your conversation with Chris Tritabaugh[^1] and you guys briefly discussed using light and frequent vs. deep and infrequent irrigation. I was surprised to hear you and Chris lean more to the side of light and frequent. I have always heard deep and infrequent was the way to go. I read your blog titled, [For irrigation, which is better? Deep and infrequent, or light and frequent?]({{< relref "/post/deep-and-infrequent-or-light-and-frequent-irrigation-which-is-better" >}}), and was wondering if you could expand on this?

[^1]: Watch our ATC Office Hours conversation at <https://youtu.be/J5_5mDJ-Vxc> or listen to the podcast version at <https://share.transistor.fm/s/b7418028>.

I used to be convinced that deep and infrequent irrigation was the way to go. But not anymore. Now I take a pragmatic approach to irrigation.

{{< figure src="featured.jpg" caption="I'd thought deep and infrequent was the ideal too, until Doug Soldat made an offhand comment to me that with light and frequent irrigation one can use less water." >}}

One of the documents I sent for further reading was my [Irrigation Management in Summer: timing, amount, syringing, and water quality](http://www.files.asianturfgrass.com/201306_summer_irrigation.pdf). In that document, I discussed irrigation frequency and summarized with this:

> A study of these experiments leads me to the conclusion that maintaining VWC at a lower level will give the best chance for improved turf quality and more extensive roots. As a practical matter, the best approach will usually be a combination of infrequent irrigation events interspersed with frequent irrigation events [(Johnson, 2003)](https://usgatero.lib.msu.edu/v02/n06.pdf). For turfgrass managers, I suggest focusing not so much on whether irrigation is applied frequently, or infrequently, but rather on applying just the right amount of water for a particular situation, and on keeping the VWC as low as possible.

I'll use some simulations to explain this some more. What I had not realized until Doug pointed it out to me was that one can apply *less* water, maintain the average soil water content at a lower level (more air space), *and* keep the soil from dropping as low in water content as one would when employing a deep and infrequent approach. That should result in better playability, obviously less water use, and rather importantly, may reduce the risk of developing localized dry spot.

This effect can be simulated, and I have a couple online calculators that allow one to do just that. [This one](https://asianturfgrass.shinyapps.io/irrigation/) has examples for four locations in Thailand and for Corvallis, Oregon. I also made one to calculate turfgrass irrigation requirement [in the Philippines](https://asianturfgrass.shinyapps.io/irr_ph/). With these calculators, you can make a number of adjustments to what I call the "irrigation rules." For multiple locations, and for multiple years of actual weather data for those locations, you can adjust:

* rootzone depth
* field capacity of the rootzone
* which soil volumetric water content (VWC) triggers an irrigation application
* what VWC the irrigation will raise the soil to
* the crop coefficient
* the irrigation system distribution uniformity

From those adjustments, the calculator then steps through the year with the real precipitation and the real evapotranspiration for that site, finding the total irrigation requirement and the average VWC for the year based on the rules you selected. 

I ran this for 2015 weather data at Khon Kaen, Corvallis, and Cebu. I used a 10 cm (4 inches) rootzone depth, a 25% field capacity, and 0.7 for both the crop coefficient and the distribution uniformity. Then I ran the calculator for two scenarios. Deep and infrequent was irrigation at 12% raising the soil back to field capacity. Light and frequent was irrigation at 14% raising the soil to 20%.

At Khon Kaen, the irrigation requirement went from 1,095 mm with deep and infrequent to 1,037 mm with light and frequent. The annual average VWC was 19.5% with deep and infrequent and 17.2% with light and frequent. Frequent irrigation required less water and kept the soil drier.

At Corvallis, this was 627 mm down to 606 mm, and average VWC of 22.1% down to 20.5%. Again, frequent irrigation required less water and kept the soil drier.

At Cebu, it was 976 down to 970, and 19.2% down to 17.2%. At this location also, frequent irrigation required less water and kept the soil drier.

And with all of these light and frequent approaches, the soil was kept from dropping below 14% VWC. With deep and infrequent, it was allowed to drop to 12%. 
