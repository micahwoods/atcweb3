+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "GP avatar"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
#  gradient_start = "DarkGreen"
#  gradient_end = "ForestGreen"
  
  # Background image.
   image = "gp_avatar.jpg"  # Name of image in `static/media/`.
   image_darken = 0.6   # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
   image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
   image_position = "center"  # Options include `left`, `center` (default), or `right`.
   image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

{{< cta cta_text="Open GP avatar app" cta_link="https://paceturf.shinyapps.io/GPAvatar/" cta_new_tab="true" >}}

This app developed with [PACE Turf](https://www.paceturf.org/) generates a downloadable avatar that shows two lines -- blue and red. Blue is the cool-season growth potential through the year, and red is the warm season growth potential. We put this together in a hackathon when I visited PACE Turf headquarters a few years ago.

You can choose built-in temperature data from *any* zip code in the USA, or can input your own temperature data for any location.


