# Hey, I'm Milkboy ☕

I'm a generalist who likes building practical tools, tinkering with servers, and seeing how much performance I can squeeze out of minimal hardware.

---

### What I spend my time on
* **SysOps & Zero-Trust Networking:** Linux server administration, Docker environments, and secure overlay networks with **NetBird**. I build zero-port remote access solutions for SMEs—letting staff securely access internal company resources from the public internet without port-forwarding, while giving managers centralized, granular access control (ACLs).
* **Local AI & Edge Hardware:** Squeezing fast inference out of budget hardware. I prefer lightweight local models (Ollama, small Qwen models, SQLite vector search) over burning massive API budgets.
* **Flat-file CMS & PHP:** Developing plugins and themes for Grav CMS so websites stay lean, responsive, and database-independent.

---

### Stuff I've built (Public & Clickable)

* **[grav-ai-chatbot](https://github.com/milkboyinchina/grav-ai-chatbot)**  
  A chatbot plugin for Grav CMS with built-in RAG and prompt security.  
  *Fun fact:* The live demo on [milkboy.my.id](https://www.milkboy.my.id) is routed through NetBird to an Ollama endpoint running on an old Intel Celeron N4100 mini PC. It runs at ~3.6 tokens/sec, but thanks to tight context trimming, it actually works!

* **[api-indonesia.com](https://api-indonesia.com)**  
  A fast directory and documentation portal for Indonesian APIs, built on Grav CMS to keep page loads near-instant.

* **[docker-lamp-grav](https://github.com/milkboyinchina/docker-lamp-grav)**  
  My personal plug-and-play Docker LAMP setup. Nothing bloated—just Apache, modern PHP, MariaDB, and automated backup scripts for running Grav or custom PHP apps.

* **[Milkys-Sound-Booster-EQ](https://github.com/milkboyinchina/Milkys-Sound-Booster-EQ)**  
  A native Android audio equalizer written in Kotlin to boost volume and fine-tune playback.

---

### 🔒 Behind the Scenes (Private & Client Systems)

Not everything I build is open-source. A lot of my day-to-day work lives in private client repos or internal servers:

* **SME Zero-Trust Remote Access (NetBird Infrastructure)**  
  Architected and deployed secure remote access for small-to-medium businesses:
  * Connected remote and mobile staff to internal office networks (file servers, internal portals, ERP) from the public internet without exposing any open ports.
  * Configured granular manager access controls (peer-to-peer ACLs) with centralized device authorization and instant access revocation.

* **MilkTechERP (Sovereign ERP Platform)**  
  A self-hosted business operating platform built with Django and PostgreSQL:
  * Multi-tenant PostgreSQL schema isolation over a private NetBird mesh.
  * Native Indonesian statutory tax engines (PPh 21 TER calculations, BPJS, e-Faktur integration).
  * Cryptographic Merkle WORM ledgers for tamper-proof audit trails.  
  👉 *[Read the architectural whitepaper on my site](https://www.milkboy.my.id/blog/sovereign-erp-architecture)*

* **Custom Client Infrastructure**  
  Minimal-downtime server migrations, reverse proxy orchestration, and keeping small business backends fast and stable on modest infrastructure.
---

### Tools I reach for
`Linux` · `NetBird` · `Docker` · `Bash` · `PHP` · `Python` · `PostgreSQL` · `Ollama` · `Grav CMS` · `Kotlin`
