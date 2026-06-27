<img width="100%" src="[https://raw.githubusercontent.com/aditya-dolas-thinkersteps/aditya-dolas-thinkersteps/main/assets/divider.svg](https://images.unsplash.com/photo-1644325349124-d1756b79dd42?q=80&w=1775&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)" />

# Aditya Dolas

**Systems · Product · Rust**

I write software that's meant to last — low-level when it counts, full-stack when it ships.  
Currently: Shopify apps, Rust microservices, auth systems nobody wants to think about but everyone needs.

### Full Stack Engineer · Rust × Shopify
*Building high-performance systems where Rust's safety guarantees meet Shopify's merchant ecosystem.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adityadolas-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/adityadolas)
[![GitHub followers](https://img.shields.io/github/followers/aditya-dolas-thinkersteps?style=flat-square&label=Follow&logo=github)](https://github.com/aditya-dolas-thinkersteps)
![Location](https://img.shields.io/badge/Nagpur%2C%20India-🇮🇳-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Status-Open%20to%20Collaborate-brightgreen?style=flat-square)

</div>

---

Full Stack Developer at **ThinkerSteps Technologies** with a dual focus: systems-level Rust engineering and Shopify ecosystem product development. I write security-critical auth flows, image rendering pipelines, and encrypted data vaults — then build the admin UIs that sit on top of them.

Currently deep in **FAPI 2.0 / Singpass** integration, **Rust ONNX inference pipelines**, and **GSAP animation** for a portfolio that actually represents the work.

---

## Stack

**Systems**
`Rust` `Axum` `ONNX / ort` `Docker` `Contabo VPS`

**Fullstack**
`TypeScript` `Remix` `React` `NestJS` `Node.js`

**Data**
`PostgreSQL` `ScyllaDB` `Prisma`

**Shopify**
`Polaris Web Components` `Shopify Admin GraphQL` `Theme Extensions` `Metafields`

**Security**
`FAPI 2.0` `DPoP` `PAR` `JWE` `JWT / JWKS` `AES-256-GCM` `PBKDF2` `RBAC / ABAC`

**Tooling**
`GitHub Actions` `GSAP` `Tailwind CSS`

---

## Selected Work

### 🦀 `necklace_renderer` — Rust Virtual Try-On Pipeline
> High-performance 2D jewelry try-on microservice

MediaPipe Pose/Hands keypoints → ONNX inference via `ort` crate → overlay parameters (position, scale, rotation) computed per keypoint and stored as Shopify product metafields (`custom.tryon_params`). Deployed on Contabo VPS in Docker.

`Rust` `ONNX` `MediaPipe` `Docker` `Shopify Metafields`

[![View Repo](https://img.shields.io/badge/View_Repo-necklace__renderer-D85A30?style=flat-square&logo=github)](https://github.com/aditya-dolas-thinkersteps/necklace_renderer)

---

### 🔐 `VerifyPass` — Singpass KYC App
> End-to-end identity verification for Shopify merchants

Full FAPI 2.0 flow: PAR → DPoP-bound auth code → `private_key_jwt` client assertion → JWE-encrypted MyInfo `/person` response. PII stored in an AES-256-GCM + PBKDF2 vault with bcrypt-hashed vault password and a multi-stage OTP reset flow. Admin UI built with Shopify Polaris web components (`s-*` elements), backed by Prisma `OnboardingApplication` and `SingpassVerification` models.

`Remix` `TypeScript` `Singpass` `FAPI 2.0` `DPoP` `JWE` `AES-256-GCM` `Prisma` `Shopify Polaris`

---

### 🗺 `GeoLocation Heatmap` — Merchant Analytics
> Choropleth world map for the Shopify admin

Leaflet + chroma-js, stale-closure-free data binding, map re-initialization guard on data change, and double-API-call prevention via strict effect dependencies. Batch-safe Shopify Admin GraphQL queries.

`Remix` `Leaflet` `chroma-js` `Shopify Admin GraphQL`

---

### 🤖 `Monorepo Chat Agent` — VS Code Extension
> AI coding assistant tuned to my exact stack

Slash commands `/component`, `/route`, `/schema`, `/api`, `/task` — each with automatic workspace context injection (Remix routes, Polaris web components, Prisma schema, Shopify Admin GraphQL 2024-01). No generic completions; every suggestion is monorepo-aware.

`TypeScript` `VS Code API` `Shopify` `Prisma`

---

### 📊 `PostgreSQL Backup Automation`
> Cron-scheduled backups targeting Contabo S3

Multi-database support, retention pruning, and GitHub Actions integration. Designed around the same VPS infrastructure that runs the Rust microservices.

`PostgreSQL` `Bash` `GitHub Actions` `Contabo S3`

---

---

<div align="center">

**Open to collaborating on** Shopify integrations · Rust open-source · full-stack MERN

[![LinkedIn](https://img.shields.io/badge/-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/adityadolas)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=for-the-badge&logo=github)](https://github.com/aditya-dolas-thinkersteps)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>
