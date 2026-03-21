---
# content/hi/index.md

layout: home
description: "Rust को हिंदी में सीखें, शून्य से उन्नत स्तर तक - जितनी गहराई देने की हिम्मत कहीं और नहीं हुई।"

hero:
  name: "Ultimate Rust"
  text: "पूरी यात्रा"
  tagline: "Rust को अपनी पहली प्रोग्रामिंग भाषा के रूप में सीखने के लिए एक संपूर्ण मार्गदर्शिका।"
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: सीखना शुरू करें →
      link: /hi/before-we-start
    - theme: alt
      text: प्रोजेक्ट के बारे में जानें
      link: /hi/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="भाषाएँ"
  :stats="[
    {
      value: '100%',
      label: 'पढ़ने के लिए मुफ़्त',
      description: 'सारा कॉन्टेंट बिना रजिस्ट्रेशन और बिना paywall के उपलब्ध। हमेशा।',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'पंजीकृत रस्टेशियन',
      description: 'वे लोग जिन्होंने Rust को उस तरह सीखने का फ़ैसला किया, जैसे हमेशा सिखाया जाना चाहिए था।',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'पूर्वशर्त',
      description: 'कोई अनुभव नहीं। कोई आधार नहीं। बस शुरू करने की चाहत काफ़ी है।',
    },
    {
      value: '∞',
      label: 'प्रोजेक्ट जो आप बना सकते हैं',
      description: 'भाषा आपकी सीमा नहीं बनेगी।',
      highlightNumber: true,
    },
  ]"
/>