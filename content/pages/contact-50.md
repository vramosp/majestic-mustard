---
title: Contact us
sections:
  - type: ContactSection
    title: Contact us
    text: Fill out the form below and we will get in touch within 1 business day.
    variant: variant-a
    topGap: none
    bottomGap: none
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      idAttr: contact-form
      submitLabel: Send
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: 1/2
        - type: TextFormControl
          label: Last name
          placeholder: Your last name
          width: 1/2
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - type: CheckboxFormControl
          label: Sign me up to receive updates
          width: full
layout: PageLayout
---
