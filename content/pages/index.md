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
      Hello,I’m a Zaineb,an Electronics communications engineering student and a
      blockchain enthusiast.
    subtitle: >-
      I specialize in Embedded Systems as part of my engineering degree, but
      along the way, I've developed a strong expertise in blockchain technology.
      My passion lies in creating decentralized applications and advancing the
      potential of Web3.0. Currently, I’m working on a project focused on NFTs
      and cross-chain compatibility to connect various blockchain ecosystems.
    actions:
      - type: Button
        label: Resume
        altText: ''
        url: >-
          https://drive.google.com/file/d/1iStnJnkJuKkERHG5VIwQMOItBlRmMetW/view?usp=sharing
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/WhatsApp Image 2024-08-30 at 1.46.14 PM.jpeg
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
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-a
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
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
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Certificates
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
