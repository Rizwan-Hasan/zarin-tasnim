---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: email
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: zarintasnim0077@gmail.com
  phone: false
  address:
    street: 'Agrabad'
    city: 'Chattogram'
    region: false
    postcode: '4100'
    country: 'Bangladesh'
    country_code: 'BD'
  coordinates:
    latitude: '22.3237417'
    longitude: '91.8091193'
  directions: ''
  office_hours: ''
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
  appointment_url: ''
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Contact me on Linkedin
      link: 'https://www.linkedin.com/in/zarin-tasnim-maisha-4b408b232/'

design:
  columns: '2'
---
