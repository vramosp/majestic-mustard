---
title: Contact us
sections:
  - type: HeroSection
    title: Contact Us
    subtitle: Fill out the form below and we will get in touch within 1 business day.
    variant: variant-b
  - type: ContactSection
    text: Fill out the form below and we will get in touch within 1 business day.
    variant: variant-b
    feature:
      type: FormBlock
      idAttr: contact-form
      action: /.netlify/functions/submission_created
      fields:
        type: TextFormControl
        label: Home address
        placeHolder: Your home address
layout: PageLayout
---
