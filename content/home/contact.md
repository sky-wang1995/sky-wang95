---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: xiang.wang@bcm.edu
  phone: 858 249 8782
  address:
    street: 1 Moursund St
    city: Houston
    region: TX
    postcode: '77030'
    country: United States
    country_code: US
  directions: Enter Building Jewish Building and take the elevator to Office 643 on Floor 6
  appointment_url: ''
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: '[https://zoom.com](https://bcm.zoom.us/j/2598600554)'

design:
  columns: '2'
---
