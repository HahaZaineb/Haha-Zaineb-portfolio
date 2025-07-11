---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: HeroSection
    title: >-
      Hello There! I’m Zaineb, an Electronics communications engineer and a
      blockchain enthusiast.
    subtitle: >-
      I specialize in Embedded Systems as part of my engineering degree, but
      along the way, I've developed a strong expertise in blockchain technology.
      My passion lies in creating decentralized applications and advancing the
      potential of Web3.0. Currently, I am working on a decentralized
      crowdfunding platform on the Massa Blockchain, which you can check out in
      the projects section!
    actions:
      - type: Button
        label: Resume
        altText: ''
        url: >-
          https://drive.google.com/file/d/1XWsyjoai6rBUJOd8viLuih7HxokmDtSA/view?usp=sharing
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/1671637968415-removebg-preview.png
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    text: ''
  - type: FeaturedProjectsSection
    subtitle: ''
    actions: []
    projects:
      - content/pages/projects/project-1.md
      - content/pages/projects/project-2.md
      - content/pages/projects/3.md
    colors: colors-f
    variant: variant-a
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    title: 'Projects:'
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: ''
    showFeaturedImage: false
    actions: []
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
      - content/pages/blog/hashgraph-developer-course.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    title: Certificates
  - type: FeaturedPostsSection
    title: 'Extracurriculars:'
    actions: []
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/2.md
      - content/pages/blog/3.md
      - content/pages/blog/4.md
    colors: colors-f
    variant: variant-a
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: false
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
---
