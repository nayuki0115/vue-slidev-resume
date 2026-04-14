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

# Frontend Team Lead / Sr. Frontend Engineer 

Annie Wu

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/nayuki0115" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!-- 
大家好，我是 Annie。  
今天會用大約 10 分鐘，分享我在前端架構、技術決策，以及團隊協作上的經驗。    
 -->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 關於我
- Frontend Technical Lead / Frontend Architect
- 8 年前端經驗，負責「系統與團隊」而非單一功能
- 擅長：
  - 舊系統升級與版本演進規劃
  - 前端架構整理與開發流程建立
  - 與利害關係人（PM、後端、其他角色）溝通與對齊


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
我目前的角色比較不像單純寫前端，而是負責讓前端系統與團隊可以長期穩定運作。  

這幾年我的工作重心，主要放在三件事：  
第一，穩定交付，逐步推進舊系統的版本升級；  
第二，讓多人協作時，前端的產出能夠變得一致、可預期，而不是各寫各的；  
第三，則是把技術選擇轉成利害關係人能理解的決策依據，而不只是工程師內部的討論。  

所以今天的分享，我會比較著重在我怎麼做技術判斷、怎麼帶團隊與對齊角色，  
而不是單一技術細節的介紹。  
-->

---
transition: fade-out
---
# Career Foundation
## 藍星球資訊（2017–2024）

- Frontend Engineer → Senior → Team Lead
- 技術轉型經驗：
  - `jQuery` / `Blade` → `Vue 2` / `Nuxt` / `TypeScript`
- 專案類型：
  - 政府系統、後台管理系統、Dashboard
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

# 前端架構／技術決策

## 背景
> - 30年前系統重構  
> - 系統技術版本混雜
>   - Node 16 / 18
>   - Vue 2（Options API）
> - i18n 結構混亂
> - Repo 與資料夾結構缺乏一致性

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
>   - Vue 2 → Vue 3 升級與組件重構，導入 Typescript 開發    
>   - 統一 Node 與專案結構
>   - 建立 Monorepo 架構  
>   - 重構 i18n 模組，統一 JSON 架構與命名規則
> - 建立前端技術 Wiki

<br />
<img src="/frontend-wiki.jpg" class="h-63 shadow" />

<!-- 第一個我想分享的是 在統智科技負責的前端重構專案 
背景：   
30年前系統重構，新的要使用 vue， 
整體系統算下來有 108 個子系統，  
我到職時已經有2個 子系統  
  
我那時候思考的第一件事不是急著升級技術，  
是先判斷：**這個系統現在最不能承受的到底是什麼風險**。  
  
當時我認為最大的問題，不是效能或功能不足，  
而是技術版本與結構混亂，導致維護成本不可預期。  

所以我選擇  
先統一 Node 與專案結構，再逐步導入 Vue 3，  
同時重構 i18n 的 JSON 結構，讓多語系維護變得可控  

以這樣的做法逐步改善整體前端的可維護性與一致性。  
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 團隊影響力／流程改善

## 背景
> - Commit 與 Branch 規則不一致
> - Code Style 各自為政，維護成本高

<br />

## 我做的事
> - 建立：
>   - Conventional Commits
>   - Branch 命名規範
> - Coding Style 建立與落實：
>   - ESLint / Prettier
>   - 專案規範檔案建置
>   - 制定團隊統一規則  
> - 撰寫專案規範文件  
> - Code Review 中實際落實
> - 建立 Onboarding Guide

::right::
<img src="/knowledge.jpg" class="h-63 shadow" />
<img src="/onboarding_guide.png" class="h-63 shadow" />

<!-- 
第二個我想補充的是 團隊流程、規範建立  

我推動這些流程與規範的目的，  
並不是為了單純讓程式碼看起來比較漂亮，  
而是因為在多人協作、多專案的情況下，  
溝通成本往往比寫 code 本身還要高。  

當規範不一致時，最先受影響的通常是團隊與專案的節奏，  
這也包含新進人員，    
專案節奏也會變得不穩定。  

所以我把這些規範當成一種『對齊工具』，  
讓不同資歷、不同角色的人，  
都能在同一個基準上協作，  
進而讓整體產能變得可預期。  
 -->


---
transition: fade-out
---

# 為何尋找下一個機會？
- 希望在產品生命週期較長的環境中，持續累積 Domain Know-How 與前端技術深度  
- 期待在相對成熟的流程與團隊配置下，發揮前端在系統穩定性與可維護性上的影響力  
- 希望更深入投入前端架構層面的設計與決策，長期優化系統的可維護性與可擴充性  


<!-- 
至於為什麼考慮轉職，  
主要是覺得 職務內容與我期待持續累積的 Domain 與技術深度有些落差，  
加上團隊與流程成熟度有限，對長期成長比較受限。  

我也意識到，如果希望在前端架構這個方向上走得更扎實，  
我需要在產品生命週期相對較長的環境中，  
持續觀察並參與系統隨時間演進的過程，  
並不只是完成短期需求。  

因此，我這次尋找的機會，  
是希望能在相對成熟的流程與團隊配置下，  
專注於前端系統穩定性與可維護性的提升，  
並在長期投入的產品中，承擔更多前端架構層面的設計與決策責任。  
 -->

---
layout: center
class: text-center
---

# Thank You !

[Web](https://nayuki0115.github.io/) · [GitHub](https://github.com/nayuki0115) · [Cake](https://www.cake.me/nayuki0115) · [Linkedin](https://tw.linkedin.com/in/nayuki0115)

