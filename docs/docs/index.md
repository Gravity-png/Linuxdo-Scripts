---
layout: home

hero:
  name: LinuxDo Scripts
  tagline: 持续更新，提供更强大的论坛体验，欢迎贡献您的创意！
  image:
    src: https://github.com/ezyshu/linuxdo-scripts/blob/main/public/icon/128.png?raw=true
    alt: 文档封面
  actions:
    - theme: brand
      text: 使用指南
      link: /guide/0-home/home.html
    - theme: alt
      text: GitHub
      link: https://github.com/ezyshu/linuxdo-scripts
    - theme: alt
      text: Chrome Web Store
      link: https://chromewebstore.google.com/detail/fbgblmjbeebanackldpbmpacppflgmlj
    - theme: alt
      text: Firefox Addons
      link: https://addons.mozilla.org/zh-CN/firefox/addon/linux_do-scripts/

features:
  - icon: 📖
    title: 完整文档
    details: 详细说明每个功能的使用方法与配置技巧
  - icon: ⚡
    title: 功能增强
    details: 在论坛基础功能上新增多项实用特性
  - icon: 🔧
    title: 持续更新
    details: 定期添加新功能并优化现有体验
---

<style>
.VPHero .text {
  font-size: 18px;
}

.VPImage {
  border-radius: 50%;
}

:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);
  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  --vp-home-hero-image-filter: blur(40px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(72px);
  }
  .clip {
    font-size:45px !important;
  }
  .tagline {
    font-size:20px !important;
  }
}
</style>