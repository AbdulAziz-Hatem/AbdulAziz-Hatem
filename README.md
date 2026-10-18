# AbdulAziz Hatem

## About

I'm an Android systems developer, accessibility researcher, and senior student of Quranic Sciences at Sana'a University. My work lives at the intersection of deep mobile systems engineering, digital accessibility, and resilient cloud architectures — built entirely from the command line on Android.

Being a blind developer who relies on various Android screen readers every day, I don't treat accessibility as an afterthought or a compliance checkbox. It is the fundamental lens through which I inspect, build, and re-engineer software. If an interface isn't predictable, responsive, and barrier-free, it is broken by design.

---

## What I Build

### 1. Digital Accessibility & Android Engineering
- **Upstream Open-Source Contributions:** Enhanced TalkBack navigation and semantics in [`ShizuCallRecorder`](https://github.com/AbdulAziz-Hatem/ShizuCallRecorder) (PR #89 merged upstream), added complete Arabic/RTL localization to [`wifi-password-manager`](https://github.com/AbdulAziz-Hatem/wifi-password-manager) (PR #31 + signed v1.15.0 releases), and built accessibility-first forks for [`NetLimiter`](https://github.com/AbdulAziz-Hatem/NetLimiter).
- **Security & Privacy Hardening:** Maintained and enhanced [`privacify-premer`](https://github.com/AbdulAziz-Hatem/privacify-premer), adding full Arabic localization (239 strings, RTL) and building an autonomous background `Auto-Guard` protection engine with automated signed release workflows.
- **Modern Voice & AI Features:** Built [`PixelBoard`](https://github.com/AbdulAziz-Hatem/PixelBoard) to port and sideload advanced on-device AI voice typing and editing tools to any Android device without root.

### 2. Android Systems, Binary Patching & Reverse Engineering
- **Low-Level DEX & Native Surgery:** Perform direct in-archive DEX manipulation, Smali instrumentation, and ARM64 machine-code disassembly and patching via a custom Termux/CLI toolchain (`d8`, `apkeditor`, `baksmali`, `radare2`, `patchelf`).
- **Runtime Hardening & Screen Reader Engines:** Engineered automated patching frameworks (`Talkman Engine`) for screen reader stability, crash prevention, and null-safety injection across native libraries (`.so`) and Android bytecode.
- **Hardware & Protocol Diagnostics:** Performed low-level Qualcomm Diag protocol audits and NV item inspections over USB OTG and Termux.

### 3. Cloud, AI Proxies & Serverless Infrastructure
- **24/7 AI Gateways:** Designed and deployed `AbdehGate` (`cpa-cloud-server`), an always-on Dockerized AI gateway on Northflank reverse-proxying Claude, GPT, and Gemini models with sub-second latency, WebSocket relays (`/v1/ws`), and automated CI/CD builds.
- **Native Telegram Serverless Bots:** Engineered multi-platform content publishers (*Medad*) and network query engines (*Faseeh 4G*) running 100% on native Telegram Serverless (`tgcloud`) with SQLite databases and reactive living screens.
- **Edge APIs & Security:** Built *yemdata*, a high-resilience serverless proxy on Cloudflare Workers and Netlify with API key authentication, RESTful blob caching, and IP-based rate limiting.

### 4. Interactive Web Platforms
- **Madarej Platform:** Created and launched [`interactive-exams-platform`](https://github.com/AbdulAziz-Hatem/interactive-exams-platform), a fast, zero-dependency interactive examination and self-assessment web platform for university students.

---

## Technical Toolbelt

- **Languages:** Kotlin, Java, Go, Python, Lua, Bash / POSIX Shell, JavaScript, ARM64 Assembly (inspection & binary patching).
- **Android Internals:** Jetpack Compose, Android SDK / NDK, Shizuku & ADB, Smali / DEX surgery, Termux Proot / Rootfs environments.
- **Cloud & Automation:** Docker, Northflank, Cloudflare Workers, Netlify Functions, Telegram Cloud (`tgcloud`), GitHub Actions CI/CD.
- **Protocols & Networking:** WebSocket Relays, Model Context Protocol (MCP), REST APIs, Reverse Proxies, Traffic Shaping.

---

## Education

Senior Student (Final Year) of Quranic Sciences at the Faculty of Education, Sana'a University. My studies ground my technical philosophy: disciplined inquiry, textual verification, and building tools that serve genuine human needs.

---

## Roadmap

- [x] Contribute accessibility improvements and localizations to leading open-source Android tools.
- [x] Architect and deploy resilient 24/7 cloud AI proxy gateways and serverless engines.
- [x] Launch web-based interactive examination platforms for university peers.
- [ ] Publish an original, standalone open-source accessibility utility on Android.
- [ ] Document mobile-first CLI workflows and native reverse engineering methodologies for screen reader users.
