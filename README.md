<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0b0f14,100:4aa8ff&text=Tr%E1%BA%A7n%20B%E1%BA%A3o%20Trung&fontColor=e6edf5&fontSize=46&fontAlignY=36&desc=apollosuny%20%C2%B7%20Software%20Engineer%20%C2%B7%20Hanoi&descAlignY=58&descSize=16&animation=fadeIn" alt="Trần Bảo Trung" />
</p>

<p align="center">
  <a href="https://apollosuny-portfolio.pages.dev/">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=4AA8FF&center=true&vCenter=true&width=620&lines=Backend+systems%2C+built+to+scale.;From+the+first+diagram+to+the+pipeline+that+ships+it.;APIs+%C2%B7+Cloud+%C2%B7+Cross-chain+%C2%B7+AI;AWS+Certified+Solutions+Architect+%E2%80%94+Associate" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://apollosuny-portfolio.pages.dev/"><img src="https://img.shields.io/badge/Portfolio-0b0f14?style=for-the-badge&logo=cloudflarepages&logoColor=4aa8ff" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/apollosuny/"><img src="https://img.shields.io/badge/LinkedIn-0b0f14?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iIzRhYThmZiIgZD0iTTIwLjQ1IDIwLjQ1aC0zLjU2di01LjU3YzAtMS4zMy0uMDItMy4wNC0xLjg1LTMuMDQtMS44NSAwLTIuMTQgMS40NS0yLjE0IDIuOTR2NS42N0g5LjM0VjloMy40MXYxLjU2aC4wNWMuNDgtLjkgMS42NC0xLjg1IDMuMzctMS44NSAzLjYgMCA0LjI3IDIuMzcgNC4yNyA1LjQ2djYuMjh6TTUuMzQgNy40M2EyLjA2IDIuMDYgMCAxIDEgMC00LjEzIDIuMDYgMi4wNiAwIDAgMSAwIDQuMTN6TTcuMTIgMjAuNDVIMy41NlY5aDMuNTZ2MTEuNDV6TTIyLjIyIDBIMS43N0MuNzkgMCAwIC43NyAwIDEuNzN2MjAuNTRDMCAyMy4yMy43OSAyNCAxLjc3IDI0aDIwLjQ1Yy45OCAwIDEuNzgtLjc3IDEuNzgtMS43M1YxLjczQzI0IC43NyAyMy4yIDAgMjIuMjIgMHoiLz48L3N2Zz4%3D" alt="LinkedIn" /></a>
  <a href="mailto:baotrung06092003@gmail.com"><img src="https://img.shields.io/badge/Email-0b0f14?style=for-the-badge&logo=gmail&logoColor=4aa8ff" alt="Email" /></a>
  <a href="https://www.credly.com/badges/834f1f9b-7626-4fba-9967-ef62c720b21d"><img src="https://img.shields.io/badge/AWS_SAA--C03-0b0f14?style=for-the-badge&logo=credly&logoColor=ff9900" alt="AWS Certified Solutions Architect — Associate" /></a>
</p>

---

## `$ whoami`

```ts
const trung = {
  handle: "apollosuny",
  role: "Software Engineer @ CyberK",
  basedIn: "Hanoi, Vietnam 🇻🇳",
  experience: "2+ years — architecture, APIs, data, cloud & CI/CD",
  certified: ["AWS Certified Solutions Architect — Associate (SAA-C03)"],
  education: "B.Sc. MIS · VNU International School · GPA 3.52/4.0",
  caresAbout: ["clean boundaries", "stateless services", "code the next engineer can read"],
  askMeAbout: ["system design", "edge / serverless", "Web3 infra", "LLM-powered products"],
} as const;
```

> I work across the whole life of a system — from the first architecture diagram to the pipeline that ships it.

### 🛰️ `now.md` <sub>— updated 09.2026</sub>

- 🧠 Going deeper into **AI** — LLMs, RAG, agents and evals.
- 🤖 Building **ApolloGPT**, my own AI assistant, for fun.

---

## 🏗️ Selected work — *four systems, in production*

| # | Project | What it is | Key technical call | Stack |
|:-:|---|---|---|---|
| 01 | **[VisibleBrands](https://www.visiblebrands.ai)** | AI visibility (AEO) platform — audits how ChatGPT, Gemini & Perplexity see a brand and turns gaps into a prioritized fix list | Repeatable, aggregated prompt runs instead of one-off queries → scores stay comparable week to week | `Next.js` `TypeScript` `LLM APIs` `Crawlers` `Vercel` |
| 02 | **Ghola** <sub>private beta</sub> | AI companion that checks in daily, remembers what matters and celebrates your small wins | **One Durable Object per user** — no shared DB + cache, no races, no central DB on the hot path | `Hono` `Cloudflare Workers` `Durable Objects` `R2` |
| 03 | **[Oracler V2](https://oracler.co)** | Cross-chain swap & send in one unified flow | One adapter layer normalizing every third-party provider behind a single internal interface | `Next.js` `NestJS` `PostgreSQL` `Redis` `Docker` |
| 04 | **AI-MI** <sub>sunset 2025</sub> | Token launchpad on EVM — every token ships with its own OpenAI-powered agent | Infrastructure as code from day one — every GCP resource in Terraform | `React` `NestJS` `OpenAI` `GCP` `Terraform` |

<p align="right"><a href="https://apollosuny-portfolio.pages.dev/">Full case studies → portfolio ↗</a></p>

### 📦 Open source

<a href="https://github.com/Apollosuny/react-truncate"><img src="https://img.shields.io/npm/v/@apollosuny/react-truncate?style=flat-square&color=4aa8ff&label=%40apollosuny%2Freact-truncate" alt="npm version" /></a>
<a href="https://react-truncate-alpha.vercel.app"><img src="https://img.shields.io/badge/demo-live-0b0f14?style=flat-square" alt="Live demo" /></a>

**[`@apollosuny/react-truncate`](https://github.com/Apollosuny/react-truncate)** — pixel-accurate text truncation with an inline *“see more”*.
`canvas.measureText` + binary search · 0 deps · React 18/19

---

## 📜 `$ git log --career`

```diff
+ 2026        AWS Certified Solutions Architect — Associate (SAA-C03)
+ 10.2023 →   Software Engineer @ CyberK Company Limited
!             Architecture, APIs and cloud delivery for AI and Web3 products
+ 10.2022     Tech Department Lead @ ISTECH Club            (→ 07.2025)
!             Set technical direction for club web projects, mentored members through real builds
+ 09.2021     B.Sc. Management Information Systems @ VNU-IS  (→ 07.2025)
!             GPA 3.52 / 4.0 · Merit-based scholarship, 3 consecutive semesters
```

---

## 🧰 The toolbox

| Layer | Tools |
|---|---|
| **System design** | Layered architecture · Modular monolith · RESTful APIs · Stateless services · Caching · Async processing |
| **Application & API** | <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,nextjs,react,vite&theme=dark" alt="App & API" /> &nbsp;+ Hono |
| **Data & caching** | <img src="https://skillicons.dev/icons?i=postgres,mysql,redis&theme=dark" alt="Data" /> |
| **Cloud & platform** | <img src="https://skillicons.dev/icons?i=aws,gcp,cloudflare,workers,terraform,docker,githubactions&theme=dark" alt="Cloud" /> |

---

## 📊 Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Apollosuny&theme=github_dark" alt="GitHub profile summary" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Apollosuny&theme=github-dark-blue&hide_border=true&background=0b0f14&ring=4aa8ff&fire=4aa8ff&currStreakLabel=4aa8ff" alt="GitHub streak" />
</p>

---

<p align="center">
  <b>Got a system to build? <i>Let’s talk.</i></b><br/>
  <sub>Interesting project, a system question, or just want to talk architecture — my inbox is open → <a href="mailto:baotrung06092003@gmail.com">baotrung06092003@gmail.com</a></sub>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=apollosuny&label=profile%20views&color=4aa8ff&style=flat-square" alt="Profile views" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:4aa8ff,100:0b0f14" width="100%" alt="" />
