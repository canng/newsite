---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-15
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Full Curriculum Vitae
        url: https://docs.google.com/document/d/1WfDsR307eWinxXHo8zVZfSaO4xPcsedD/edit?usp=sharing&ouid=110358112673854373714&rtpof=true&sd=true
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <p style="font-size: 18px; text-align: justify">        
        <p style="font-size: 18px; text-align: justify"> 
        Prior to join CZP, he was a postdoc researcher for a joint program between <a href="https://en.psu.ac.th/">Prince of Songkla University (Hatyai campus)</a> and <a href="https://www.gistda.or.th/home.php?lang=EN">Geo-Informatics and Space Technology Development Agency </a>(GISTDA, Public Orgainization), under the framework of <a href="https://www.futureearththailand.org/frontpage">Future Earth Thailand</a>. 
        
        <p style="font-size: 18px; text-align: justify"> 
        He completed doctoral degree in Environmental Technology in 2022 at <a href="https://www.jgsee.kmutt.ac.th/v3/">The Joint Graduate School of Energy and Environment </a>(JGSEE), <a href="https://www.kmutt.ac.th/en/">King Mongkut’s University of Technology Thonburi </a>(KMUTT, Thailand), under the supervision of <a href="https://www.jgsee.kmutt.ac.th/v3/personnel/assoc-prof-dr-amnat-chidthaisong/">Prof. Amnat Chidthaisong</a>. His research focuses were <u>Urbanization</u> and <u>Climate Change</u> Impacts on <u>Urban environment</u> and <u>Nature-based Solutions (NbS)</u> of <u>Urban Green Spaces (UGS)</u>. He received B.Eng. and M.Sc. in Land Management from <a href="https://en.ctu.edu.vn/">Can Tho University (CTU)</a>, Vietnam, in 2016 and 2019, respectively. In 2016, he joined <a href="https://lrd.ctu.edu.vn/en/">Land Resources Department (LRD)</a>, College of Environment and Natural Resources, CTU as a Research and Teaching Assistant (RA/TA), where he closely worked with <a href="https://lrd.ctu.edu.vn/en/gioi-thieu/staffs/12-staff/64-assoc-prof-nguyen-thi-hong-diep.html">Assoc. Prof. Nguyen Thi Hong Diep</a>. In 2018, he was a short-term visiting researcher at <a href="http://kgeo.org/kgeo/">KMUTT Geospatial Engineering and Innovation Center</a> (KGEO, Thailand), with <a href="https://kirim.kmutt.ac.th/converis/portal/detail/Person/54338034;jsessionid=zvmHwL9_0ucaw9cu72KglOHDF13_5BdtfLqxmzPG.kirim-web?lang=en_GB">Dr. Pariwate Varnakovida</a>. 

        <p style="font-size: 18px; text-align: justify"> 
        His mission is to be an <i>Environmental Geographer</i>, who adopts <i>Remote sensing</i> and <i>Geoinformatics</i> by both quantitative and qualitative approaches to address diverse environmental problems and work towards ensuring environmental and living qualities for involved stakeholders.😃
        </p>
    design:
      columns: '2'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
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
        css_class: "bg-primary-700"
        css_style: ""
---
