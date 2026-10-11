# Hey, I'm Milkboy ☕

I build practical systems that run fast, cost almost nothing to host, and don't fall over when the internet blinks.

I believe most modern software is absurdly overengineered. If an application needs 16GB of RAM and four cloud microservices just to serve text, the architecture is broken. I'd rather squeeze 110% performance out of modest hardware than burn money on cloud bills.

---

### 🛠️ The Workbench (Things You Can Actually Click)

* **[grav-ai-chatbot](https://github.com/milkboyinchina/grav-ai-chatbot)**  
  An AI chatbot plugin for Grav CMS with local RAG, SQLite vector search, and leetspeak/jailbreak defenses.  
  *Yes, the live demo on [milkboy.my.id](https://www.milkboy.my.id) is powered by a janky Intel Celeron N4100 mini-PC* running quantized Qwen via a private NetBird tunnel. At ~3.6 tokens/sec it’s not breaking speed records, but tight context trimming keeps it snappy in real time. (Don't judge me, I'm not made of money).

* **[api-indonesia.com](https://api-indonesia.com)**  
  A clean, fast directory and documentation portal for public Indonesian APIs. Built on flat-file Grav CMS so pages load instantly without database connection pools crashing under traffic spikes.

* **[docker-lamp-grav](https://github.com/milkboyinchina/docker-lamp-grav)**  
  My personal Docker LAMP environment. No bloated layers: just Apache, PHP 8.3/8.4, MariaDB, and automated bash backup scripts that do their job and get out of the way.

* **[Milkys-Sound-Booster-EQ](https://github.com/milkboyinchina/Milkys-Sound-Booster-EQ)**  
  A native Android equalizer written in Kotlin when stock phone audio just wasn't loud enough.

---

### 💼 What I Do When I'm Not Tinkering

Most of my heaviest work isn't public on GitHub because it runs behind private client firewalls:

* **Zero-Trust Remote Access for SMEs (NetBird Mesh):**  
  Fixing the classic small business nightmare: remote staff need access to office file servers and internal tools, but opening router ports to the public internet is an invitation for bots to brute-force the network. I deploy zero-port NetBird mesh overlays that give staff secure access while giving managers granular control over who can touch what.

* **MilkTechERP (Sovereign Business Platform):**  
  A self-hosted, air-gapped business OS built with Django and PostgreSQL for businesses tired of paying monthly SaaS extortion. Handles real-world Indonesian statutory tax compliance (PPh 21 TER, BPJS, e-Faktur) and cryptographic Merkle WORM audit trails over private peer-to-peer networks.  
  👉 *[Read the architecture breakdown](https://www.milkboy.my.id/blog/sovereign-erp-architecture)*

* **AI Technical Due Diligence for Angel Investors:**  
  Cutting through startup hype for early-stage investors. I audit raw benchmark logs, inspect codebases, and stress-test GPU compute burn rates to figure out if a pitch deck has real mathematical breakthroughs or is just burning investor runway on marketing.

* **Minimal-Downtime SysOps:**  
  Server migrations, reverse proxy routing, and keeping production systems humming on budget Linux VPS setups.

---

### 🚧 Currently in the Works

* **ANAIS (Android Node AI Server)**  
  Turning Android phones into offline, on-device AI servers:
  * **Dual-Process Architecture:** Kotlin & Jetpack Compose UI isolated from a native `:server` daemon via AIDL, preventing C++ crashes from killing the app.
  * **C++20 NDK Engine:** Custom `IAIEngine` facade wrapping `llama.cpp` with dynamic SoC hardware acceleration.
  * **Dynamic Memory Governor:** Real-time profiling against Android's `lmkd` kill lines to safely load 4B to 14B models without kernel panics.
  * **Network Compatibility:** Serves an OpenAI-compatible REST API (`/v1/chat/completions`) and Ollama emulation over local WiFi and NetBird mesh.

---

### Stack I Actually Trust
`Linux` · `NetBird` · `Docker` · `Bash` · `PHP / Grav CMS` · `Python / Django` · `PostgreSQL` · `Ollama` · `Kotlin`
