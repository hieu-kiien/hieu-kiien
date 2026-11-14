# Hi, I'm Vũ Hiếu Kiên

**Undergraduate IT Student (`Sinh viên CNTT`)** • Vietnam • [hieukien2k6@gmail.com](mailto:hieukien2k6@gmail.com)

Focused on **Automation (`Tự động hoá`)**, **AI Evaluation & Tooling (`Nghiên cứu AI`)**, and **Applied AI Products (`Ứng dụng AI tạo sản phẩm`)** — building end-to-end systems with explicit data contracts, human-in-the-loop safety, and automated CI checks.

---

## Featured Public Projects

| Project | Description & Architecture | Demo / CI |
| :--- | :--- | :--- |
| [**`marketflow-ai`**](https://github.com/hieu-kiien/marketflow-ai) | Marketing workflow & campaign platform with human-in-the-loop AI draft proposals (`PROPOSED` approval gate), isolated `ai-runner` (`OpenCode` + Bearer-scoped MCP), offline evaluation harness — **FastAPI**, **PostgreSQL / SQLite**, **React + TypeScript**, **Docker** | [Live Demo](https://marketing.kienhieu.id.vn) • [![CI](https://github.com/hieu-kiien/marketflow-ai/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/marketflow-ai/actions/workflows/ci.yml) |
| [**`auto-tts-desktop`**](https://github.com/hieu-kiien/auto-tts-desktop) | Local-first Vietnamese Text-to-Speech desktop studio — **Rust**, **Tauri v2**, **Svelte 5**, **SQLite**, Windows Credential Manager (`keyring` BYOK), Tokio actor queue, Vietnamese text chunker, 24kHz PCM/WAV merger & Gemini TTS API | [![CI](https://github.com/hieu-kiien/auto-tts-desktop/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/auto-tts-desktop/actions/workflows/ci.yml) |
| [**`facebook-content-aggregator`**](https://github.com/hieu-kiien/facebook-content-aggregator) | Event-driven Messenger ingestion & AI content pipeline with HMAC verification, DLQ retry, **Whisper STT**, multi-LLM extraction, **Notion** rate-limited sync & **Telegram** Q&A bot — **Python 3.12**, **FastAPI**, **Redis**, **Supabase** | [![CI](https://github.com/hieu-kiien/facebook-content-aggregator/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/facebook-content-aggregator/actions/workflows/ci.yml) |
| [**`vietfarm-trace`**](https://github.com/hieu-kiien/vietfarm-trace) | Agricultural cold-chain traceability platform featuring DAG split/merge genealogy, SHA-256 event hash chain, sliding-window sensor violation detection & 6-role RBAC — **FastAPI**, **PostgreSQL 16 (RLS)**, **React 19 + TypeScript**, **Docker** | `Local Docker Compose` • [![CI](https://github.com/hieu-kiien/vietfarm-trace/actions/workflows/ci.yml/badge.svg)](https://github.com/hieu-kiien/vietfarm-trace/actions/workflows/ci.yml) |

---

## Core Stack

- **Languages:** Python, TypeScript, Rust, SQL
- **Frameworks & UI:** FastAPI, React, Svelte 5, Tauri v2, Tokio
- **AI & Automation:** Gemini API, Whisper STT, Multi-LLM Pipelines, MCP Tooling, Offline Eval Harnesses
- **Databases & Infra:** PostgreSQL (RLS), Redis, SQLite, Supabase, Docker, Nginx, GitHub Actions
