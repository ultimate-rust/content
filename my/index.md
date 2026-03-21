---
# content/my/index.md

layout: home
description: "ဗမာဘာသာဖြင့် Rust ကို အစကနေ အဆင့်မြင့်အထိ သင်ယူပါ၊ တစ်နေရာမှ မပေးဝံ့သော နက်နဲမှုနှင့်အတူ။"

hero:
  name: "Ultimate Rust"
  text: "ပြည့်စုံသောခရီး"
  tagline: "Rust ကို သင်၏ ပထမဆုံး programming ဘာသာစကားအဖြစ် သင်ယူရန် ပြည့်စုံသော လမ်းညွှန်တစ်ခု။"
  image:
    src: "/images/ferris/animated.gif"
    alt: "Ultimate Ferris"
  actions:
    - theme: brand
      text: သင်ယူစတင်ရန် →
      link: /my/before-we-start
    - theme: alt
      text: ပရောဂျက်အကြောင်း
      link: /my/before-we-start/the-project
---

<HomeStats
  :max-per-row="3"
  locale-label="ဘာသာစကားများ"
  :stats="[
    {
      value: '100%',
      label: 'အခမဲ့ဖတ်ရှုနိုင်',
      description: 'အကောင့်ဖွင့်ရန်မလိုဘဲ၊ ငွေပေးရန်မလိုဘဲ အကြောင်းအရာအားလုံး ရရှိနိုင်သည်။ အမြဲတမ်း။',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: 'auto:members',
      animated: true,
      label: 'မှတ်ပုံတင်ထားသော ရပ်တေးရှင်များ',
      description: 'Rust ကို အမြဲသင်ကြားသင့်သည့်နည်းဖြင့် သင်ယူရန် ဆုံးဖြတ်ခဲ့သောသူများ။',
      highlightNumber: true,
      highlightBorder: true,
    },
    {
      value: '0',
      label: 'လိုအပ်ချက်များ',
      description: 'အတွေ့အကြုံမလိုပါ။ အခြေခံမလိုပါ။ စတင်လိုသောစိတ်ဓာတ်သာ လိုသည်။',
    },
    {
      value: '∞',
      label: 'တည်ဆောက်နိုင်သော ပရောဂျက်များ',
      description: 'ဘာသာစကားသည် သင်၏ အကန့်အသတ်မဖြစ်ပါ။',
      highlightNumber: true,
    },
  ]"
/>