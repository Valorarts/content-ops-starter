---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: 'I''m Valor, a ROBLOX designer!'
      color: text-dark
    subtitle: I specialize in ROBLOX Logo and UI design.
    text: |
      Would you like to order?
      Click "Learn more"
    actions:
      - type: Button
        label: Learn more
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: 'Hey There! '
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - subtitle: 'Reviews:'
    images:
      - altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - altText: Vise logo
        type: ImageBlock
      - altText: Contentful logo
        type: ImageBlock
      - altText: tEEEEEEEAA
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
