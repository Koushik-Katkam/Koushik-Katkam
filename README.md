<div align="center">

# Koushik Katkam

**Full-Stack Systems Builder | Applied AI & Data Engineering | Mobile & Spatial Computing**

Warangal / Hyderabad, India

[GitHub](https://github.com/Koushik-Katkam) | [LinkedIn](https://linkedin.com/in/koushik-katkam) | [Hugging Face](https://huggingface.co/Koushik-Katkam) | [Kaggle](https://www.kaggle.com/koushikkatkam) | [ORCID](https://orcid.org/0009-0000-8084-557X) | [Email](mailto:koushikkatkam@gmail.com)

</div>

---

## About

I am a B.Tech Data Science student at Kakatiya University College of Engineering and Technology (KUCET), Warangal. I design and build applied software systems spanning edge computer vision, AST-based data governance, document intelligence, privacy-first geospatial routing, and interactive graphics.

My work emphasizes explicit validation boundaries, mathematical invariant guarantees, data provenance, and transparent reporting of prototype constraints.

- **Evidence over assumptions:** Explicit validation, traceable data, and honest reporting of model boundaries.
- **Security by design:** Least privilege, fail-closed authorization, input validation, and secure defaults.
- **Privacy by design:** Local-first storage, minimized data retention, and zero third-party telemetry.
- **Engineering discipline:** Automated testing, reproducible benchmarks, CI/CD, and documented architecture.

---

## Open-Source Contributions

Contributed five merged pull requests to [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills):

### Original Skill Development
- [Cinematic UI/UX](https://github.com/sickn33/agentic-awesome-skills/pull/2420) — Production-oriented motion engineering, GSAP, Lenis, canvas experiences, kinetic typography, and motion accessibility.
- [Codebase-Aware UI Prompts](https://github.com/sickn33/agentic-awesome-skills/pull/2421) — Architecture-preserving AI prompts, component discovery, design-system inheritance, and implementation verification.

### Documentation & Quality Fixes
- [PR #2418](https://github.com/sickn33/agentic-awesome-skills/pull/2418) — Corrected YAML syntax and Terraform block tags in `alerting-oncall`.
- [PR #2419](https://github.com/sickn33/agentic-awesome-skills/pull/2419) — Supplied missing statement in `azure-storage-queue-py` peek loop.
- [PR #2422](https://github.com/sickn33/agentic-awesome-skills/pull/2422) — Corrected shell code fence syntax in `deployment-pipeline-design`.

---

## Featured Projects

### [K² — Classroom Attendance Proposal System](https://github.com/Koushik-Katkam/K-Squared-Face-Recognition-Attendance-System)
**Institutional classroom-photo attendance proposal system for Kakatiya University College of Engineering & Technology (KUCET)**
- Replaces single-face biometric punch kiosks and paper attendance ledgers with an asynchronous, multi-face classroom sweep workflow.
- Computer vision operates strictly as an evidence producer rather than an authoritative decision maker: faculty captures sweep photos, reviews candidate proposals against immutable roster snapshots, and commits atomic verified attendance records.
- Integrates physical camera sweep streaming, OpenCV YuNet face detection, and 5-landmark aligned SFace 128-D vector extraction alongside ArcFace ResNet-50 embeddings (open-set threshold tau = 0.60) with ONNX Runtime.
- **Security, Privacy & Receipts:** Ephemeral frame wiping, client SHA-256 anchoring, zero raw facial image storage, and server-issued HMAC-SHA256 attendance receipts.
- **Verification:** 86 unit and governance tests, 15 Playwright E2E browser tests, 5 mathematical invariant suites, Flutter static analysis, and TypeScript/Dart cross-language contracts.
- **Release & Live App:** [FRS v7.1.0 on GitHub Releases](https://github.com/Koushik-Katkam/K-Squared-Face-Recognition-Attendance-System/releases/tag/v7.1.0) (includes downloadable Android APK asset) | [Admin Console](https://k-squared-face-recognition-attendan.vercel.app/) | [Official Technical Wiki](https://github.com/Koushik-Katkam/K-Squared-Face-Recognition-Attendance-System/wiki)
- **Stack:** Python 3.12, FastAPI, Flutter, Next.js 15, PostgreSQL 16, OpenCV YuNet, SFace, ArcFace, ONNX Runtime, Docker Compose

### [SchemaSense 2.0](https://github.com/Koushik-Katkam/schemasense)
**AI-native database intelligence, governance, and multi-cloud schema analysis platform**
- Connects to relational and cloud databases (PostgreSQL, MySQL, SQLite, AWS RDS, Cloud SQL, Supabase, Neon) to generate interactive data dictionaries, profile data quality, classify sensitive PII entities, and export DBML/DDL schemas.
- Features a dual-mode operational architecture: lightweight Simple Mode (Streamlit) for exploratory analysis and Advanced Mode (FastAPI, Celery, Redis, PostgreSQL) for asynchronous cataloging and deep audit workflows.
- Implements SQLGuard with dialect-aware Python AST parsing and an optional native Rust core (`crates/schemasense_core`) with Rayon parallelism and PyO3 ABI3 bindings, enforcing a strict read-only boundary on user queries.
- Manages an automated 12-state LangGraph agent execution lifecycle with permission checks and human-in-the-loop review gating.
- **Verification:** 450+ automated tests (91% code coverage), 54 adversarial SQL AST tests, CycloneDX SBOM v1.5, and detect-secrets security baseline.
- **Live Demo:** [SchemaSense on Streamlit](https://neural-nexus-schemasense-n9aixu78zu8ebbbahcvvhc.streamlit.app/)
- **Stack:** Python, Rust, PyO3, FastAPI, Streamlit, LangGraph, SQLAlchemy, sqlglot, PostgreSQL, MySQL, SQLite, Redis, Celery

### [ResQ — Unified Women's Safety & Action Platform](https://github.com/Koushik-Katkam/Vyshuuu-Unified-Women-Safety-Action-Platform)
**Evidence-first women's safety, pedestrian navigation, and statutory grievance escalation platform**
- Unifies three interconnected pillars: **Move** (explainable pedestrian route intelligence evaluating corridor amenities and astronomical solar daylight at arrival ETA), **Protect** (cross-platform harassment documentation with SHA-256 cryptographic digests, temporal graph analysis for block evasion, and exposure audits), and **Act** (statutory legal grievance generation and directory under Indian regulatory frameworks: UGC, FSSAI, and PoSH).
- Built with zero cloud telemetry: corridors and incident graphs are encrypted at rest with AES-256-GCM and stored strictly in on-device SQLite; features emergency 112 intent filtering and prompt-isolated AI safety navigation via Google Gemini API.
- Co-authored with [Vyshnavi Nagavelli](https://github.com/nagavellivyshnavi).
- **Verification:** 293/293 tests passing across 55 test suites, full TypeScript type safety, and Fastify server rate limiting with in-memory TTL caching.
- **Documentation:** [Official Technical Wiki](https://github.com/Koushik-Katkam/Vyshuuu-Unified-Women-Safety-Action-Platform/wiki)
- **Stack:** TypeScript, React Native, Expo 58, Fastify, Node.js 22 LTS, SQLite, MapLibre, Google Gemini API

### [GuardAI](https://github.com/Koushik-Katkam/guardai)
**URL threat analysis and real-time security telemetry**
- Automated threat intelligence, lexical heuristic evaluation, and active cryptographic scanning platform.
- Combines DNS/TLS inspection, external reputation lookups (VirusTotal, Google Safe Browsing, AbuseIPDB, URLhaus), Shannon entropy heuristics, and Server-Sent Events (SSE) scan telemetry.
- Features an interactive Three.js/WebGL threat globe with custom GLSL shaders and GSAP animation.
- **Security & Abstention Policy:** 80 Vitest security/regression tests, 11 Playwright E2E tests, 20-vector SSRF test suite with pinned IP transport, rootless multi-stage Docker container (UID 1001), and OpenAPI 3.1 schema. When external threat feeds are absent, the scanner returns an INCONCLUSIVE verdict rather than producing fabricated risk classifications.
- **Live Demo:** [guardai-six.vercel.app](https://guardai-six.vercel.app) | **Documentation:** [GuardAI Wiki](https://github.com/Koushik-Katkam/guardai/wiki)
- **Stack:** Next.js 16, React 19, TypeScript, Prisma, PostgreSQL 16, NextAuth, Three.js, GLSL, Tailwind CSS v4, Docker

### [Walkscope](https://github.com/Koushik-Katkam/Walkscope)
**Transparent, privacy-first pedestrian walking companion and route context scoring engine**
- Mobile-first pedestrian navigation companion that replaces opaque, subjective safety scores with verifiable Route Context Coverage (0 to 100%) and Route Context Intelligence.
- Evaluates OpenStreetMap venue opening hours at projected arrival time, along-route venue distribution gaps, major-road share breakdown, verified support-point registry, and an auditable "Why This Route?" evidence drawer.
- **Privacy & Resilience:** Zero analytics SDKs or advertising trackers; all journey history remains in local-first SQLite. Dedicated Fastify gateway with request deduplication, rate limiting, and in-memory TTL caching with graceful standalone fallback. Verified support-point registry strictly requires independently audited access evidence (defaults to 0 points).
- **Verification:** 253/253 passing tests, 13 CI quality jobs, 11 Playwright E2E tests, SLA latency bounds (p50 < 100ms), ReDoS fuzzing immunity across 500+ patterns, and nearest line-segment off-route detection with kinematic teleportation filtering.
- **Stack:** React Native, Expo 58, TypeScript, Node.js 22 LTS, Fastify, MapLibre Native, SQLite, Docker, Redis, PostGIS

### [NoticeSync](https://github.com/Koushik-Katkam/NoticeSync)
**Academic-document intelligence and calendar-event extraction**
- Ingests university circulars, exam timetables, and syllabi into structured dates using document-grounded RAG with Supabase pgvector and 768-dimensional embeddings.
- Resolves multi-document deadline revisions and temporal conflicts with human-in-the-loop review gating for ambiguous or conflicting dates.
- **Verification & Limitations:** 144 tests across 38 suites, streaming byte bounds, decompression bomb defense, CSRF Fetch Metadata protection, and an empirical benchmark suite (100% extraction F1, 0% false confirmations). Evaluated on 11 synthetic, privacy-safe university circulars; calendar events export as .ics files (automatic Google Calendar synchronization is not implemented).
- **Live Demo:** [notice-sync.vercel.app](https://notice-sync.vercel.app) | **Documentation:** [NoticeSync Wiki](https://github.com/Koushik-Katkam/NoticeSync/wiki)
- **Stack:** Next.js 16, React 19, TypeScript, Supabase (pgvector), Vercel AI SDK, Tesseract.js, pdf-parse, Langfuse

### [CycloneSense](https://github.com/Koushik-Katkam/cyclonesense)
**Explainable multi-source tropical cyclone intelligence and scientific research prototype**
- Ingests and validates Earth-observation data alongside official storm-track records, including workflows for NOAA GOES-16/18 ABI data and NASA Earthdata CMR.
- Integrates a native Rust scientific core (`crates/cyclonesense_core`) with Rayon multithreading and SHA-NI accelerated hashing, exposed to Python via PyO3.
- Implements spatial and temporal validation splits, Grad-CAM spatial heatmaps, and provenance tracking aligned with W3C PROV concepts across NetCDF4, HDF5, and xarray scientific data.
- Co-authored with Varshini Akula and Nivedan Katkam.
- **Verification & Validation Caveat:** 84 backend automated tests and 8 Playwright E2E tests passing. The repository model audit identifies the image-only model raster inputs as synthetic proxy data and the fusion model as a hybrid; reported scores reflect exploratory architecture rather than validated predictive accuracy on authentic satellite imagery.
- **Release:** [CycloneSense v1.0.0 on GitHub Releases](https://github.com/Koushik-Katkam/cyclonesense/releases/tag/v1.0.0).
- **Stack:** Python, Rust, PyO3, FastAPI, PyTorch, Next.js, NetCDF4, HDF5, xarray, SQLAlchemy, Celery

### [BuildMart](https://github.com/Koushik-Katkam/BuildMart)
**Construction-materials procurement marketplace monorepo**
- Consolidates a Next.js 15 commercial procurement web application, a FastAPI backend service, and a Flutter mobile client.
- Implements multi-tenant marketplace workflows, role-based procurement operations, backend API tests, and multi-target CI configuration.
- **Verification & Release:** 59 backend API tests passing with documented test-execution report. [BuildMart v2.0.0 on GitHub Releases](https://github.com/Koushik-Katkam/BuildMart/releases/tag/v2.0.0) (includes downloadable Android APK asset).
- **Stack:** Next.js 15, TypeScript, FastAPI, Python, Flutter, Dart, pnpm, Turborepo

### [KinexMed](https://github.com/Koushik-Katkam/KinexMed)
**Edge-native clinical movement intelligence and physical rehabilitation**
- Real-time rehabilitation-exercise observation built for the iQOO Hackathon 2026 (Hyderabad City Battle).
- Employs MediaPipe Tasks Vision (Pose Landmarker) and CameraX for 100% on-device pose tracking, One-Euro temporal filtering, Euclidean joint geometry, and finite-state machine repetition counting across 15 clinical exercises.
- Integrates Alembic database migrations, clinician REST endpoints with API-key authentication and strict CORS whitelisting, and a React clinician portal.
- **Verification, Privacy & Disclaimer:** 87 automated tests passing across Backend and Playwright (50), Android Subsystem (32), and Web Clinician Portal (5). Raw camera frames are analyzed in-memory and immediately freed with zero video/images stored or transmitted. Assistive observation tool; not a substitute for professional medical diagnosis or unsupervised prescription.
- **Release:** [KinexMed v1.0.0 on GitHub Releases](https://github.com/Koushik-Katkam/KinexMed/releases/tag/v1.0.0) (includes downloadable Android debug APK).
- **Stack:** Kotlin, Android SDK, MediaPipe Tasks Vision, CameraX, Python 3.12, FastAPI, React, Vite, SQLite, Alembic

### [Restaurant Ecosystem](https://github.com/Koushik-Katkam/restaurant-ecosystem)
**Four-brand restaurant web-platform monorepo**
- Consolidates four restaurant applications: Sampradaya, Majesty Mandi House, Mandiwala, and Aroma, with distinct brand aesthetics and deployment workflows.
- Implements digital menus, portion-based pricing calculators, reservation workflows, Clerk authentication, and Firebase/Firestore real-time persistence.
- Co-authored with [Vyshnavi Nagavelli](https://github.com/nagavellivyshnavi).
- **Live Deployments:** [Sampradaya](https://sampradaya-multicuisine-family-rest.vercel.app/) | [Majesty Mandi House](https://majesty-mandi-house-eight.vercel.app/) | [Mandiwala](https://mandiwala-arabian-restaurant.vercel.app/) | [Aroma](https://aroma-fine-dine-restaurant-banquet.vercel.app/)
- **Stack:** Next.js 16, React, TypeScript, Turborepo, Tailwind CSS, Clerk, Firebase/Firestore

### [HealX](https://github.com/Koushik-Katkam/HealX)
**Accessible bilingual healthcare-facility navigation prototype**
- Provides English/Telugu interfaces, browser text-to-speech, high-contrast controls, adjustable typography, and telephony simulation.
- Offers Gemini-assisted natural-language search and a Supabase-backed facility store, with an in-memory Demo Mode for offline evaluation.
- **Data & Scope Disclosure:** Prototype developed for the Seva First Innovation Challenge (SFIC) Level 3. Default facility records are simulated sample data across South India; does not provide medical diagnosis, emergency dispatch, or official government health-record integration.
- **Live Demo:** [healx-six.vercel.app](https://healx-six.vercel.app)
- **Stack:** Next.js, React, TypeScript, Supabase, Google Gemini API, Tailwind CSS

### [VYSHUUU — The Unstitched Continuum](https://github.com/Koushik-Katkam/vyshuuu)
**Digital haute couture house and computational textile experience**
- Immersive digital-fashion experience devoted to the Indian saree, unstitched silk architecture, and computational textile intelligence.
- Employs React Three Fiber and custom GLSL shaders (catenary drape, dynamic traveling pleats, anisotropic zari specular glints) with Lenis smooth-scroll and GSAP ScrollTrigger choreography across 11 curatorial chapters.
- **Asset Architecture & Live Experience:** 95 locked production assets resolved via Cloudinary CDN manifest; 10 curated saree concepts honoring classical Indian textile lineages.
- **Live Experience:** [vyshuuu-five.vercel.app](https://vyshuuu-five.vercel.app)
- **Stack:** Next.js, React, TypeScript, Three.js, React Three Fiber, GLSL, GSAP, Lenis, Zustand, Tailwind CSS

### [StreetSense](https://github.com/Koushik-Katkam/streetsense)
**Adaptive mobile sensing for pedestrian-safety research**
- Combines Android sensor inputs (accelerometer, gyroscope, GPS, ambient light, camera) with a backend event pipeline.
- Implements a selective-escalation architecture intended to call more expensive specialist checks when sensor evidence is ambiguous.
- **Verification, Limitations & Release:** 16 passing tests (12 backend + 4 on-device). The repository verification matrix clarifies that edge-vision weights are not pre-packaged; when absent, the vision expert safely reports UNAVAILABLE rather than returning fabricated detections. [StreetSense v1.0.0 on GitHub Releases](https://github.com/Koushik-Katkam/streetsense/releases/tag/v1.0.0).
- **Stack:** Kotlin, Jetpack Compose, CameraX, Android Room, Python, FastAPI, React, SQLite, PostGIS, WebSockets

### [Proposal Website](https://github.com/Koushik-Katkam/proposal-website)
**Cinematic interactive scroll-based digital romantic storytelling experience**
- Dark-mode visual storytelling experience built with Next.js 16, React 19, Lenis smooth-scroll, glowing typography, and interactive particle effects.
- **Live Demo:** [proposal-website-drab.vercel.app](https://proposal-website-drab.vercel.app/)
- **Stack:** Next.js 16, React 19, TypeScript, Tailwind CSS, Lenis, Framer Motion, Vercel

---

## Technical Skills

- **Languages:** Rust, Python, TypeScript, JavaScript, Kotlin, Dart, SQL, HTML, CSS, GLSL
- **Frameworks & Runtimes:** Next.js (15/16), React (18/19), FastAPI, Fastify, Node.js (22 LTS), Flutter, Android SDK, Jetpack Compose, React Native / Expo, Streamlit, Turborepo
- **AI, ML & Computer Vision:** PyTorch, MediaPipe Tasks Vision, SCRFD Face Detection, ArcFace ResNet-50, OpenCV YuNet, SFace, ONNX Runtime, Document-Grounded RAG, LangGraph, Google Gemini API, Anthropic Claude, Vercel AI SDK, sqlglot, Langfuse, Grad-CAM, NetCDF4, HDF5, xarray
- **Databases & Storage:** PostgreSQL 16 (pgvector), Supabase, PostGIS, SQLite / Android Room, Firebase Firestore, MySQL, Redis, Prisma, SQLAlchemy, Alembic
- **Graphics & Real-Time:** Three.js, React Three Fiber, WebGL, Custom GLSL Shaders, MapLibre Native, GSAP, Lenis, Framer Motion, Server-Sent Events (SSE), WebSockets
- **DevOps, Security & Tooling:** Docker & Docker Compose (rootless multi-stage), GitHub Actions CI/CD, Playwright E2E, Vitest, Pytest, CycloneDX SBOM, Git, pnpm workspaces, Vercel

---

## Connect

- **GitHub:** [Koushik-Katkam](https://github.com/Koushik-Katkam)
- **LinkedIn:** [Koushik Katkam](https://linkedin.com/in/koushik-katkam)
- **Hugging Face:** [Koushik-Katkam](https://huggingface.co/Koushik-Katkam)
- **Kaggle:** [koushikkatkam](https://www.kaggle.com/koushikkatkam)
- **Google Developer Profile:** [koushik-katkam](https://me.developers.google.com/u/koushik-katkam)
- **Google Skills:** [Public Profile](https://www.skills.google/public_profiles/93f9bd7b-1868-4d4a-b5f7-b30fda368712)
- **Commudle:** [Koushikkatkam](https://www.commudle.com/users/Koushikkatkam)
- **ORCID:** [0009-0000-8084-557X](https://orcid.org/0009-0000-8084-557X)
- **Instagram:** [koushik_katkam](https://www.instagram.com/koushik_katkam)
- **Email:** [koushikkatkam@gmail.com](mailto:koushikkatkam@gmail.com)
