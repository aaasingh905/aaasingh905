<div align="center">

<img src="./assets/banner.svg" width="100%" alt="Anurag Singh — Lead Frontend Engineer" />

<br /><br />

<a href="https://www.linkedin.com/in/anurag-singh-6661a5179/"><img src="https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/aaasingh905"><img src="https://img.shields.io/badge/GitHub-4338CA?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://trestech.in"><img src="https://img.shields.io/badge/TresTech-4338CA?style=for-the-badge&logo=vercel&logoColor=white" /></a>

</div>

<br />

---

<br />

## About

I'm a software engineer with **8+ years** of experience designing and building large-scale, customer-facing applications — primarily across **fintech, banking, and SaaS platforms**. My work sits at the intersection of frontend architecture and backend systems: I care about how products are structured underneath as much as how they feel to use.

I'm currently a **Lead Software Engineer at Publicis Sapient**, working across enterprise banking engagements for US Bank, NatWest Group, TIAA, and Bank of Ireland. Alongside that, I run **[TresTech](https://trestech.in)** — my own SaaS venture, where I build vertical SaaS products end-to-end in my free time.

<br />

## By the Numbers

<div align="center">

<img src="https://img.shields.io/badge/Experience-8%2B_Years-4338CA?style=for-the-badge" />
<img src="https://img.shields.io/badge/Micro--apps_Shipped-200%2B-F59E0B?style=for-the-badge" />
<img src="https://img.shields.io/badge/Banking_Clients-4-0D9488?style=for-the-badge" />
<br />
<img src="https://img.shields.io/badge/Engagement_Lift-30%25-F43F5E?style=for-the-badge" />
<img src="https://img.shields.io/badge/Component_Library-50%2B-4338CA?style=for-the-badge" />
<img src="https://img.shields.io/badge/Team_Led-8_Engineers-F59E0B?style=for-the-badge" />

</div>

<br />

## Technical Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,react,nodejs,express,mongodb,tailwind,redux,vite,docker,aws,git,figma&theme=dark" />

</div>

<table>
<tr><td><b>Languages</b></td><td>TypeScript · JavaScript · Node.js</td></tr>
<tr><td><b>Frontend</b></td><td>React · React Router · TanStack Query · Zustand · Tailwind CSS · shadcn/ui</td></tr>
<tr><td><b>Backend & Data</b></td><td>Express · MongoDB · Mongoose · REST APIs</td></tr>
<tr><td><b>Architecture</b></td><td>Micro Frontends · Design Systems · Multi-Tenant SaaS · System Design</td></tr>
<tr><td><b>Cloud & Tooling</b></td><td>Docker · AWS · CI/CD · Git</td></tr>
</table>

<br />

## Currently Exploring

<table>
<tr>
<td width="33%" valign="top">

**Agentic Developer Tooling**
Navigating and refactoring large microfrontend codebases with AI-assisted agents.

</td>
<td width="33%" valign="top">

**AI-Assisted Architecture Review**
Applying LLMs to enforce SOLID and Clean Architecture boundaries at PR time.

</td>
<td width="34%" valign="top">

**Edge & Runtime Performance**
Streaming, selective hydration, and virtualisation for data-dense fintech UIs.

</td>
</tr>
</table>

<br />

---

<br />

## What I Build

<table>
<tr>
<td width="50%" valign="top">

**Frontend Architecture**
Scalable component systems, micro frontends, and design systems built to survive scale and change.

**SaaS Platforms**
Multi-tenant architecture, subscription lifecycles, billing, and role-based access control.

</td>
<td width="50%" valign="top">

**Enterprise Applications**
Fintech and banking platforms handling real transactional workloads at scale.

**Backend & Cloud Systems**
API design, service architecture, and cloud-native deployments.

</td>
</tr>
</table>

<br />

## Engineering Principles

```
architecture > code        systems are designed, not assembled
simplicity   > cleverness   the best abstraction disappears when unneeded
ownership    > tickets      build what you'd still trust in two years
DX           > afterthought internal tooling deserves the same care as the product
boring tech  > trends       used well, always wins
```

<br />

---

<br />

## Career Timeline

<img src="./assets/timeline.svg" width="100%" alt="Career timeline: NTT Data 2019-2020, Radicle Software 2020-2022, Publicis Sapient 2022-Present" />

<br />

## Client Work

*Enterprise engagements delivered via Publicis Sapient and Radicle Software — code is under client NDA, so these are presented as case studies.*

**NatWest Group — Unified Online Banking Platform** · 2025 – Present · *Lead Frontend Engineer*
- Built a React-based Launchpad micro-app integrating 10+ banking services behind one consistent shell
- Designed framework-agnostic Web Components consumable across React, Angular, and Vue
- Ran knowledge-transfer sessions onboarding 8+ NatWest engineers onto Module Federation patterns

**US Bank — Enterprise Microfrontend Banking Platform** · 2022 – 2024 · *Lead Frontend Engineer / Frontend Architect*
- Architected the Module Federation shell + remote setup for 200+ micro-apps across 10+ squads (see diagram below)
- Designed shared auth state and a global event bus (Observer pattern) for zero-coupling cross-remote communication
- Delivered a 30% increase in user engagement and a 22% reduction in support inquiries

**TIAA — Nuveen Advisor Portal** · 2024 – 2025 · *Frontend Lead*
- Built dynamic, multi-step advisor onboarding workflows from 20+ reusable, validated form components
- Integrated AG-Grid data tables and a Tailwind CSS responsive layout system
- Drove WCAG 2.1 AA accessibility compliance across all new components

**GMetrix — InspectIT Cross-Platform Inspection App** · 2021 – 2022 · *Frontend Architect*
- Architected a shared, UI-independent business logic layer consumed by both React (web) and React Native (iOS/Android)
- Built an offline-capable inspection UI with FlatList virtualisation for large field-inspection datasets

**Panels — Productivity Dashboard** · 2020 – 2021 · *Frontend Architect*
- Architected a modular, multi-data-source dashboard with a plugin-style widget system (Strategy/Factory patterns)
- Optimised data fetching across concurrent widgets via request deduplication and caching

<br />

---

<br />

## Signature Architecture — Microfrontend Shell Pattern

The pattern behind the platforms I've built for US Bank, NatWest, and TIAA: a shell application orchestrating independently deployable remotes, coordinated through shared auth state and an event bus rather than tight coupling — the setup behind 200+ micro-apps across 10+ product squads.

```mermaid
flowchart TB
    classDef shell fill:#F59E0B,stroke:#B45309,color:#111111,stroke-width:2px
    classDef remote fill:#4338CA,stroke:#312E81,color:#ffffff,stroke-width:2px
    classDef core fill:#0D9488,stroke:#134E4A,color:#ffffff,stroke-width:2px

    Shell["Shell Application<br/>(Host / Orchestrator)"]:::shell
    R1["Remote: Accounts"]:::remote
    R2["Remote: Payments"]:::remote
    R3["Remote: Cards"]:::remote
    R4["Remote: Statements"]:::remote
    Auth["Shared Auth State"]:::core
    Bus["Global Event Bus<br/>(Observer Pattern)"]:::core
    Router["Cross-App Router"]:::core

    Shell --> R1
    Shell --> R2
    Shell --> R3
    Shell --> R4
    R1 --> Auth
    R2 --> Auth
    R3 --> Bus
    R4 --> Bus
    Auth --> Router
    Bus --> Router
```

<br />

---

<br />

## Featured Work

### FuelKhata — SaaS Platform for Petrol Pump Operations
*Built via TresTech*

A multi-tenant SaaS platform that helps petrol pump owners manage daily operations end-to-end — shift reporting, fuel sales, stock and density tracking, sales registers, and subscription-based access.

**System Capabilities**
- Multi-tenant architecture with tenant isolation
- Role-based access control across hierarchies
- Subscription lifecycle management
- Automated shift and stock reporting workflows
- Operational analytics and reporting pipeline

```mermaid
flowchart LR
    classDef fe fill:#4338CA,stroke:#312E81,color:#ffffff,stroke-width:2px
    classDef be fill:#0D9488,stroke:#134E4A,color:#ffffff,stroke-width:2px
    classDef db fill:#F59E0B,stroke:#B45309,color:#111111,stroke-width:2px

    ZS["Zustand Store"]:::fe
    UI["React + TypeScript UI"]:::fe
    RQ["TanStack Query"]:::fe
    API["Express REST API"]:::be
    MW["Tenant Isolation<br/>Middleware"]:::be
    MG[("MongoDB + Mongoose")]:::db

    ZS --> UI
    UI --> RQ
    RQ -->|HTTPS| API
    API --> MW
    MW --> MG
```

The frontend is built around a query-driven data layer (TanStack Query) with lightweight local state (Zustand), keeping server state and UI state cleanly separated — a pattern that scales cleanly across a growing number of tenant-specific views. The backend follows a service-oriented structure on top of Express, with schema-driven data modeling in Mongoose supporting strict multi-tenant data boundaries.

<br />

## Other Projects

<table>
<tr>
<td width="50%" valign="top">

**DSA Visualization Platform**
An interactive learning platform for understanding data structures and algorithms — combining algorithm visualization, guided walkthroughs, and system design modules.

</td>
<td width="50%" valign="top">

**Open Source Packages**
A growing set of reusable, enterprise-ready npm packages focused on developer productivity and common engineering patterns.

</td>
</tr>
</table>

<br />

---

<br />

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aaasingh905/aaasingh905/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aaasingh905/aaasingh905/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/aaasingh905/aaasingh905/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

<br /><br />

<img src="https://img.shields.io/github/followers/aaasingh905?style=for-the-badge&color=4338CA&label=Followers&logo=github&logoColor=white" />
<img src="https://komarev.com/ghpvc/?username=aaasingh905&style=for-the-badge&color=F59E0B&label=Profile+Views" />

</div>

<br />

---

<br />

<div align="center">

### Let's build something worth architecting.

<a href="https://www.linkedin.com/in/anurag-singh-6661a5179/"><img src="https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/aaasingh905"><img src="https://img.shields.io/badge/GitHub-4338CA?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://trestech.in"><img src="https://img.shields.io/badge/TresTech-4338CA?style=for-the-badge&logo=vercel&logoColor=white" /></a>

</div>
