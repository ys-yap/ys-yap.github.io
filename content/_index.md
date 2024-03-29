---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

      
  - block: markdown
    id: outreach
    content:
      title: Education & Outreach
      text: |2-
        
        Quality education is scarce. To be provided with the opportunities I have had, learning from the most passionate of people, has been a massive privilege. For that, I am forever indebted. In turn, I have embarked on this endeavour to reciprocate the goodwill of many before me and reach out to younger generations, and it has been a journey I truly cherish.

        [FrogAsia SPACE Series](https://www.frogasia.com/launchpad-space-series)
        ----------------------------------------------------
    
        ![FrogAsia SPACE Series](frog.png)
    
        In efforts to provide a local, Malaysian narrative on astronomy, several astrophysicists and I partnered with [Frogasia](https://www.frogasia.com/) to curate an open-access learning module as a first-exposure course to astronomy for kids between ages 10 to 15. The course focuses on demonstrating connections between the cosmos and human life across the past, present and future. We aim to bring vibrance to astronomy education, and hope to inspire curious minds with the highlights of talented Malaysian astronomers.
    
        [International Olympiad on Astronomy and Astrophysics](https://www.ioaastrophysics.org/)
        ----------------------------------------------------
        
        ![Malaysia at IOAA 2019](ioaa.jpeg)
        
        I have served on the Academic Council for the Malaysia Olympiad on Astronomy and Astrophysics (MOAA) since 2018. Specifically, I coordinate academic tasks involved in the national selection, which includes problem-setting, lecturing and training in problem-solving and practical observations. We share the objective in providing aspiring students a pedagogical walkthrough into the field of astronomy.
        
        From 2019 to 2023, I have been the coach and team leader for the Malaysia team at the IOAA in [Hungary](https://www.sinchew.com.my/?p=2876622), [Colombia (virtual)](https://www.sinchew.com.my/20211122/%e5%9b%bd%e9%99%85%e5%a4%a9%e6%96%87%e4%b8%8e%e5%a4%a9%e4%bd%93%e7%89%a9%e7%90%86%e5%a5%a5%e6%9e%97%e5%8c%b9%e5%85%8b%e7%ab%9e%e8%b5%9b/), [Georgia](https://www.sinchew.com.my/?p=4039928), and [Poland](https://www.chinapress.com.my/?p=3568959). Through collaboration with the [National Planetarium](https://www.planetariumnegara.gov.my/#/landing), [Langkawi National Observatory](http://observatory.mysa.gov.my/), and the Malaysian astronomy community, we have been able to provide high-calibre training in theoretical and practical aspects of astronomy. We aim to promote the learning of astronomy among students, and to expose them to the frontiers of astronomical research. For more information, check out the [MOAA website](https://moaa.starfinder.org.my/) or email us at [moaa@starfinder.org.my](mailto:moaa@starfinder.org.my)


        
    design:
      columns: '2'


  - block: experience
    id: commitments
    content:
      title: Commitments
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Board Member
          company: "[Association of the Malaysian Alumni of the International Science Olympiads, AMISO](https://amiso.my/)"
          company_url: ''
          company_logo: amiso
          location: 
          date_start: '2022-03-01'
          date_end: ''
          description: Coordinating STEM outreach initiatives, as well as administrative and academic initiatives between AMISO and local Olympiad selection committees.
          
        - title: Academic Counciller
          company: "[Malaysia Olympiad on Astronomy and Astrophysics, MOAA](https://moaa.starfinder.org.my/)"
          company_url: ''
          company_logo: moaa
          location: 
          date_start: '2018-01-01'
          date_end: ''
          description: Lecturing, setting test questions and selecting a Malaysian team for the International Olympiad.
    design:
      columns: '2'
      
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: yongsheng_yap@live.com
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
#      address:
#        street: 450 Serra Mall
#        city: Stanford
#        region: CA
#        postcode: '94305'
#        country: United States
#        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
