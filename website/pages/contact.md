---
title: Contact Us
metaDescription: Contact us
showTitle: true
permalink: /contact/
eleventyNavigation:
  key: Contact
  parent: Secondary
  order: 0
  parentItem: About
dynamicContent:
  - type: form
    formName: Contact
    formSuccessMessage: Thank you for getting in touch. We will respond soon.
    fields:
      - inputLabel: Your number
        fieldType: inputNumber
      - fieldType: inputText
        inputLabel: Your name
        field: inputText
      - inputLabel: Your email
        fieldType: inputEmail
        field: inputEmail
      - inputLabel: Your message
        fieldType: textarea
        field: textarea
    bg: standard-bg
---
You can contact us via email at info@email.com.

Or you can use the form below: