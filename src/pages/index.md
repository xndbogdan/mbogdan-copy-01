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
        is_primary: true
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
        text: Over 2 years of experience.
        icon: fab  fa-laravel orange-fa
      - title: Vue.js
        text: Consistently used in Laravel projects.
        icon: fab fa-js orange-fa
      - title: Alpine.js
        text: ''
        icon: fab fa-js orange-fa
      - title: Inertia.js
        text: >-
          Used for [TrackerPro ](https://github.com/xndbogdan/TrackerPro)hiring
          challenge.
        icon: fab fa-js orange-fa
      - title: Bootstrap & Tailwindcss
        text: Big fan of Tailwind. Experienced with Bootstrap 3 and 4.
        icon: fa-css3
      - title: ASP.NET
        text: >-
          Worked on ExeSoftware's [esFields
          ](https://www.exesoftware.ro/ro/produse/esfields/)project.
        icon: fa-windows
    actions: []
    component: Features
  - type: contact
    title: Get in touch
    text: 'Don''t delay, apply for my services today!'
    section_id: three
    background_style: style1
    contact_list:
      - title: Address
        text: Strada Targu Neamt Nr. 14A Bloc B37
      - title: Email
        text: bogdanmmosteanu@gmail.com
        url: 'mailto:bogdanmmosteanu@gmail.com'
      - title: Phone
        text: '+40723400149'
        url: 'tel:+40723400149'
    social:
      title: Social Media
      social_icons:
        - title: Twitter
          icon: fa-twitter
          url: 'https://twitter.com/xnd_bogdan'
        - title: GitHub
          icon: fa-github
          url: 'https://github.com/xndbogdan'
        - title: Instagram
          icon: fa-instagram
          url: 'https://www.instagram.com/xnd_bogdan/'
        - title: LinkedIn
          icon: fa-linkedin
          url: 'https://www.linkedin.com/in/bogdan-mihai-476262120/'
    component: Contact
menus:
  main:
    title: Home
    weight: 1
template: home
---
