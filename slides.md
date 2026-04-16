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

# Sr. Frontend Engineer / Frontend Team Lead 

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
Hi, I’m Annie.

IC：  
Today I’ll take around 5 to 10 minutes to share my experience in frontend development,
including system improvement, implementation, and how to make development more stable in team collaboration.

Lead：  
Today I’ll take around 5 to 10 minutes to share my experience in frontend architecture,
technical decision-making, and how to improve team productivity through engineering practices.
 -->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# About Me
- Sr. Frontend Engineer / Frontend Team Lead / Frontend Architect 
- 8+ years of experience
- Focus on:
  - Maintainable frontend systems and structure optimization
  - Development workflow and team consistency
  - Cross-functional collaboration with PMs and backend engineers


::right::
<br />

## Frontend Tech Stack
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
I’m a frontend engineer with around 8 years of experience.

IC：  
I mainly work in complex or evolving systems,
where I focus on building stable and maintainable frontend applications.

Besides implementation, I also pay attention to code structure and development workflow,
so that teams can collaborate more efficiently.

Lead：  
In my recent role, besides development,
I also contribute to technical decisions and architecture adjustments.

I work on improving system structure, development workflow,
and aligning with different stakeholders to ensure long-term maintainability.  
-->

---
transition: fade-out
---
# Career Foundation
## BluePlanet (2017–2024)

- Frontend Engineer → Senior → Team Lead
- Technical transformation:
  - `jQuery` / `Blade` → `Vue 2` / `Nuxt` / `TypeScript`
- Projects:
  - Government systems, admin systems, dashboards
- Experience:
  - System evolution and technical transformation
  - Long-term collaboration with PMs and backend engineers
  - Task breakdown and onboarding


<!-- 
Before joining my current company, I worked at BluePlanet for seven years.

During this time, I grew from a frontend engineer to a senior role,
and experienced a full transformation from traditional development to Vue and TypeScript.

Through this process, I gained experience in technical transformation,
team collaboration, and working closely with PMs and backend engineers.
 -->
---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---

# Architecture / Technical Decisions

## Background
> - Legacy system with mixed technologies
> - Multiple Node and Vue versions
> - i18n structure was inconsistent
> - Project structure lacked standardization


<br />

## My Role
> - Led or contributed to frontend architecture and technical decisions
>   - Technology selection and upgrade planning
>   - Architecture design and code review
> - Collaborated with a team of 3 engineers

::right::
<br />

## Key Actions
> - Vue 2 → Vue 3 migration with TypeScript
> - Unified Node and project structure
> - Introduced monorepo
> - Refactored i18n structure
> - Built frontend wiki

<br />
<img src="/frontend-wiki.jpg" class="h-63 shadow" />

<!-- 
IC:  
In this project, the biggest issue was not functionality,
but inconsistent system structure and technology versions.

So I focused on improving consistency and maintainability.

I was involved in frontend architecture adjustments,
and contributed to technical decisions in key areas.

For example, we unified the project structure,
migrated from Vue 2 to Vue 3,
and refactored the i18n structure.

These changes helped make the system more stable and easier to maintain.


Lead:  
At the beginning, I identified that the main risk was not missing features,
but the inconsistency in system structure and technology.

So I prioritized improving maintainability and consistency.

I contributed to architecture decisions,
including upgrade strategy and system structure alignment.

For example, we unified Node versions,
introduced Vue 3 step by step,
and redesigned the i18n structure.

This helped the system evolve in a more controlled and predictable way.
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-16
---
# Development Workflow & Collaboration Improvement

## Background
> - Inconsistent commit and branch practices
> - Code style differences increased maintenance cost

<br />

## What I Did
> - Introduced:
>   - Conventional Commits
>   - Branch naming conventions
> - Improved coding standards:
>   - ESLint / Prettier
> - Wrote documentation
> - Applied standards through code reviews
> - Built onboarding guide

::right::
<img src="/knowledge.jpg" class="h-63 shadow" />
<img src="/onboarding_guide.png" class="h-63 shadow" />

<!-- 
In team collaboration, I noticed that inconsistent practices
can increase communication cost and slow down development.

So I helped improve the development workflow.

For example, we introduced ESLint and Prettier,
and defined commit and branch conventions.

I also used code reviews to ensure these standards were applied in practice.

The goal was to make development more consistent and predictable.
 -->


---
transition: fade-out
---

# Why I'm Looking for a New Opportunity
- Looking to work in a long-term product environment
- Want to deepen domain knowledge and technical expertise
- Interested in contributing to system stability and maintainability
- Hope to be involved in long-term system evolution and architecture decisions


<!-- 
I’m looking for an opportunity in a product-driven environment
where I can continue building domain knowledge and technical depth.

I want to be involved in long-term system evolution,
not just short-term feature delivery.

At the same time, I want to stay hands-on,
while contributing to system stability and maintainability.
 -->

---
layout: center
class: text-center
---

# Thank You !

[Web](https://nayuki0115.github.io/) · [GitHub](https://github.com/nayuki0115) · [Cake](https://www.cake.me/nayuki0115) · [Linkedin](https://tw.linkedin.com/in/nayuki0115)

