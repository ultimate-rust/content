---
# content/en/index.md

layout: home
description: "Learn Rust from scratch to advanced - with the depth no one else had the courage to offer."

hero:
  name: "Ultimate Rust"
  text: "The Complete Journey"
  tagline: "A complete guide to learning Rust as your first programming language."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: Get Started →
      link: /en/before-we-start
    - theme: alt
      text: About the Project
      link: /en/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="languages"
  :stats="[
    {
      value: '100%',
      label: 'free to read',
      description: 'All content available with no sign-up and no paywall. Always.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'registered Rustaceans',
      description: 'People who decided to learn Rust the way it always deserved to be taught.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'prerequisites',
      description: 'No experience. No background. Just the will to start.',
    },
    {
      value: '∞',
      label: 'projects you can build',
      description: 'The language will not be your limit.',
      highlightNumber: true,
    },
  ]"
/>