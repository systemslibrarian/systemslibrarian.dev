# Paul Clark · Systems Analyst · Library Technologist · Security & Cryptography

I build production systems where security, AI, and public service intersect — from library platforms that staff depend on daily to cryptographic protocols and Scripture apps that matter.

**Application Systems Analyst · MLIS · Google Data Analytics Certified**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian/)
[![GitHub followers](https://img.shields.io/github/followers/systemslibrarian?label=Follow&style=social)](https://github.com/systemslibrarian)

---

## Start Here

Recommended projects to explore my work:

🔐 **[Meow Decoder](https://github.com/systemslibrarian/meow-decoder)** — Secure optical air-gap file transfer via animated QR-code GIFs. AES-256-GCM + Argon2id + ML-KEM-1024 + fountain codes. Explicit threat model, fail-closed design.

🧪 **[Crypto Lab](https://crypto-lab.systemslibrarian.dev** — 99 browser-based cryptography demos spanning deniable encryption, post-quantum, zero-knowledge proofs, FHE, and more. Real primitives. No backends. Just the math.

✝️ **[Scripture Journey](https://scripturejourney.com)** — A Christ-centered PWA mapping 200+ Old Testament prophecies to their New Testament fulfillments.

🤖 **[AI Conversation Platform](https://github.com/systemslibrarian/ai-conversation-platform)** — Multi-agent LLM orchestration with circuit breakers, observability, and 90%+ test coverage.

---

## About

By day I'm a systems analyst (IT Librarian) behind production systems a public library depends on — patron registration, access control, ILS integrations, and automated workflows that staff and patrons use without thinking about them, because they just work.

Outside work I'm building air-gapped crypto tools, multi-agent AI platforms, and Scripture apps that matter to me personally. Scripture Journey and Hide in Heart aren't side projects — they're the same discipline applied to something eternal.

The cryptography work isn't a hobby track separate from my library career — it's the foundation underneath it. Patron data is sensitive by nature. I built Crypto Lab, Shadow Vault, Meow Decoder, and the rest because I wanted to understand AEAD encryption, key derivation, deniable containers, and post-quantum primitives at the implementation level — not just call a library and hope it works. Every production system I ship reflects that: AES-256-GCM encrypted uploads, HMAC-validated webhooks, fail-closed parsing, explicit threat models. The demos exist so the discipline shows.

I use AI as a real development partner — faster without cutting corners on architecture or correctness.

My Christian faith is the throughline. Clarity, integrity, and building things worth depending on.

---

## Engineering Focus Areas

- **Security Engineering & Applied Cryptography** — Protocol design, AEAD encryption, post-quantum primitives, threat modeling, and fail-safe architectures
- **AI Systems & Multi-Agent Orchestration** — Coordinating multiple LLMs for reasoning, comparison, and collaborative problem-solving
- **Library Systems Integration** — Connecting ILS platforms, access control, reservations, and patron workflows
- **Data Pipelines & Analytics** — Turning raw public-sector data into actionable insights
- **Human-Centered Design** — Prioritizing reliability, accessibility, and real-world usefulness

---

## Technical Toolkit

| Category | Technologies & Tools |
|---|---|
| **Languages** | C#, TypeScript, JavaScript, Python, Rust, SQL |
| **Frameworks** | .NET 8, ASP.NET Core MVC, Next.js, Node.js |
| **AI / ML** | Multi-Agent Orchestration, LLM APIs, Prompt Engineering |
| **Data** | SQL Server, Power BI, Pandas, APIs, Observability |
| **Security** | AES-256-GCM, Argon2id, HMAC, Post-Quantum (ML-KEM, SMAUG-T, HAETAE), Threat Modeling, Fail-Closed Design |
| **Practices** | TDD, Security Reviews, WCAG Accessibility, Ethical & Human-Centered Design |

---

## Featured Projects

### 🔐 Meow Decoder

A research tool for secure data transfer across air gaps using animated QR code frames. The phone acts only as an untrusted optical channel — all cryptographic operations stay on the secure endpoints. Built as a tribute to my Navy-veteran father.

**Key Features:**
- AES-256-GCM with Argon2id key derivation
- ML-KEM-1024 post-quantum hybrid keys
- Fountain codes for reliable optical transmission
- Explicit, versioned byte-level protocol specification
- Fail-closed parsing with tamper detection

> *Status: Actively hardening — not yet externally audited. All cryptographic primitives are standard, publicly vetted algorithms. Security depends on correct implementation.*

### 🤖 AI Conversation Platform

Async platform for orchestrating real-time conversations between multiple LLMs — useful for comparing model reasoning, stress-testing arguments, and exploring how different AI systems approach the same problem.

**Key Features:**
- Supports Claude, ChatGPT, Gemini, Grok, and Perplexity
- Async orchestration with circuit breakers and rate limiting
- Observability via Prometheus + Grafana
- LLM Guard integration and security hardening
- Dockerized with CI/CD and 90%+ test coverage

### ✝️ Scripture Journey

A Christ-centered web app that helps readers explore how the entire Bible points to Jesus through 200+ messianic prophecy lessons. Built to show that Scripture is one unified story, and Jesus is the center of all of it.

**Tech Stack:** Next.js · TypeScript · Tailwind CSS

🌐 [Live Site](https://scripturejourney.com)

---

## Additional Projects

| | Project | Description |
|---|---|---|
| 🧪 | **[Crypto Compare](https://github.com/systemslibrarian/crypto-compare)** | Reference tool cataloging 16 cryptographic algorithm categories with linked interactive demos |
| 🔮 | **Phantom Vault** | Stateless PBKDF2 password manager — no database, no storage, no sync; passwords derived on demand |
| 🌑 | **Shadow Vault** | Deniable encryption with Argon2id + ChaCha20-Poly1305 — two keys, two plaintexts, no way to prove which is real |
| ⚡ | **Corrupted Oracle** | Educational demo of the Dual_EC_DRBG backdoor and why CSPRNG design matters |
| 🧬 | **[Quantum Vault (KPQC)](https://github.com/systemslibrarian/quantum-vault-kpqc)** | Browser-based threshold secret storage using Korean PQC algorithms (SMAUG-T, HAETAE) compiled to WASM — bilingual EN/KR |
| 🏛️ | **[Cipher Museum](https://ciphermuseum.com)** | Interactive platform exploring 2,500 years of cryptographic history across 10 halls and 37 ciphers |
| ✝️ | **[Hide in Heart](https://hideinheart.com)** | A calm daily companion for hiding God's Word in your heart — rooted in Psalm 119:11 |
| 🙏 | **PrayerWarriors** | Platform for organizing prayer requests and tracking intercession |
| 📖 | **[HisWillGuide](https://hiswillguide.com)** | Finding God's will through Scripture, prayer, and wisdom |
| 📊 | **IMLS Public Libraries Analysis** | Analysis of U.S. public library service and funding trends using IMLS survey data |
| 📚 | **NYT Bestsellers CatKey Generator** | Automates SirsiDynix catalog key creation using current NYT Bestseller data |

---

## Production Systems (Private)

Live systems built for a public library institution — not open-sourced due to security and operational sensitivity.

🔒 **Secure Patron Registration Platform + Staff Administration Dashboard** — Replaced a manual paper-based registration process with a full-stack ASP.NET Core system — encrypted document uploads (AES-256-GCM), malware scanning, ArcGIS address validation, and automated patron record creation through SirsiDynix Symphony Web Services.

🚪 **SwipeWatcher — Real-Time Access Control Event Monitor** — Monitors C•CURE 9000 door events in real time via HMAC-validated webhooks, with automated staff alerting and structured logging.

🔑 **LibCal ↔ C•CURE 9000 Integration** *(Team Project)* — Patrons unlock meeting rooms with their library cards — no staff intervention required. Automatic access provisioning driven by LibCal reservation data. *Recognized with an I² (Innovator / Inspirator) Award.*

📦 **LibCal ↔ SirsiDynix Integration** *(Team Project)* — Eliminated manual checkout processing for Library of Things equipment by triggering circulation transactions directly from LibCal reservation events.

---

## Let's Connect

Open to conversations on secure AI systems, library technology, applied cryptography, or projects that serve the public good. If you're building something meaningful, I'd love to connect.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/systemslibrarian/)

---

*"So whether you eat or drink or whatever you do, do it all for the glory of God." — 1 Corinthians 10:31 (NIV)*
