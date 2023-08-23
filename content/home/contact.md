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
  email: yajing.zhou@kcl.ac.uk
  phone: +86 13807478148
  address:
    street: No.5 Kelian Road
    city: Shenzhen
    region: Guangdong
    postcode: '94305'
    country: China
    country_code: CHN
  coordinates:
    latitude: '22.72'
    longitude: '113.91'
  directions: Shenzhen Bay Laboratory 


design:
  columns: '2'
---
