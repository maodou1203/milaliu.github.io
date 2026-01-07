---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing:
    # Top, Right, Bottom, Left
    padding: ['0', '0', '0', '0']

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |-
        <div style="text-align: justify; text-justify: inter-word;">
          <style>
            /* Only affect links inside the bio block */
            .bio-link { color: #0d829dff !important; text-decoration: none; }
            .bio-link:hover { color: #e9d32eff !important; text-decoration: underline; }
          </style>
          <p> I am currently affiliated with <a class="bio-link" href="https://hypersec.research.st/">Hyperdimensional Multimedia Perception and Frontier Security Laboratory</a> at Macao Polytechnic University.</p>
          <p>I received dual Ph.D. degrees, one in Computer Applied Technology from <a class="bio-link" href="https://www.mpu.edu.mo/en/index.php">Macao Polytechnic University</a>, and the other in Informatics Engineering from <a class="bio-link" href="https://www.uc.pt/en/">University of Coimbra</a>, under the supervision of Assoc. Prof. <a class="bio-link" href="https://hypersec.research.st/pages/8477">Xiaochen Yuan</a> and Assoc. Prof. <a class="bio-link" href="https://www.cisuc.uc.pt/en/people/pedro-martins">Pedro Martins</a>.</p>
          <p>My research focuses on information security, particularly image tampering detection and self-recovery, AI model security, and digital watermarking. To date, I've published over 10 SCI-indexed journal papers, including IEEE TIFS, IEEE TII, and IEEE TCSVT, among others.</p>
          <p>🌟🌟🌟I am actively seeking <u>postdoctoral research</u> opportunities.</p>
        </div>
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/
      headings:
        about: 'Hi!👋 I’m Mila!'
        interests: 'Research Interests'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: compact # Options: compact (long names), balanced (default), display (short names)

      # Avatar customization
      avatar:
        size: small # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded


  - block: resume-experience
    content:
      username: me
      text: ''
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  #   content:
  #   design:
  #       columns: "2"
  # # - block: experience
  #   content:
  #     title: "Education"
  #     items:
  #       - title: "Ph.D. in Computer Applied Technology"
  #         company: "Macao Polytechnic University"
  #         date_start: "2019-09-01"
  #         date_end: "2023-06-30"
  #         description: |
  #           * Research focus: image security and digital watermarking
  #           * Supervisor: Assoc. Prof. Xiaochen Yuan

  #       - title: "Ph.D. in Informatics Engineering"
  #         company: "University of Coimbra"
  #         date_start: "2019-09-01"
  #         date_end: "2023-06-30"
  #         description: |
  #           * Joint Ph.D. program
  #           * Supervisor: Assoc. Prof. Pedro Martins


  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: markdown
    id: news
    content:
      title: 'News'
      text: |-
        <div class="news-item">
          <div class="news-date">2026.01</div>
          <div class="news-content"> 🎉 One paper is accepted by <em><strong>Expert Systems With Applications (ESWA)</em></strong>.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2025.11 </div>
          <div class="news-content"> 🎓 Successfully defended my Ph.D. dissertation and obtained dual Ph.D. degrees, with <strong>Distinction and Honors (<em>summa cum laude</em>)</strong> awarded by the University of Coimbra, Portugal.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2025.11</div>
          <div class="news-content"> 🎉 SSEM-HIR is accepted by <em><strong>IEEE Transactions on Information Forensics and Security (TIFS)</em></strong>.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2025.10</div>
          <div class="news-content">🎉 One Chinese invention patent is granted.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2025.07</div>
          <div class="news-content">🎉 GHCW is accepted by <em><strong>Applied Soft Computing (ASOC)</em></strong>.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2025.08</div>
          <div class="news-content">🎉 One Chinese invention patent is officially granted.</div>
        </div>
        <div class="news-item">
          <div class="news-date">2024.10</div>
          <div class="news-content">🎉 One paper is accepted by <em><strong>IEEE Transactions on Industrial Informatics (TII)</em></strong>.</div>
        </div>
    design:
      css_class: 'news-wide'
      spacing:
        # Top, Right, Bottom, Left
        padding: ['3rem', '0', '1rem', '0']
      background:
        color: 'AliceBlue'
        text_color_light: false
    # design:
    #   background:
    #     css_style: 'background-color: #001f3f; color: white;'

  - block: collection
    content:
      title: Featured Publications
      text: ''
      button:
        text: More Publications
        url: /publications/
      filters:
        folders:
          - featured-publication
        exclude_featured: false
    design:
      view: date-title-image
      columns: 
      spacing:
        padding: ['3rem', 0, 0, 0]



  - block: hero
    content:
      primary_action:
        text: "Read More Publications"
        url: "/publications/"
        icon: "sparkles"
      # secondary_action:
      #   text: "Learn More"
      #   url: "https://docs.hugoblox.com"
      # announcement:
      #   text: "🎉 New features available now!"
      #   link:
      #     text: "Read more"
      #     url: "https://example.com/news"
    design:
      no_padding: true
      css_class: hero-tight
      background:
        color: ""
        gradient_start: "#8ebdd7ff"
        gradient_end: "#7c3aed"
        text_color_light: true
  
  - block: resume-awards
    content:
      title: Scholarship & Awards
      username: me
    design:
      columns: "2"

  - block: markdown
    id: news
    content:
      title: 'Beyond research'
      text: |-
        <div class="news-item">
          <div class="news-content">📷 Polaroid addict, I like my memories instant..</div>
        </div>
        <div class="news-item">
          <div class="news-content">🐱 Owned by a cat who bites a lot, but is also extremely clingy.</div>
        </div>
        <div class="news-item">
          <div class="news-content">🪂 Survived a 233m bungee jump from the Macao Tower, would do it again (maybe)</div>
        </div>
        <div class="news-item">
          <div class="news-content">🧋 Unsweetened milk tea only.</div>
        </div>
        <div class="news-item">
          <div class="news-content"> 🌍 Another life experience unlocked: visited the world’s northernmost city. (still thawing).</div>
        </div>
        <div class="news-item">
          <div class="news-content"> ✈️ A life experience seeker, always happy to be on the road. Been to 🇳🇴🇫🇮🇵🇹🇯🇵🇸🇬🇫🇷🇪🇸🇮🇹🇬🇷🇨🇿🇭🇺</em></strong>.</div>
        </div>
    design:
      css_class: 'news-simple'
      spacing:
        # Top, Right, Bottom, Left
        padding: ['3rem', '0', '1rem', '0']
      background:
        color: 'white'
        text_color_light: false
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
