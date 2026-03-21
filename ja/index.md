---
# content/ja/index.md

layout: home
description: "Rustを日本語でゼロから上級まで学ぼう、他のどこも踏み込まなかった深さで。"

hero:
  name: "Ultimate Rust"
  text: "完全な学びの旅"
  tagline: "Rustを最初のプログラミング言語として学ぶための、完全なガイド。"
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: 学習をはじめる →
      link: /ja/before-we-start
    - theme: alt
      text: プロジェクトについて
      link: /ja/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="言語"
  :stats="[
    {
      value: '100%',
      label: '無料で読める',
      description: '登録もペイウォールも不要。すべてのコンテンツをいつでも無料で。',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: '登録済みラスタシアン',
      description: 'Rustを、ずっとそうあるべきだった形で学ぶことを決めた人たち。',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: '前提知識',
      description: '経験は要らない。下地も要らない。始めようという気持ちだけでいい。',
    },
    {
      value: '∞',
      label: '作れるプロジェクト',
      description: '言語が、あなたの限界になることはない。',
      highlightNumber: true,
    },
  ]"
/>