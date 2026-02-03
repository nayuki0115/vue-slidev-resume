---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Annie's Resume
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Senior Frontend Engineer

Annie Wu

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/nayuki0115" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>


---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 關於我

- 台北科技大學 資訊與財金管理系 碩士班
- 8 年前端工程師經驗
- Frontend Team Lead
- 前端架構重整與團隊流程建立

::right::
<br />

## Frontend Tech Stack  前端技能
- Frontend Frameworks
<section>
  <p>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/vuejs/vuejs-ar21.svg" alt="vue" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/nuxtjs/nuxtjs-ar21.svg" alt="nuxt" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg" alt="react" />
    </span>
  </p>
</section>

- Languages
<section>
  <p>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/javascript/javascript-ar21.svg" alt="js" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-ar21.svg" alt="ts" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-ar21.svg" alt="html" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/w3_css/w3_css-ar21.svg" alt="css" />
    </span>
  </p>
</section>

<style>
  section {
    line-height: 1.75;

    .tags {
      display: inline-block;
      padding: 5.01px 8.35px;
      margin-bottom: 6.68px;
      line-height: 30px;
      margin: 0 0 0 0.5rem;
    }
  }
</style>


<!-- 
目前是一位 Senior Frontend Engineer，同時擔任前端 Team Lead，  
前端年資約 8 年，主要技術是 Vue 2 / Vue 3、Nuxt 2 / Nuxt 3、TypeScript，  
近一年也有實際投入 Monorepo、前端架構重整與團隊流程建立   
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# Career Foundation
## 藍星球資訊（2017–2024）

- Frontend Engineer → Senior → Team Lead
- 技術轉型經驗：
  - jQuery / Blade → Vue 2 / Nuxt / TypeScript
- 專案類型：
  - 政府系統 / 文化典藏
  - Open Data 平台
  - 後台管理系統 / Dashboard
- 累積能力：
  - 舊系統維運與重構
  - 與 PM / 後端長期協作
  - 任務拆解與新人指導

<!-- 
在加入統智科技之前，我在藍星球資訊工作七年，  
這段經歷對我來說是職涯非常重要的基礎。  

我是在這裡從前端工程師一路成長到 Senior，  
後期也開始承擔 Team Lead 的角色。  

技術上，我經歷過從 jQuery 與傳統後端模板，  
轉型到 Vue 2、Nuxt 與 TypeScript，  
也處理過不少舊系統在維運與重構上的問題。  

這個階段讓我學到的，不只是技術，  
而是如何在資源有限、需求變動頻繁的情況下，  
把系統穩定交付，並開始帶人、拆任務、與 PM 與後端密切合作。  

這些經驗，讓我後來在統智科技能更快進入架構與 Lead 的角色。  
 -->
---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---

# 前端架構／技術決策(PTC)

## 背景
> - 30年前系統重構  
> - 技術版本老舊：  
>   - `node 16 / 18` 
>   - `vue 2 (options)`
>   - i18n 結構混亂
>   - 許多文件混雜，無整理
>   - 開發無流程， repo 資料夾混亂

<br />

## 我的角色
> - 我是 前端組 Leader，負責：
>   - 技術選型與升級路線規劃
>   - 架構設計與 Code Review
>   - 帶領 3 位前端工程師

::right::
<br />

## 關鍵決策與做法
> - 推動技術升級與開發流程優化：
>   - Vue 2 → Vue 3 升級與組件重構  
>   - 導入 Node.js 開發環境  
>   - 建立 Monorepo 架構  
>   - 重構 i18n 模組，統一 JSON 架構與命名規則
> - 前端技術 Wiki

<br />
<img src="/frontend-wiki.jpg" class="h-63 shadow" />

<!-- 第一個我想分享的是 在統智科技負責的前端重構專案 
背景：   
30年前系統重構，新的要使用 vue， 
我到職時已經有2個 repo   
技術版本混雜， node.js 16、18 都有，  
vue的話使用的已經 eol 的 vue2，而且是 options 的寫法  
i18n 的寫法變數很混亂

我的角色：  
我是 前端組 Leader，帶領帶 3 位工程師  
負責：  
技術選型與升級路線規劃  
架構設計與 Code Review  

我那時候做了：  
規劃 Vue 2 → Vue 3 的升級策略，避免一次性重寫  
導入 Monorepo 架構，統一共用模組與開發流程  
重構 i18n JSON 結構，並且統一命名
前端技術 Wiki（下方圖片）
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 團隊影響力／流程改善(PTC)

## 背景
> - Commit 混亂  
> - Branch 規則不一致  
> - Code Style 各寫各的，維護成本高  


## 我做的事
> - 從 0 到 1 建立：
>   - Conventional Commits
>   - Branch 命名規範
> - Coding Style 建立與落實：
>   - ESLint / Prettier
>   - 專案規範檔案建置
>   - 制定團隊統一規則  
> - 規範寫成文件  
> - Code Review 中實際落實
> - Onboarding Guide

::right::
<img src="/knowledge.jpg" class="h-63 shadow" />
<img src="/onboarding_guide.png" class="h-63 shadow" />

<!-- 
第二個我想補充的是 團隊流程、規範建立  
背景：  
沒有開發規範與流程，我覺得這樣下去不行，  
長久下去不好

我做的是：  
由 0 到 1，建立前端規範  
- Git Commit 規範  
- Branch 命名慣例  
- Coding Style 建立與落實，包含 ESLint / Prettier，等等設定檔  
- 共通元件與資料夾結構設計  

也有建立知識留存的 wiki  

另外我還寫了新進人員文件，  
這個是針對未來入我組別的新進人員寫的  
因為公司系統多，也有多個行政平台  
希望他們盡量可以早入進入狀況，所以寫了這個文件
 -->


---
transition: fade-out
---

# 為何尋找下一個機會？
- 期待更能累積 Domain Know-How 與技術深度的環境
- 希望在更成熟的流程與團隊配置下發揮前端影響力
- 職涯發展考量，尋找長期可投入的成長路徑


<!-- 
至於為什麼考慮轉職，  
主要是覺得 目前職務內容與我期待持續累積的 Domain 與技術深度有些落差，  
加上團隊與流程成熟度有限，對長期成長比較受限。  

我希望下一個角色，  
能讓我 持續在前端架構、系統設計、以及跨角色合作上發揮影響力，  
而不只是把需求完成。  
 -->

---
layout: center
class: text-center
---

# Thank You !

[Web](https://nayuki0115.github.io/) · [GitHub](https://github.com/nayuki0115) · [Cake](https://www.cake.me/nayuki0115) · [Linkedin](https://tw.linkedin.com/in/nayuki0115)

