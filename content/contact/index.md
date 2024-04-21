---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        If you're interested in iZhu Lab, we'd love to hear from you!
      email: lfzhulf@outlook.com
      phone: 888 888 88 88
      address:
        street: Southeast University, No.2 Sìpáilóu, Xuánwǔ district
        city: Nanjing
        region: Jiangsu Province
        postcode: '210096'
        country: People’s Republic of China
        country_code: CN
      coordinates:
        latitude: '32.0542'
        longitude: '118.7948'
      directions: Enter Zhongxin Building, and take the stairs to Office 117 on Floor 1
      office_hours:
        - 'Monday 09:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
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
          filename: contact.jpg
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
