---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '350px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: The ATC Doublecut with Micah Woods
      content: 'The podcast that takes a second look, thus a "double cut," at material on the ATC website.'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: headers/singha_Ac.jpg
      link:
        icon: podcast
        icon_pack: fas
        text: 'Listen to The ATC Doublecut'
        url: 'https://atc-doublecut.transistor.fm'
    - title: Videos & livestreams
      content: 'A turfgrass library of videos, conversations, and seminar screencasts.'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: headers/youtube_thumbs.jpg
      link:
        icon: video-camera
        icon_pack: fas
        text: "ATC's YouTube channel"
        url: 'https://www.youtube.com/asianturfgrasscenter'
    - title: ATC newsletters
      content: "Newsletters from ATC. Get highlights and announcements, #MLSN updates, or the full text of every new blog post the same day it is published."
      align: center
      background:
        position: center
        media: headers/atc_newsletter_banner.jpg
      link: 
        icon: envelope
        icon_pack: fas
        text: 'Sign up to ATC newsletters'
        url: 'https://subscribepage.com/atc_newsletters'
    - title: ATC Office Hours
      content: 'Office Hours podcast with turf managers, scientists, and students, about grass around the world.'
      align: center
      background: 
        position: center
        media: headers/banyan.jpg
      link: 
        icon: podcast
        icon_pack: fas
        text: "Listen to ATC Office Hours"
        url: 'https://atc-office-hours.transistor.fm'
---
