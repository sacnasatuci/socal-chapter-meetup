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
      title: SoCal SACNAS Chapters
      text: 🏝️ JOIN THE 2026 SOCAL MEET-UP  🌊
      primary_action:
        text: Interest Form
        url: https://forms.gle/GCMudeFpXzabWZAr6
        icon: rocket-launch
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
          filename: sacnas-socal-chapter-meetup-2025-v2.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "5+"
          description: |
            Counties
        - statistic: "20"
          description: |
            Southern California SACNAS Chapters
        - statistic: "150+"
          description: |
            SACNAS Members
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Build Community
          text: Build a supportive regional community of scientists who uplift and empower one another!
          feature_icon: user-group #check
          features:
            - Create a regional support network that extends beyond a single campus
            - Connect students from different universities who share similar cultural and academic experiences
            - Foster belonging for students from historically underrepresented backgrounds in STEM
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/build-community-ucsd-gemini.png
          #button:
          #  text: Get Started
          #  url: https://hugoblox.com/templates/
        - title: Share Experiences & Perspectives
          text: Learning from each other’s journeys in STEM and strengthening our collective voice
          feature_icon: book-open
          features:
            - Share personal academic journeys
            - Discuss navigating STEM as first-generation and/or underrepresented students
            - Learn how other chapters run events, outreach, and mentorship programs
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/share-experiences-and-perspectives-uci-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
        - title: Cross-Campus Collaboration
          text: Creating opportunities for collaboration across Southern California institutions
          feature_icon: academic-cap
          features:
            - Joint research discussions
            - Collaborative outreach programs
            - Multi-campus events and conferences
            - Shared resources between chapters
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/cross-campus-collaboration-csuf-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
        - title: Expand Professional Networks
          text: Growing a network of future scientists, researchers, and leaders
          feature_icon: user-plus
          features:
            - Build friendships and research connections
            - Meet future collaborators, lab mates, or graduate school peers
            - Strengthen connections within the broader SACNAS network
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/expand-professional-networks-cpp-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
        - title: Leadership Development
          text: Empowering the next generation of STEM leaders
          feature_icon: briefcase #check
          features:
            - Sharing successful event ideas
            - Discussing strategies for recruitment and retention
            - Learning how other chapters engage their communities
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/leadership-development-usc-gemini.png
          #button:
          #  text: Get Started
          #  url: https://hugoblox.com/templates/
        - title: Representation and Empowerment
          text: Celebrating the diversity that strengthens science
          feature_icon: trophy #map-pin #map #identification #hand-raised #globe-alt-solid
          features:
            - Reinforces representation in STEM fields
            - Creates a space where students feel seen and supported
            - Celebrates diverse cultures and identities in science
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/representation-and-empowerment-ucla-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
        - title: Inspire and Motivate
          text: Inspire one another to thrive in STEM
          feature_icon: heart
          features:
            - Motivation from peers who overcame similar challenges
            - Exposure to new career paths
            - Renewed enthusiasm for STEM and community engagement
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/inspire-and-motivate-sdcc-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
        - title: Regional Identity
          text: Strengthening the Southern California SACNAS community
          feature_icon: flag
          features:
            - Strengthen the SoCal SACNAS network
            - Encourage ongoing collaboration between nearby universities
            - Lay the groundwork for future regional events
          # Upload image to `assets/media/` and reference the filename here
          image: university-cartoons/regional-identity-csuci-gemini.png
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  #- block: logos
    # URL: https://github.com/HugoBlox/kit/blob/main/modules/blox/blox/logos/README.md
  - block: testimonials
    id: testimonials
    content:
      #title: ""
      #text: ""
      title: "Testimonials"
      #text: "Hear from SACNAS members that have attended a SoCal Chapter Meet-Up in the past!"
      items:
        - name: "Juan Gonzalez"
          role: "UC San Diego SACNAS Graduate Events Coordinator"
          image: "headshots/Juan-Gonzalez-UCSD.png"
          text: "The SoCal meet-up makes the community feel much larger. It reminds me that this STEM journey is being pursued by so many SACNAS members across different chapters, and I really enjoy getting to know each new person I encounter."
        #- name: "Helio Tejeda"
        #  role: "UCI SACNAS Chapter President 2024-2025"
        #  # Upload image to `assets/media/` and reference the filename here
        #  image: "headshots/Helio.jpg"
        #  text: "The SoCal Chapter Meet-Up allows us to build and strengthen our community."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: team-showcase
    id: chapters
    content:
      title: SoCal SACNAS Chapters
      subtitle: List of all Southern California SACNAS Chapters 🌊
      #text: Our diverse team brings together expertise from multiple disciplines.
      user_groups:
        - Provisional Chapters
        - Student Chapters
        - Professional Chapters
        #- name: Alumni          # optional per-group sort override
        #  sort_by: graduation_year
        #  sort_ascending: false
      sort_by: 'order' #'graduation_year' # legacy 'Params.' prefix optional
      sort_ascending: true
      # TODO
      #   Add a Google Form for SoCal chapters to add additional information and links!
      #cta:
      #  text: Update Chapter Info
      #  url: GoogleForm
      #  icon: plus
    design:
      show_role: true
      show_organizations: true
      show_interests: true
      max_interests: 3   # set 0 to hide interests even if provided
      align: center      # or "left" to align header + CTA left
      max_columns: 4     # 2, 3, or 4
      show_social: true
      show_empty_groups: false # show a placeholder when a group has no members
      # Section background color (CSS class)
      css_class: "bg-gray-50 dark:bg-gray-900"
#  - block: features
#    id: chapters
#    content:
#      title: SoCal SACNAS Chapters
#      text: List of all Southern California SACNAS Chapters 🌊
#      items:
#        - name: University of California, Santa Barbara
#          #icon: star
#          icon: UCI-Chapter-Logo-Circle.svg
#          description: "<b>Chapter Name</b>: SACNAS UCSB<br /><b>Chapter Type</b>: Student<br />Build with <i class='fas fa-heart fa-fw'></#i>by me with Hugo."
#        - name: Oxnard College
#          icon: star
#          description: "<b>Chapter Name</b>: OC SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: California State University Channel Islands
#          icon: star
#          description: "<b>Chapter Name</b>: SACNAS Chapter at Channel Islands<br /><b>Chapter Type</b>: Student"
#        - name: Los Angeles Valley College
#          icon: star
#          description: "<b>Chapter Name</b>: LAVC SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: Glendale Community College
#          icon: sparkles
#          description: "<b>Chapter Name</b>: SACNAS at GCC<br /><b>Chapter Type</b>: Student (Provisional)"
#        - name: University of California, Los Angeles
#          icon: star
#          description: "<b>Chapter Name</b>: UCLA SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: City of Hope
#          icon: star
#          description: "<b>Chapter Name</b>: SACNAS Chapter at City of Hope<br /><b>Chapter Type</b>: Student"
#        - name: California State Polytechnic University, Pomona
#          icon: star
#          description: "<b>Chapter Name</b>: CPP SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: University of Southern California
#          icon: star
#          description: "<b>Chapter Name</b>: USC SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: California State University Fullerton
#          icon: star
#          description: "<b>Chapter Name</b>: CSUF SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: California State University Long Beach
#          icon: star
#          description: "<b>Chapter Name</b>: CSULB SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#       - name: California State University San Bernardino
#         icon: star
#         description: "<b>Chapter Name</b>: SACNAS @ California State University, San Bernardino<br /><b>Chapter Type</b>: Student"
#       - name: University of California, Riverside
#         icon: star
#         description: "<b>Chapter Name</b>: UCR SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#       - name: Vanguard University
#         icon: star
#          description: "<b>Chapter Name</b>: SACNAS Chapter at Vanguard University of Southern California<br /><b>Chapter Type</b>: Student"
#        - name: University of California, Irvine
#          icon: star
#          description: "<b>Chapter Name</b>: UCI SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: College of the Desert
#          icon: star
#          description: "<b>Chapter Name</b>: SACNAS Chapter COD<br /><b>Chapter Type</b>: Student"
#        - name: University of California San Diego
#          icon: star
#          description: "<b>Chapter Name</b>: SACNAS Chapter at UC San Diego<br /><b>Chapter Type</b>: Student"
#        - name: University of San Diego
#          icon: sparkles
#          description: "<b>Chapter Name</b>: SACNAS Chapter at USD<br /><b>Chapter Type</b>: Student (Provisional)"
#        - name: San Diego City College
#          icon: star
#          description: "<b>Chapter Name</b>: San Diego City College SACNAS Chapter<br /><b>Chapter Type</b>: Student"
#        - name: Southwestern College
#          icon: brands/UCI-Chapter-Logo-Circle
#          description: "<b>Chapter Name</b>: SACNAS at SWC<br /><b>Chapter Type</b>: Student"
  - block: cta-card
    content:
      title: Join the SACNAS SoCal Chapter Meet-Up 2026
      text: "Fill out the interest form!<br />Deadline: March 28, 2026"
      button:
        text: Interest Form
        url: https://forms.gle/wCJ1FTRKnRdjr3Rv6
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
