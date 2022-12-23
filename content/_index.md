---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: header2
    content:
      title: |-
        <font align="left">
        
        ## WestLake Nlp Lab
        
        </font>
      subtitle: ''
      text:
        Lexical, syntactic and semantic representation and analysis in Chinese and English basic natural language processing.
        {{% cta cta_link="https://frcchang.github.io/" cta_text="View Our Github →" %}}
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["250px", "0", "250px", "0"]
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: ww.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: hero
    content:
      title: WestLake Nlp
      image:
        filename: hero-academic.png
      text: |-
        **Dr. Zhang's main research interests are natural language processing, text mining, machine learning and artificial intelligence, including natural language processing, text mining, machine learning and artificial intelligence.**

        Lexical, syntactic and semantic representation and analysis in Chinese and English basic natural language processing.
    design:
      background:
        gradient_end: '#003055'
        gradient_start: '#003055'
        text_color_light: true
#  - block: about.avatar
#    id: about
#    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
#      username: admin
      # Override your bio text from `authors/admin/_index.md`?
#      text:
  - block: collection
    id: posts
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
  - block: markdown
    id: people
    content:
      title: |-
        <font color="#ff7b00">People</font>
      subtitle: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      # Override your bio text from `authors/admin/_index.md`?
      text: |-
        ## Faculty
        <table width="100%" align="center">
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="200" style="border-radius:100%"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Zhang Yue</a></h4><font color="#9EA0A4">Tenured Full Professor</font></td>
            </tr>
        </table> 

        ## Post Doc
        <table width="100%" align="center">
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="100" height="200"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="100" height="200"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="100" height="200"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
            </tr>
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
            </tr>
        </table> 

        ## PHD Students
        <table width="100%" align="center">
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
            </tr>
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">PHD student</font></td>
            </tr>
        </table> 

        ## Research Assistants
        <table width="100%" align="center">
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
            </tr>
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ZheJiang University</font></td>
            </tr>
        </table>

        ## Alummi
        <table width="100%" align="center">
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">Tencent</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">360</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">SenseTime</font></td>
            </tr>
            <tr>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">CUHK</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">ByteDance</font></td>
                <td align="center" style="margin-bottom:40px"><img src="./authors/admin/avatar.jpg" width="200" height="300"/><h4><a href="https://frcchang.github.io/" style="text-decoration: none;">Student 1</a></h4><font color="#9EA0A4">MeiTuan</font></td>
            </tr>
        </table>
    design:
      columns: '1'  
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo">}}           
    design:
      columns: '1'  
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 1
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '20'
  - block: contact
    id: contact
    content:
      title: Join Us
      subtitle:
      text: |-
        Welcome to join us!
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
