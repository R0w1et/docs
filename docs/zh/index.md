---
layout: home

title: RetroAchievements

# TODO track what the most popular links are and update these accordingly
hero:
  name: RetroAchievements
  text: 文档
  tagline: 自2012年以来，在复古游戏中添加成就。
  actions:
    - theme: brand
      text: 支持的模拟器
      link: /zh/general/emulator-support-and-issues
    - theme: alt
      text: 行为规范
      link: /zh/guidelines/users/code-of-conduct
    - theme: alt
      text: 成为开发者
      link: /zh/developer-docs/how-to-become-an-achievement-developer
  image:
    src: /ra-logo-big-shadow.png
    alt: VitePress

features:
  - icon: 🙋🏽
    title: 注册
    details: 从注册账号开始。
    link: https://retroachievements.org/createaccount.php
  - icon: 🕹️
    title: 模拟器下载
    details: 安装可用模拟器，开始获得成就。
    link: https://retroachievements.org/download.php
  - icon: 📡
    title: API文档
    details: 将RetroAchievements集成到你的APP、网站，或者后端中。
    link: https://api-docs.retroachievements.org
  - icon: 🔧
    title: 模拟器集成文档
    details: 把RetroAchievements集成到你的模拟器中。
    link: https://github.com/RetroAchievements/rcheevos/wiki/rc_client-integration
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(
    140deg,
    hsl(44deg 85% 48%) 0%,
    hsl(40deg 51% 59%) 44%,
    hsl(43deg 21% 62%) 58%,
    hsl(187deg 10% 62%) 66%,
    hsl(202deg 40% 60%) 72%,
    hsl(200deg 68% 53%) 78%,
    hsl(204deg 68% 52%) 82%,
    hsl(208deg 68% 52%) 87%,
    hsl(212deg 68% 52%) 91%,
    hsl(218deg 68% 52%) 96%,
    hsl(223deg 67% 52%) 100%
  );

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #c39c30 50%, #3663d8 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
