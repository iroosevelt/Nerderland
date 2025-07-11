# 🛸 NERDERLAND

**“Inside every mystery, mystery...”**

**Nerderland** is a timeless, community-powered web platform and creative archive for nerds, yah yah yah... It blends the aesthetic of alien archives, early internet chaos, and next-gen decentralized technology.

A gamified social arena for nerds. Nothing too deep... Or is it?

This project is built to be:

- **Censorship-resistant**
- **Modular and bug-resilient**
- **Built for long-term survival**
- **Fun, weird, and expressive**

---

## ⚙️ Tech Architecture Overview

| Layer                     | Stack                                                           |
| ------------------------- | --------------------------------------------------------------- |
| **Frontend**              | Next.js (App Router), Tailwind CSS, Zustand, TypeScript         |
| **Backend**               | Rust, Axum, Tokio                                               |
| **Database**              | PostgreSQL, Redis                                               |
| **Decentralized Storage** | IPFS (via Web3.Storage), Arweave for archival                   |
| **Auth**                  | JWT + SIWE (Sign-In With Ethereum)                              |
| **Hosting**               | Vercel (Frontend), Fly.io (Backend), Docker + Caddy (Self-host) |
| **Infra as Code**         | Terraform                                                       |
| **Domain**                | nerderland.com (Web2), nerderland.eth (Web3 ENS)                |

---

## 📦 Monorepo Structure (Planned)

```txt
nerderland/
├── apps/
│   ├── web/         # Frontend (Next.js)
│   └── api/         # Backend (Rust, Axum)
├── infra/           # Terraform configs
├── packages/        # Shared TS/Rust utils (future)
├── .github/         # CI/CD workflows
├── README.md
└── LICENSE


```

---

## 🧱 Stack Details and Rationale

### 🌐 Frontend – Next.js

- **Why**: Industry standard for building scalable, SEO-friendly apps
- **App Router**: Edge-ready, layout-based routing
- **Developer Experience**: Seamless with TypeScript, Tailwind, Framer Motion

### 🧠 State Management – Zustand

- Lightweight, predictable, avoids boilerplate
- Ideal for managing interactive state across nerd boards and user profiles

### 🛠 Styling – Tailwind CSS

- Utility-first CSS
- Fast to build, easy to theme, and consistent design

---

### 🦀 Backend – Rust + Axum

- **Rust** is memory-safe, fast, and designed for long-term code health
- **Axum** is a clean async HTTP server built on Tokio, well-suited for scalable APIs
- API returns JSON over REST
- Easily integrates PostgreSQL, Redis, JWT, and background tasks

---

### 🧬 Database Layer

- **PostgreSQL**: Structured, reliable, mature
- **Redis**: For ephemeral storage, caching, and background job queue

---

### 📡 Decentralized Storage

- **IPFS (via Web3.Storage)**: For user-created assets (folders, zines, files)
- **Arweave**: Permanent backup/archival of community-generated history
- **nerderland.eth (ENS)**: For decentralized DNS & wallet identity

---

### 🔐 Authentication

- JWT for session authentication
- SIWE (Sign-In with Ethereum) for wallet-native login & pseudonymity
- Traditional login methods can be added later

---

### 🚀 Hosting

- **Frontend**: Vercel — zero-config and blazing fast
- **Backend**: Fly.io — runs globally-distributed containers for Rust apps
- **Backup**: Docker + Caddy on NixOS (for self-hosted archival)
- **Infra Automation**: Terraform to describe and provision infra reliably

---

### 🧪 Tooling & Dev Experience

- **Frontend**: Prettier, ESLint, TypeScript strict mode, NPM
- **Backend**: Clippy, Rustfmt, Cargo workspaces
- **CI/CD**: GitHub Actions for deployments and lint checks
- **Dev DB**: SQLite (local only) with easy swap to PostgreSQL in prod

---

## 📚 Learning Resources

### 🦀 Learn Rust

- [Rust Book (Official)](https://doc.rust-lang.org/book/)
- [Rustlings](https://github.com/rust-lang/rustlings) – CLI exercises

### 🧠 Zustand

- [Zustand Docs](https://docs.pmnd.rs/zustand)
- [Zustand Examples](https://github.com/pmndrs/zustand/tree/main/examples)

### 🛸 Axum

- [Axum Docs](https://docs.rs/axum)
- [Axum Examples](https://github.com/tokio-rs/axum/tree/main/examples)

### 📡 IPFS

- [web3.storage](https://web3.storage/)
- [IPFS Docs](https://docs.ipfs.tech/)

---

## 🧭 Project Philosophy

This isn’t just software — it’s digital culture. Nerderland is:

- A permanent archive of the weird and wonderful
- A decentralized community powered by curiosity
- A platform that resists deletion, decay, and dullness

> “We don’t just host nerds — we preserve them.”

---

## 👨‍🚀 Built by Humans, floating in space

**Roosevelt Innocent (Trouper)**  
Nerderland Social Arena, 2025  
🧪🛸🧠
