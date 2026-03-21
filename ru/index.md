---
# content/ru/index.md

layout: home
description: "Учи Rust по-русски, с нуля до продвинутого уровня, с той глубиной, на которую больше никто не решился."

hero:
  name: "Ultimate Rust"
  text: "Полный путь"
  tagline: "Полное руководство, чтобы выучить Rust как первый язык программирования."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: Начать учиться →
      link: /ru/before-we-start
    - theme: alt
      text: О проекте
      link: /ru/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="языков"
  :stats="[
    {
      value: '100%',
      label: 'бесплатно для чтения',
      description: 'Весь контент доступен без регистрации и без paywall. Всегда.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'зарегистрированных рустацеев',
      description: 'Люди, которые решили учить Rust так, как он всегда заслуживал быть преподан.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'предварительных требований',
      description: 'Ни опыта. Ни базы. Только желание начать.',
    },
    {
      value: '∞',
      label: 'проектов, которые ты можешь создать',
      description: 'Язык не станет твоим ограничением.',
      highlightNumber: true,
    },
  ]"
/>