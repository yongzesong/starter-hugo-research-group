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
    - title: AI and Spatial Association Lab
      content: 'Everything is Spatially Associated with Everything Else.'
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: welcome.jpg
    - title: 💡 [International Workshop on Spatial Association (IWSA)](https://spatialassociation.org/iwsa/)
      content: We invite top researchers to give talks ...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Artificial Intelligence, Innovative Geospatial Methods, Sustainable Infrastructure, Spatial Big Data, Open-Source Software, and More ...
      content: 'Students receive professional academic training.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: contact.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
