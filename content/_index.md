---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Automate the annoying little things
      text: 🚀 Follw us and learn to solve data automation challenges with code 🚀
      primary_action:
        text: Start learning and subscribe
        url: https://youtube.decodinglove.tv
        icon: rocket-launch
      secondary_action:
        text: Read the blog
        url: blog/
      # announcement:
      #   text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
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
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: learningjourney
    content:
      title: Your learning journey
      text: Learn to automate 🧱 with re-usable bulding blocks from first principles
      items:
        - name: Get the basics right
          icon: magnifying-glass
          description: Understand control structures and version control and also data structures
        - name: Dependency handling
          icon: bolt
          description: Avoid running into any dependency issues without all the hassle
        - name: Easy and proven
          icon: sparkles
          description: From the basics of programming to data manipulation to full blown pipelines
        - name: CI/CD
          icon: code-bracket
          description: Understand the value of automation and testing
        - name: relational algebra
          icon: star
          description: Get the basics of the relational model right - and apply it with any kind of dataframe tool - even for GPU accelerated large-scale data
        - name: Modular steps to advanced topics
          icon: rectangle-group
          description: Build up more and more advanced knowhow step by step about data visualization, pipeline orchestration, governance of data, large-scale data handling, deplyoments - even sprinkle of AI and more
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Learn how to build automation
          text: from the basics up to reliable pipelines
          feature_icon: check
          features:
            - "No more Excel hickups"
            - "No more manual annoying steps"
            - "No prior programming knowledge required"
            - "Clear observability of your automations"
          # Upload image to `assets/media/` and reference the filename here
          image: logo.jpg
          #build-website.png
          button:
            text: Get Started and subscribe
            url: https://youtube.decodinglove.tv
        # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: logo.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Learn automation
      text: By coding.
      button:
        text: No more Excel hickups
        url: https://youtube.decodinglove.tv 
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
