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
    provider: formspree
    formspree:
      id: xnqwkyad
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
  email: zhangsk@umich.edu
  phone: 'NA'
  address: 
    street: 440 Church St
    city: Ann Arbor
    region: MI
    postcode: '48109'
    country: US
    country_code: US
  coordinates:
    latitude: '42.272209'
    longitude: '-83.734558'
  directions: Samuel T. Dana Building
  office_hours:
    - 'Office Hours'
    - '[Register](https://calendar.app.google/9niTeJ3o3jKaYEWq8)'

design:
  columns: '2'
---
