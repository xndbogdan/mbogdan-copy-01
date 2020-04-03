---
title: Home
sidebar:
  entries:
    - title: 'Welcome '
      url: '#intro'
      is_primary: true
    - title: About me
      url: '#one'
      is_primary: false
    - title: Skills
      url: '#two'
      is_primary: false
    - title: Get in touch
      url: '#three'
      is_primary: false
sections:
  - type: intro
    title: Not your average Bogdan
    subtitle: 'Passionate about computers, programming and electronic music'
    section_id: intro
    background_style: style1
    actions:
      - label: Learn more
        url: '#one'
        is_scrolly: true
        is_primary: false
    component: Intro
  - type: spotlights
    title: Spotlights Section
    section_id: one
    background_style: style2
    component: Spotlights
  - type: features
    title: Relevant skills
    subtitle: ''
    section_id: two
    background_style: style3
    features_list:
      - title: Laravel
        text: Over 2 years of experience
        icon: fab  fa-laravel orange-fa
      - title: Vue.JS
        text: ''
        icon: fab fa-js orange-fa
      - title: Alpine.JS
        text: ''
        icon: fab fa-js orange-fa
      - title: Inertia.JS
        text: ''
        icon: fab fa-js orange-fa
      - title: Bootstrap & Tailwindcss
        text: ''
        icon: fa-css3
      - title: ASP.NET
        text: ''
        icon: fa-windows
    actions:
      - label: Learn more
        url: /generic
        is_scrolly: false
        is_primary: false
    component: Features
  - type: contact
    title: Get in touch
    text: >-
      Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis
      mauris, eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget
      hendrerit bibendum, urna est aliquam sem, sit amet imperdiet est velit
      quis lorem.
    section_id: three
    background_style: style1
    contact_list:
      - title: Address
        text: |-
          12345 Somewhere Road #654
          Nashville, TN 00000-0000
          USA
      - title: Email
        text: user@Hyperspace.tld
        url: '#'
      - title: Phone
        text: (000) 000-0000
    social:
      title: Social
      social_icons:
        - title: Twitter
          icon: fa-twitter
          url: '#'
        - title: Facebook
          icon: fa-facebook
          url: '#'
        - title: GitHub
          icon: fa-github
          url: '#'
        - title: Instagram
          icon: fa-instagram
          url: '#'
        - title: LinkedIn
          icon: fa-linkedin
          url: '#'
    component: Contact
menus:
  main:
    title: Home
    weight: 1
template: home
---
