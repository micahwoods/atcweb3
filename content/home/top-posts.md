---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured

active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Top posts
subtitle: ""

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: post
  # Choose how many pages you would like to display (0 = all pages)
  count: 12
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  
design:

  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 1
  
  background:
    image: headers/keya_tools.jpg
    image_darken: 0.4
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---
