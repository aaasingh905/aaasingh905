<div align="center">

# Anurag Singh

**Lead Experience Engineer**

Building scalable frontend architectures, SaaS platforms, and developer-friendly systems.

`React` · `TypeScript` · `Node.js` · `System Design` · `SaaS Architecture`

</div>

<br />

## About

I'm a software engineer with 8+ years of experience designing and building large-scale, customer-facing applications — primarily across fintech, banking, and SaaS platforms. My work sits at the intersection of frontend architecture and backend systems: I care about how products are structured underneath as much as how they feel to use.

I lead engineering efforts that require both technical depth and product judgment — from multi-tenant SaaS platforms to enterprise financial applications used by real businesses at scale.

<br />

## What I Build

| Area | Focus |
|---|---|
| **Frontend Architecture** | Scalable component systems, micro frontends, design systems |
| **SaaS Platforms** | Multi-tenant architecture, subscription lifecycles, RBAC |
| **Enterprise Applications** | Fintech & banking platforms, customer-facing systems at scale |
| **Backend Services** | API design, service architecture, cloud-native deployments |
| **Developer Tooling** | Reusable packages, internal tooling, engineering productivity |

<br />

## Engineering Principles

- **Architecture before code.** Systems should be designed to survive scale and change, not just ship features.
- **Simplicity is a discipline.** The best abstraction is the one that disappears when you don't need it.
- **Ownership over tickets.** I build things I'd be comfortable maintaining two years from now.
- **Developer experience is product experience.** Internal tooling deserves the same care as customer-facing UI.
- **Boring technology, used well, beats trendy technology, used poorly.**

<br />

## Featured Work

### FuelKhata — SaaS Platform for Petrol Pump Operations

A multi-tenant SaaS platform that helps petrol pump owners manage daily operations end-to-end — shift reporting, fuel sales, stock and density tracking, sales registers, and subscription-based access.

**System capabilities**
- Multi-tenant SaaS architecture with tenant isolation
- Role-based access control across operational hierarchies
- Subscription lifecycle management (trials, upgrades, renewals)
- Automated business workflows for shift and stock reporting
- Reporting and analytics pipeline for operational insights

**Architecture**

```
Frontend                          Backend
─────────────────────             ─────────────────────
React + TypeScript                Node.js + Express
React Router                      TypeScript
TanStack Query                    MongoDB + Mongoose
Zustand
Tailwind CSS + shadcn/ui
```

The frontend is built around a query-driven data layer (TanStack Query) with lightweight local state (Zustand), keeping server state and UI state cleanly separated — a pattern that scales well across a growing number of tenant-specific views. The backend follows a service-oriented structure on top of Express, with schema-driven data modeling in Mongoose supporting the multi-tenant data boundaries.

<br />

## Other Projects

**DSA Visualization Platform**
A learning platform for understanding data structures and algorithms through visual, interactive explanations — combining algorithm visualization, guided walkthroughs, and system design learning modules.

**Open Source Packages**
A growing set of reusable, enterprise-ready npm packages focused on developer productivity and common engineering patterns — built to be dropped into real projects, not just demos.

<br />

## Technical Stack

**Languages & Core**
`TypeScript` `JavaScript` `Node.js`

**Frontend**
`React` `React Router` `TanStack Query` `Zustand` `Tailwind CSS` `shadcn/ui`

**Backend & Data**
`Express` `MongoDB` `Mongoose` `REST APIs`

**Architecture & Systems**
`Micro Frontends` `Design Systems` `Multi-Tenant SaaS` `System Design` `Cloud-Native Deployment`

<br />

## Currently Exploring

- AI Engineering & LLM-powered applications
- Autonomous AI agents and agentic workflows
- Advanced system design patterns
- Developer tooling and platform engineering
- Open-source contribution at scale

<br />

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aaasingh905&show_icons=true&theme=default&hide_border=true&hide_title=true" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=aaasingh905&hide_border=true" width="48%" />

</div>

<br />

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000000?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anurag-singh-6661a5179/)
[![GitHub](https://img.shields.io/badge/-GitHub-000000?style=flat&logo=github&logoColor=white)](https://github.com/aaasingh905)
[![TresTech](https://img.shields.io/badge/-TresTech-000000?style=flat&logo=vercel&logoColor=white)](https://trestech.in)

</div>

<br />

<div align="center">
<sub>Designing systems that scale, one architecture decision at a time.</sub>
</div>
