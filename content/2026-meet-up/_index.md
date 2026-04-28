---
title: 'Home'
date: 2023-10-24
type: landing
#icon: UCI-Chapter-Logo-Circle.svg

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Hosted by: UC San Diego<br /><br /><br /><br /><br /><br />"
      #text: 🏝️ ALL SOCAL CHAPTERS ARE INVITED  🌊
      #primary_action:
      #  text: Interest Form
      #  url: https://forms.gle/GCMudeFpXzabWZAr6
      #  icon: rocket-launch
      #secondary_action:
      #  text: Zoom Planning When2Meet
      #  url: https://www.when2meet.com/?35530745-IHUjw
      #announcement:
      #  text: "Announcing the release of version 1."
      #  link:
      #    text: "Read more"
      #    url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: university-cartoons/build-community-ucsd-gemini.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  #- block: stats
  #  content:
  #    items:
  #      - statistic: "5+"
  #        description: |
  #          Counties
  #      - statistic: "20"
  #        description: |
  #          Southern California SACNAS Chapters
  #      - statistic: "150+"
  #        description: |
  #          SACNAS Members
  #  design:
  #    # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900"
  #    # Reduce spacing
  #    spacing:
  #      padding: ["1rem", 0, "1rem", 0]
  #- block: testimonials
  #  content:
  #    title: ""
  #    text: ""
  #    #title: "Testimonials"
  #    #text: "Hear from SACNAS members that have attended a SoCal Chapter Meet-Up in the past!"
  #    items:
  #      - name: "Helio Tejeda"
  #        role: "UCI SACNAS Chapter President 2024-2025"
  #        # Upload image to `assets/media/` and reference the filename here
  #        image: "headshots/Helio.jpg"
  #        #text: "The SoCal Chapter Meet-Up allows us to build and strengthen our community."
  #        text: ""
  #  design:
  #    spacing:
  #      # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #      padding: ["6rem", 0, 0, 0]

  - block: cta-card
    content:
      title: "SoCal SACNAS Chapter<br />Meet-Up 2026"
      text: |
        Event Date:
        <br />
        <b>Saturday May 23rd 2026 @ 9am</b>
        <br />
        <br />
        Join the next planning meeting by filling out the interest form!
        <br />
        Fill out by <b>May 1, 2026</b>
      button:
        text: Interest Form
        url: https://forms.gle/NBAcd429y9mgYDfWA
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
