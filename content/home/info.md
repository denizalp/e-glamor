---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Join us!
subtitle: If you want to work with our group, contact us to join our weekly Tuesday group meetings at 4pm.

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: formspree
    formspree:
      id: test
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false
  
design:
  columns: '2'
---
