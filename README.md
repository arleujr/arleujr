<h1 align="center">Arleu Júnior</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=3ECF8E&center=true&vCenter=true&width=500&height=50&lines=Software+Engineer;Industrial+IoT+%26+Data+Engineering;Constantly+evolving+my+technical+stack" alt="Typing SVG" />
</p>

<p align="center">
  Software Engineer focused on Asynchronous Systems, Industrial IoT, and Data Engineering.
</p>

<p align="center">
  <a href="https://linkedin.com/in/arleujunior" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:arleujr30@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=arleujr&show_icons=true&theme=radical&include_all_commits=true&count_private=true" alt="Arleu's GitHub Stats" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arleujr&layout=compact&theme=radical" alt="Arleu's Most Used Languages" />
</p>

---

## Featured Projects

<details>
<summary><strong>AgriSentry Ecosystem (AgTech IoT)</strong> - Click to expand</summary>
<br>

Microservices-based architecture designed for real-time agricultural telemetry ingestion, streaming, and data quality processing. The system automatically sanitizes raw field sensor data using advanced statistical intelligence.

* **Ecosystem Status:** Live in the Cloud
* **Repositories:** [AgriSentry Core](https://github.com/arleujr/agrisentry-core) | [Device Simulator](https://github.com/arleujr/agrisentry-device-simulator)
* **Live Demo Endpoint:** `https://agrisentry-core.onrender.com/`

#### System Architecture
`Edge Simulator (Python) ➡️ MQTT Broker (EMQX) ➡️ Gateway (Rust) ➡️ Supabase (Postgres Pooler) ⬅️ Core API (FastAPI Worker)`

#### Technical Highlights
* **Industrial Simulation:** Emulates multiple real-world agricultural field hardware nodes transmitting via MQTT protocol (Paho-MQTT/EMQX).
* **Data Quality Engine:** An asynchronous background worker (FastAPI/AsyncIO) that fetches raw telemetry data in batches and eliminates hardware noise using Statistical Z-Score (Pandas).
* **Extreme Resilience:** Implemented Exponential Backoff with Jitter on the database processing loop, ensuring the system survives network blips or database maintenance without causing self-inflicted DoS attacks.
* **Connection Optimization:** Seamless integration with Supabase's Transaction Pooler (port 6543), efficiently managing multiple concurrent async database connections.
</details>

<details>
<summary><strong>DevGuard Core</strong> - Click to expand</summary>
<br>

A high-performance security engine designed to monitor application environments, manage asynchronous access tokens, and mitigate infrastructure vulnerabilities in real-time.

* **Repository:** [DevGuard Core](https://github.com/arleujr/dev-guard-core)
* **Status:** Fully Functional / Production Ready

#### Technical Highlights
* **Secure Token Management:** Built-in cryptographic orchestration layer ensuring zero-trust communication across downstream services.
* **Asynchronous Auditing:** Leverages highly efficient background threads to log and analyze system event metrics without introducing latency to user-facing APIs.
</details>

---

## Tech Stack & Tools

<details>
<summary><strong>View Technology Stack</strong> - Click to expand</summary>
<br>

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |
| **Frameworks / APIs** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white) |
| **Databases & Storage** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Protocols & DevOps** | ![MQTT](https://img.shields.io/badge/MQTT-3C525C?style=flat-square&logo=mqtt&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white) |

</details>
