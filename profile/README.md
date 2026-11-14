# jopedro-labs

Personal projects organization — learning experiments, financial management systems, shared helpers, API clients, and quantitative tooling.

## Projects

| Repository                                                           | Stack                                                                                                                                                                                                                                                                                                                                                                                                                                        | Description                                                                                                                                                                                                                                                             |
|:---------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [core-lib](https://github.com/jopedro-labs/core-lib)                 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-261230?style=flat-square&logo=ruff&logoColor=white) ![Mypy](https://img.shields.io/badge/Mypy-316192?style=flat-square&logo=mypy&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)                                          | Shared Python core library for personal automation and cross-project utilities, featuring strict type safety, automated quality gates, and production-grade CI/CD.                                                                                                      |
| [finances-manager](https://github.com/jopedro-labs/finances-manager) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white) ![Gemini AI](https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) | CLI-driven investment portfolio tracker and quantitative decision engine with multi-factor opportunity scoring, look-through exposure auditing, AI-powered rebalance advisory, and SQLite persistence. Synced via Google Drive SSoT with a full CI/CD quality pipeline. |

### Core-Lib Content & Utilities

* 📊 **`core_lib.logger`:** Structured terminal logger with ANSI colors and timestamps.
* 📁 **`core_lib.file_utils`:** Safe file-loading utilities designed to read content cleanly without throwing exceptions.
* ☁️ **`core_lib.gdrive`:** OAuth2 Google Drive client supporting credential management, remote folder access verification, file existence checks, safe uploads with optional overwrite, downloads, and automated backup sync.
* 💬 **`core_lib.discord`:** Discord webhook client and notifier (`DiscordNotifier`) for sending automated status notifications, rich messages, and system alerts[cite: 7].

## About

Home for personal learning projects, financial management systems, shared helpers, third-party service clients, and quantitative systems. All repositories follow strict production-grade standards: fully tested, statically typed, linted, and gated via automated CI/CD pipelines.

---

Developed and maintained by **João Pedro** ([@JoPedro15](https://github.com/JoPedro15)).

> *Fueled by Espresso, CrossFit WODs, and powered by Gemini AI.* ☕🏋️‍♂️🤖