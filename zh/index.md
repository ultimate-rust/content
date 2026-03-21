---
# content/zh/index.md

layout: home
description: "用中文学 Rust，从零到高级，以其他任何地方都没有勇气提供的深度。"

hero:
  name: "Ultimate Rust"
  text: "完整的旅程"
  tagline: "把 Rust 学成第一门编程语言的完整指南。"
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: 开始学习 →
      link: /zh/before-we-start
    - theme: alt
      text: 了解项目
      link: /zh/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="种语言"
  :stats="[
    {
      value: '100%',
      label: '免费阅读',
      description: '所有内容无需注册、无需付费，随时可以访问。',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: '已注册的锈壳族',
      description: '他们决定用 Rust 本该被教授的方式来学习它。',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: '前置要求',
      description: '不需要任何经验，不需要任何基础，只要有开始的念头就够了。',
    },
    {
      value: '∞',
      label: '你能构建的项目',
      description: '语言不会成为你的上限。',
      highlightNumber: true,
    },
  ]"
/>