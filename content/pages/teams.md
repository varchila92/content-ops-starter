---
title: Teams
slug: teams
sections:
  - title:
      text: UN EQUIPO QUE TRABAJA ESTRECHAMENTE UNIDO
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'Nuestro Equipo, Nuestra Fortaleza'
    text: >

      En nuestra empresa, creemos que el éxito se construye a través de la
      colaboración y el trabajo en equipo. Cada miembro aporta su experiencia y
      pasión, y juntos trabajamos estrechamente para alcanzar nuestros objetivos
      comunes. Con una comunicación abierta y un enfoque en la innovación,
      nuestro equipo es la base sólida sobre la que se construyen nuestras
      soluciones y nuestro éxito. ¡Conoce a las personas que hacen posible todo
      lo que logramos!
    actions: []
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: justify
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Conoce al equipo
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person2.json
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
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
seo:
  metaTitle: Equipo - vDevCodes
  metaDescription: Equipos
  socialImage: /images/vDevCodes.jpg
  type: Seo
type: PageLayout
---
