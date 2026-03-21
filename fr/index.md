---
# content/fr/index.md

layout: home
description: "Apprenez Rust en français, de zéro jusqu'au niveau avancé, avec la profondeur qu'aucun autre n'a eu le courage d'offrir."

hero:
  name: "Ultimate Rust"
  text: "Le parcours complet"
  tagline: "Un guide complet pour apprendre Rust comme premier langage de programmation."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: Commencer à apprendre →
      link: /fr/before-we-start
    - theme: alt
      text: Découvrir le projet
      link: /fr/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="langues"
  :stats="[
    {
      value: '100%',
      label: 'gratuit à lire',
      description: 'Tout le contenu accessible sans inscription ni paywall. Toujours.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'Rustacés inscrits',
      description: 'Des gens qui ont décidé d\'apprendre Rust comme il a toujours mérité d\'être enseigné.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'prérequis',
      description: 'Aucune expérience. Aucune base. Juste l\'envie de commencer.',
    },
    {
      value: '∞',
      label: 'projets que tu peux construire',
      description: 'Le langage ne sera pas ta limite.',
      highlightNumber: true,
    },
  ]"
/>