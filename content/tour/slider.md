---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to The Lucas Lab
      content: What we're curious about...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Viral "dark matter" ☕️
      content: 'Bacterial viruses (or, bacteriophage, phage) are the most abundant forms of life on the planet, yet so much of phage diversity has yet to be described. '
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: Phage 
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
