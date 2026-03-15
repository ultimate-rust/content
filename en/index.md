---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
hero:
  name: "Ultimate Rust"
  text: "The Complete Journey"
  tagline: "A complete guide to learning Rust as your first programming language."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: Start Learning →
      link: /before-we-start
    - theme: alt
      text: Learn More
      link: /before-we-start/the-project

---

<HomeStats
  :max-per-row="3"
  locale-label="languages"
  :stats="[
    {
      value: '100%',
      label: 'free to read',
      description: 'All content accessible without registration and without a paywall. Always.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'registered Rustaceans',
      description: 'People who have already chosen to learn it the way it always deserved to be taught.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'prerequisites',
      description: 'No experience. No background. Just the will to start.',
    },
    {
      value: 'auto:days',
      label: 'days building',
      description: 'and it’s still nowhere near being complete.',
      highlightNumber: true,
    },
  ]"
/>