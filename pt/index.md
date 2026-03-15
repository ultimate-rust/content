---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
description: "Aprenda Rust em português, do zero ao avançado, com a profundidade que nenhum outro lugar teve coragem de oferecer."

hero:
  name: "Ultimate Rust"
  text: "A Jornada Completa"
  tagline: "Um guia completo para aprender Rust como sua primeira linguagem de programação."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: Começar a Aprender →
      link: /pt/before-we-start
    - theme: alt
      text: Saiba Mais
      link: /pt/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="idiomas"
  :stats="[
    {
      value: '100%',
      label: 'gratuito para ler',
      description: 'Todo o conteúdo acessível sem cadastro e sem paywall. Sempre.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'rustáceos registrados',
      description: 'Pessoas que decidiram aprender Rust do jeito que ele sempre mereceu ser ensinado.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'pré-requisitos',
      description: 'Nenhuma experiência. Nenhuma base. Só a vontade de começar.',
    },
    {
      value: '∞',
      label: 'projetos que você pode construir',
      description: 'A linguagem não vai ser o seu limite.',
      highlightNumber: true,
    },
  ]"
/>