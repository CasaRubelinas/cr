---
type: PageLayout
title: Home
colors: colors-d
backgroundImage:
  type: BackgroundImage
  url: /images/Diseño sin título.png
  backgroundSize: cover
  backgroundPosition: top
  backgroundRepeat: no-repeat
  opacity: 100
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: Casa Rubelinas
    subtitle: Tu casa de descanso en Tequesquitengo
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - type: MediaGallerySection
    title: ''
    subtitle: ¿Qué dicen nuestros huéspedes?
    images:
      - type: ImageBlock
        url: /images/1.png
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/logo rubelinas (50 x 50 px) (300 x 300 px) (1).png
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/2.png
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/3.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 4
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        textAlign: center
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: ''
    title: La casa
---
