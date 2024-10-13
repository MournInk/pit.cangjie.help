---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: 仓颉语言
  text: "一款由华为开发的\n全场景编程语言"
  tagline: 通过阅读本文档，尽量避免踩坑
  actions:
    - theme: brand
      text: 📚 开始阅读
      link: /sdk
    - theme: sponsor
      text: ☕ 赞助我们
      link: /sponsor
    - theme: alt
      text: 📜 申请试用 SDK
      link: "https://wj.qq.com/s2/14870499/c76f/"
  image:
      src: /cangjie.svg
      alt: VitePress

features:
  - title: 原生智能化
    # icon: 🤖
    details: 内嵌 AgentDSL 的编程框架，自然语言与编程语言有机融合；多 Agent 协同，简化符号表达，模式自由组合，支持各类智能应用开发。
  - title: 天生全场景
    # icon: 🌐
    details: 轻量化可缩放运行时，模块化分层设计，内存再小也能装得下；全场景领域扩展，元编程和 eDSL 技术，支持面向领域声明式开发。
  - title: 高性能、强安全
    # icon: 🛡
    details: 终端场景首款全并发 GC ，应用线程更流畅，响应更快。轻量化线程，并发性能更好，开销更少。安全 DNA 融入语言设计，帮助开发者专注于业务逻辑，免于将太多精力投入到防御性编程中，编码即安全，漏洞无处藏。

---
<style>
  :root {
    --vp-home-hero-name-color: transparent;
    --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #0876f5, #04eb97);
  }  
</style>
