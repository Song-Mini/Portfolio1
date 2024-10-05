---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 연락
      text: |-
      email: smg0824@jbnu.ac.kr
      phone: 010 9027 2961
      address:
        street: 교정길 36
        city: 김제시
        region: 전라북도
        postcode: '54388'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.7979'
        longitude: '126.8787'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: goodbye.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
