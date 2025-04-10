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
    title: ''
    subtitle: ''
    styles:
      self:
        height: screen
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-0
          - pb-5
          - pl-4
          - pr-4
        flexDirection: col-reverse
        textAlign: center
    type: HeroSection
    actions: []
    text: ''
    media:
      type: ImageBlock
      url: /images/RUBELINAS_GOOGLE (2).png
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-16
          - pb-16
        borderWidth: 1
  - type: CtaSection
    title: Somos Super Anfitrión en Airbnb
    text: >+
      <div style="text-align:
      left">![](/images/logo%20rubelinas%20\(50%20x%2050%20px\)%20\(300%20x%20300%20px\)%20\(3\).png)Con
      **7 años consecutivos como Súper Anfitrión en Airbnb**, Casa Rubelinas ha
      demostrado un firme compromiso con la calidad y la satisfacción de sus
      huéspedes lo que ha permitido mantener esta distinción año tras año. A lo
      largo de los años, se ha perfeccionado el servicio para ofrecer una
      estancia cómoda y sin complicaciones, siempre cuidando cada detalle. Al
      reservar directamente desde este sitio, los huéspedes disfrutan de una
      experiencia sin intermediarios, con la posibilidad de obtener tarifas más
      convenientes. El equipo detrás de este espacio está siempre atento a las
      necesidades de los visitantes, buscando que cada estadía sea lo más
      agradable posible. Haz realidad tu viaje a Tequesquitengo, todo con la
      comodidad de un servicio directo y sin intermediarios.</div>

    actions:
      - type: Button
        label: Más reseñas
        altText: ''
        url: 'https://www.airbnb.mx/h/casarubelinasmx'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Super Anfitrión Airbnb
        altText: ''
        url: 'https://www.airbnb.mx/users/show/160496907'
        showIcon: true
        icon: ''
        iconPosition: right
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: airbnb
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-0
          - pb-5
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
        borderRadius: none
        borderWidth: 0
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-10
          - pb-10
        borderWidth: 1
  - type: ContactSection
    title: ''
    text: |
      ## Casa Rubelinas

      Haz tu escapada una realidad.
    form:
      type: FormBlock
      title: Title of the form
      fields: []
      submitLabel: Sign Up
      elementId: contact-form
      styles:
        self:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        flexDirection: row
        textAlign: left
---
