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
layout: image-right
image: https://cover.sli.dev
---
# 學歷

## 台北科技大學 

## 資訊與財金管理系 碩士班

### 2015 - 2017

<a target="_blank" href="https://hdl.handle.net/11296/x3s9yy">長期照護人才推薦系統之研究</a>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Frontend Tech Stack  前端技能
## Frontend Frameworks
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

## Languages
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

## Tools & Others
<section>
  <p>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-ar21.svg" alt="git" />
    </span>
    <span class="tags">
      <img src="https://www.vectorlogo.zone/logos/eslint/eslint-ar21.svg" alt="eslint" />
    </span>
  </p>
</section>



<style>
  section {
    line-height: 1.75;
    .highlight {
      font-size: 1.25rem;
      font-weight: 600;
    }
    .tags {
      display: inline-block;
      padding: 5.01px 8.35px;
      margin-bottom: 6.68px;
      line-height: 30px;
      margin: 0 0 0 0.5rem;
    }
  }
</style>

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 工作經歷 (1/3)

## 藍星球資訊

<br/>

### 前端工程師 `2017-2019`
- `jQuery`、`Blade`
- 負責與設計、後端協作，完成前端互動功能與資料呈現
- 參與文化典藏與政府開放資料平台的開發任務

<br/>

### 高級前端工程師 `2019-2022`
- `Vue2` / `Nuxt2` / `TypeScript`
- 完成多項專案開發任務，擔任 RD Leader 進行任務拆解與實作
- 參與公司後台模組化與前端架構優化
- 技術轉型：主導從 jQuery 過渡至 Vue 2 開發流程

::right::

<br/><br/><br/>

### 主任 `2022-2024`
- `Vue2` / `Vue3` / `Nuxt2`/ `Nuxt3`/ `TypeScript`
- 擔任研發部前端組組長，帶領 4 位前端工程師
- 分配專案與人力，作為 PM 與 RD 的溝通橋樑
- 建立新人訓練制度、推動內部讀書會與知識分享
- 優化公司後台模組架構與維運流程
- 確保各項專案依期穩定交付

---
transition: fade-out
---
# 工作經歷 (2/3)

<br/>

## 專案類型
- 典藏系統
- Open Data
- 電商網站
- 儀表版


---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# 工作經歷 (3/3)

## 統智科技

<br/>

### 資深前端工程師 `2024-2025`
- `Vue2` / `Vue3`
- 前端組 Leader，帶領 3 位工程師  
- 負責技術指導、架構設計、Code Review、問題排解
- 推動技術升級與開發流程優化：
  - Vue 2 → Vue 3 升級與組件重構  
  - 導入 Node.js 開發環境  
  - 建立 Monorepo 架構與 Onboarding Guide  
  - 重構 i18n 模組，統一 JSON 架構與命名規則
::right::
<br/><br/><br/><br/><br/>

- 建立前端規範（由 0 到 1）
  - Git Commit 規範（Conventional Commits）
  - Branch 命名慣例（feature/、hotfix/、release/ 等）
  - Coding Style 建立與落實 （ ESLint / Prettier + 專案規範檔案建置，並制定團隊統一規則 ）
  - 共通元件與資料夾結構設計
  - 撰寫與維護前端技術 Wiki

<br/>

---
transition: fade-out
---

# 為何會想離開？
- **職務內容與面試期待存在落差**，與原先職涯規劃不完全一致
- **團隊角色配置不足**，使專案推動效率受限
- **缺乏累積 Domain Know-How 的機會**，難以深化專業能力
- **流程與制度尚未成熟**，對長期成長有所限制
- **職涯發展考量**，希望擁有更完整的學習與成長路徑
- **通勤時間較長**，影響工作與生活的整體平衡
- **身體與健康因素**，希望能有更永續且可長期投入的工作模式

---
layout: center
class: text-center
---

# Thank You !

[Web](https://nayuki0115.github.io/) · [GitHub](https://github.com/nayuki0115) · [Cake](https://www.cake.me/nayuki0115) · [Linkedin](https://tw.linkedin.com/in/nayuki0115)

