<h1>Ted Bankong</h1>

**Engineering lead and full-stack engineer in Lagos, Nigeria.**
I design and build products end to end: mobile apps, backend services, payments, search, infrastructure, and software that talks to hardware.

5+ years shipping across fintech, commerce, defence, logistics, and legal tech. I've led engineering teams, co-founded a company, and taken products from a blank page to the App Store and Play Store.

<p>
  <a href="https://tedbankong.com.ng"><img src="https://img.shields.io/badge/Website-tedbankong.com.ng-111?style=flat-square" alt="Website" /></a>
  <a href="mailto:bankong.ted@gmail.com"><img src="https://img.shields.io/badge/Email-bankong.ted%40gmail.com-111?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://x.com/tedbankong"><img src="https://img.shields.io/badge/X-@tedbankong-111?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
</p>

---

## What I'm building

### Terra Industries · Full-Stack Engineer
Software for security and surveillance infrastructure that runs on real hardware in the field.

- Architected and built **Sentinel** from scratch, a real-time monitoring system for a network of distributed sentry towers.
- Live alerts over **server-sent events**, plus control interfaces for operating towers remotely.
- Media processing pipelines feeding **AI inference models** for threat detection, classification, and incident reports on live streams.
- Work spans Go, Supabase, IP cameras, networking, and command-and-control interfaces. I'm also contributing to drone and gimbal systems.

### Rewear · Co-Founder & Technical Lead
An AI-enabled social commerce platform for fashion sellers in Nigeria. Live on iOS and Android with 500+ users. [rewearapp.com](https://rewearapp.com)

I designed the architecture and led engineering across every layer:

```mermaid
flowchart LR
    App["Flutter app<br/>iOS + Android"] --> API["Go API<br/>Railway"]
    Admin["Vue.js admin"] --> API
    API --> DB[("Supabase Postgres<br/>+ pgvector")]
    API --> R2[("Cloudflare R2<br/>media")]
    API --> SQS["AWS SQS"] --> Lambda["AWS Lambda<br/>async workers"]
    Paystack["Paystack"] -- webhooks --> API
```

- **Hybrid search.** Full-text search and multimodal vector embeddings (pgvector), merged with Reciprocal Rank Fusion. Buyers can search with words or with a photo.
- **Payments.** Checkout, escrow-style transaction flows, seller balances, settlements, and payouts on Paystack. Orders move through explicit states so a payment is never the end of the story.
- **AI listings.** Turns product photos and existing seller content into structured listings, including importing inventory straight from a seller's Instagram.
- **Logistics.** Delivery fees, fulfilment, and order tracking built into the purchase flow.
- **Operations.** Auth, notifications, observability, release pipelines, and deployment for mobile and backend.

### Stead · Co-Founder
A group working across housing, business FX, and software. Through Stead Innovations we build products for companies and institutions, including voter accreditation software for **LASIEC**, the Lagos State Independent Electoral Commission.

---

## Previously

| Where | Role | Highlights |
| --- | --- | --- |
| **Saleswave** | Flutter Engineer | Rebuilt the Legalpedia desktop app and migrated 17,000+ legal cases with zero data loss. Real-time GPS tracking and route optimization for Faramove and Roppi. |
| **Edge** | Engineering Team Lead | Led a multidisciplinary team building iCase, a legal tech platform. Owned architecture, sprint planning, code review, and delivery. |
| **Edge** | Mobile Engineer | Flutter and Kotlin apps. Native platform channels for camera, biometrics, and notifications. |
| **BlinxHQ** | Lead Mobile Engineer | Fintech automation app with real-time transaction monitoring. KYC with Smile Identity and Metamap. Supabase row-level security. OTA updates with Shorebird. |
| **Amaswitch** | Mobile Developer | Fintech app integrating 9 payment service banks and full KYC flows. Biometric auth and Fastlane CI/CD. |
| **Appceiv** | Senior Frontend Developer | Led remote frontend teams on React, Vue, and Next.js. Wrote and audited Ethereum smart contracts. |
| **NAMA** | Database Administrator | Data validation, consistency scripts, and backup and recovery for the Nigerian Airspace Management Agency. |

---

## Stack

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

**Mobile and web**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![SolidJS](https://img.shields.io/badge/SolidJS-2C4F7C?style=flat-square&logo=solid&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)

**Backend**
![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=gin&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

**Data and infrastructure**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS_Lambda_·_SQS_·_S3_·_SAM-232F3E?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Paystack](https://img.shields.io/badge/Paystack-00C3F7?style=flat-square)

**Areas I go deep on:** payment systems, real-time systems (SSE and WebSockets), search and embeddings, API design, KYC and identity verification, mobile CI/CD, and software that controls hardware.

---

## How I work

- I start from the problem and the people who have it, then pick the simplest system that solves it.
- I own things end to end: architecture, code, deployment, monitoring, and what happens when it breaks in production.
- As a lead, my job is to clear the path. I break work down, review code, unblock engineers, and keep technical decisions tied to what the business needs.

> Most of my production work lives in private company repositories. Happy to walk through any of the systems above in more detail.

---

<sub>Away from the screen: cars, photography, and industrial design.</sub>
