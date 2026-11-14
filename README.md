# Hi, I'm Vũ Hiếu Kiên

**Full-Stack & AI Systems Engineer** • Vietnam • [hieukien2k6@gmail.com](mailto:hieukien2k6@gmail.com)

I build production web platforms, guardrailed AI pipelines, cloud-edge systems (Cloudflare Workers/D1/R2, Docker, VPS), and native Windows desktop automation (Rust/Tauri, .NET 10 WPF/UIA3).

---

## Featured Open-Source Projects

| Project | Architecture & Stack | Demo / Status |
| :--- | :--- | :--- |
| [**`marketflow-ai`**](https://github.com/hieu-kiien/marketflow-ai) | AI-assisted marketing campaign & content operations platform — **FastAPI**, **React + TypeScript**, isolated AI Runner with safety guardrails, HITL content approval & offline prompt evaluation harness | [Live Demo](https://marketing.kienhieu.id.vn) • [![CI](https://github.com/hieu-kiien/marketflow-ai/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/marketflow-ai/actions/workflows/ci.yml) |
| [**`vietfarm-trace`**](https://github.com/hieu-kiien/vietfarm-trace) | Cold-chain & agricultural lot traceability platform — **FastAPI**, **PostgreSQL 16 (RLS)**, **React 19**, DAG split/merge genealogy, SHA-256 tamper-evident hash chain & 6-role RBAC | [Staging Demo](https://ttcs-frontend-staging.onrender.com) • [![CI](https://github.com/hieu-kiien/vietfarm-trace/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/vietfarm-trace/actions/workflows/ci.yml) |
| [**`auto-tts-desktop`**](https://github.com/hieu-kiien/auto-tts-desktop) | Native Vietnamese Text-to-Speech desktop studio — **Tauri v2**, **Rust**, **Svelte 5**, Vietnamese sentence/chapter chunker & PCM/WAV silence-gap merger | [![CI](https://github.com/hieu-kiien/auto-tts-desktop/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/auto-tts-desktop/actions/workflows/ci.yml) |
| [**`capcut-auto-render`**](https://github.com/hieu-kiien/capcut-auto-render) | Unattended Windows batch-render orchestrator — **.NET 10 WPF MVVM**, **FlaUI UIA3**, **SQLite** schema v2 job persistence & **FFmpeg/FFprobe** export verification | [![Build](https://github.com/hieu-kiien/capcut-auto-render/actions/workflows/build.yml/badge.svg)](https://github.com/hieu-kiien/capcut-auto-render/actions/workflows/build.yml) |
| [**`facebook-content-aggregator`**](https://github.com/hieu-kiien/facebook-content-aggregator) | Event-driven content intelligence pipeline — **Meta Messenger Webhook (HMAC-SHA256)**, **FastAPI**, **Redis**, Cloud Whisper STT, multi-LLM analysis, **Supabase**, **Notion** sync & **Telegram** bot | [![CI](https://github.com/hieu-kiien/facebook-content-aggregator/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/facebook-content-aggregator/actions/workflows/ci.yml) |
| [**`petshop-devops-observability`**](https://github.com/hieu-kiien/petshop-devops-observability) | Containerized observability & DevSecOps reference stack — **Node.js**, **Prometheus**, **Alertmanager**, **Grafana**, **Loki + Promtail**, **Nginx** & **Trivy** workflows | [![Checks](https://github.com/hieu-kiien/petshop-devops-observability/actions/workflows/static-check.yml/badge.svg)](https://github.com/hieu-kiien/petshop-devops-observability/actions/workflows/static-check.yml) |

---

## Production & Client Case Studies *(Private Repositories)*

- **B2B Lean Commerce Platform (`giacong.vn` — Private):** Next.js + TypeScript storefront and streamlined operations admin deployed natively on **Cloudflare Workers, D1, and R2**, paired with Google Sheets / Apps Script webhook queues for B2B order & quote workflows.
- **Automotive Lubricants Distribution Web Platform (`gtoil.vn` — Private):** Product catalog and dealer portal built with **Next.js 16 (App Router, React 19, TypeScript)**, **Tailwind CSS v4 (`oklch` design tokens)**, and **Radix UI**, deployed at the edge via **OpenNext (`@opennextjs/cloudflare`)**.

---

## Core Stack

- **Languages:** TypeScript, Python, Rust, C# (.NET 10), SQL
- **Frameworks & UI:** React, Next.js, Svelte 5, FastAPI, Tauri v2, WPF (MVVM + FlaUI UIA3)
- **Data & Messaging:** PostgreSQL (RLS), SQLite, Redis, Supabase, Notion API
- **Infrastructure & CI/CD:** Cloudflare (Workers, D1, R2, Tunnel), Docker, Nginx, Prometheus, Grafana, Loki, GitHub Actions
