---
layout: blocks
title: Sant Jordi Jam
page_sections:

  - template: navigation-header-w-button
    block: header-2
    logo: "/img/logo-horizontal.webp"
    cta:
      buttons:
        - url: "/es"
          button_text: "castellano"
          button_class: "secondary"
        - url: https://itch.io/jam/sant-jordi-jam-2025
          button_text: "<i class='fab fa-itch-io' style='font-size: 1.2rem'></i> participa-hi!"
          button_class: "primary"

  - template: hero-banner-w-image
    block: hero-2
    slug: sant-jordi-jam
    headline: "<div style='font-family: var(--font-monospace);'>Sant Jordi <br><strong>jam</strong> 2025 </div>"
    content: |
      <b style="color: var(--col-site-subtitle-dark)">
      La <i>game jam</i> de la Diada de Sant Jordi.<br>
      <i style="color: var(--col-site-subtitle-light)">Descobreix més sobre nosaltres a les nostres xarxes!</i>
      </b>
    cta:
      enabled: true
      buttons:
        - url: https://twitter.com/SantJordiJam
          button_text: "<i class='fab fa-fw fa-twitter' style='font-size: 1.1rem; padding-right: 16px'></i> segueix-nos!"
        - url: https://itch.io/jam/sant-jordi-jam-2025
          button_text: "<i class='fab fa-itch-io' style='font-size: 1.1rem; padding-right: 6px'></i> apunta-t'hi!"
    image:
      image: "/img/sant-jordi-jam-vertical.webp"
      alt_text: Product Shot
    background_image: "/img/hero-2-bg.png"

  - template: detail-content
    slug: submission
    block: text-1
    md_file_left: pages/submission-info-left.md
    md_file_right: pages/submission-info-right.md

  - template: detail-content
    slug: llegenda
    block: text-2
    md_file_left: pages/legend-title.md
    md_file_right: pages/legend-content.md

  - template: 1-column-text
    block: one-column-1
    slug: team
    md_file: pages/about-team.md

  - template: simple-footer
    block: footer-1
    content: Fet amb ❤︎ i amb senyet per l'equip de la Sant Jordi Jam.
---
