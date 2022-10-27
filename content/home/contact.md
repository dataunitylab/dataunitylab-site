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
  email: mmior@mail.rit.edu
  phone: 585 475 5810
  address:
    street: 102 Lomb Memorial Drive
    city: Rochester
    region: NY
    postcode: '14623-5608'
    country: United States
    country_code: US
  coordinates:
    latitude: '43.08419533149927'
    longitude: '-77.68006755422138'
  directions: Enter Golisano Hall and take the stairs to office 3517 on the third floor
  appointment_url: 'https://michael.mior.ca/contact/'

design:
  columns: '2'
---
