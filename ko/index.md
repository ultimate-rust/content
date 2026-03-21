---
# content/ko/index.md

layout: home
description: "Rust를 한국어로 배워보세요, 기초부터 고급까지, 아무도 감히 제공하지 못했던 깊이로."

hero:
  name: "Ultimate Rust"
  text: "완전한 여정"
  tagline: "Rust를 첫 번째 프로그래밍 언어로 배우기 위한 완전한 가이드."
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: 학습 시작하기 →
      link: /ko/before-we-start
    - theme: alt
      text: 프로젝트 알아보기
      link: /ko/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="언어"
  :stats="[
    {
      value: '100%',
      label: '무료로 읽기',
      description: '회원가입도, 페이월도 없이 모든 콘텐츠를 볼 수 있습니다. 언제나.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: '등록된 러스타시언',
      description: 'Rust가 처음부터 이렇게 가르쳐졌어야 했다고 생각한 사람들.',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: '사전 요구사항',
      description: '경험 없어도 됩니다. 기초 없어도 됩니다. 시작하고 싶다는 마음만 있으면 됩니다.',
    },
    {
      value: '∞',
      label: '만들 수 있는 프로젝트',
      description: '언어가 여러분의 한계가 되는 일은 없습니다.',
      highlightNumber: true,
    },
  ]"
/>