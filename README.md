<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1b4d3e&height=180&section=header&text=Hi,%20I'm%20Arleu%20Júnior&fontSize=40&fontColor=3ECF8E" alt="Header Banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=3ECF8E&center=true&vCenter=true&width=500&height=50&lines=Future+Agricultural+Engineer;Data+Engineer+%26+Backend+Dev;Driven+by+AgTech+Innovation" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://professional-site-ashen.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/-Website-000000?style=flat-square&logo=vercel&logoColor=3ECF8E" alt="Website" />
  </a>
  <a href="https://github.com/arleujr" target="_blank">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/arleujunior" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:arleujr30@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="assets/docs/arleucv.pdf" target="_blank">
    <img src="https://img.shields.io/badge/-Curriculum_/_CV-E74C3C?style=flat-square&logo=adobe-acrobat-reader&logoColor=white" alt="Resume" />
  </a>
</p>

---

## 👤 About Me

Agricultural Engineering student at the Federal University of Viçosa (UFV) specializing in the intersection of **Precision Agriculture, Asynchronous Systems, and Data Engineering**[cite: 3]. I combine deep field operations insight with a robust backend stack to design real-time data ingestion pipelines, cloud-hosted microservices, distributed IoT architectures, and statistical data quality engines[cite: 3]. Highly autonomous and geared towards optimization via AI and clean code principles.

---

## 📊 Top Languages & Stats

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs?username=arleujr&layout=compact&theme=dark" alt="Arleu's Most Used Languages" />
</p>

---

## 💼 Professional Highlights

* **Independent Developer (Freelancer):** Building high-performance backend infrastructure with Python and Rust, optimizing relational and time-series architectures (PostgreSQL, TimescaleDB)[cite: 1].
* **Pif Paf Alimentos (Intern):** Architected an end-to-end predictive MVP app using Streamlit and implemented robust data cleaning pipelines filtering sensor metrics before an XGBoost machine learning layer[cite: 1].
* **ADWA Cannabis (Intern):** Developed data logging workflows to track complex environmental variables and vegetative propagation, ensuring strict process traceability[cite: 1].
* **GeCotton (UFV):** Built and deployed **Nomino**, a custom automated Python tool to parse spreadsheet datasets, streamline post-event administrative flows, and digitally sign certificates[cite: 1].

---

## 📦 Featured Projects

<details>
<summary><strong>AgriSentry Ecosystem (AgTech IoT)</strong> - Click to expand</summary>
<br>

Microservices-based architecture designed for real-time agricultural telemetry ingestion, streaming, and data quality processing. The system automatically sanitizes raw field sensor data using advanced statistical intelligence[cite: 3].

* **Ecosystem Status:** Live in the Cloud[cite: 3]
* **Repositories:** [AgriSentry Core](https://github.com/arleujr/agrisentry-core) | [Device Simulator](https://github.com/arleujr/agrisentry-device-simulator)[cite: 3]
* **Live Demo Endpoint:** `https://agrisentry-core.onrender.com/`[cite: 3]

#### System Architecture
`Edge Simulator (Python) ➡️ MQTT Broker (EMQX) ➡️ Gateway (Rust) ➡️ Supabase (Postgres Pooler) ⬅️ Core API (FastAPI Worker)`[cite: 3]

#### Technical Highlights
* **Industrial Simulation:** Emulates multiple real-world agricultural field hardware nodes transmitting via MQTT protocol (Paho-MQTT/EMQX)[cite: 3].
* **Data Quality Engine:** An asynchronous background worker (FastAPI/AsyncIO) that fetches raw telemetry data in batches and eliminates hardware noise using Statistical Z-Score (Pandas)[cite: 3].
* **Extreme Resilience:** Implemented Exponential Backoff with Jitter on the database processing loop, ensuring the system survives network blips or database maintenance without causing self-inflicted DoS attacks[cite: 3].
* **Connection Optimization:** Seamless integration with Supabase's Transaction Pooler (port 6543), efficiently managing multiple concurrent async database connections[cite: 3].
</details>

<details>
<summary><strong>DevGuard Core</strong> - Click to expand</summary>
<br>

A high-performance security engine designed to monitor application environments, manage asynchronous access tokens, and mitigate infrastructure vulnerabilities in real-time[cite: 3].

* **Repository:** [DevGuard Core](https://github.com/arleujr/dev-guard-core)[cite: 3]
* **Status:** Fully Functional / Production Ready[cite: 3]

#### Technical Highlights
* **Secure Token Management:** Built-in cryptographic orchestration layer ensuring zero-trust communication across downstream services[cite: 3].
* **Asynchronous Auditing:** Leverages highly efficient background threads to log and analyze system event metrics without introducing latency to user-facing APIs[cite: 3].
</details>

---

## 🛠️ Tech Stack & Tools

<details>
<summary><strong>View Full Technology Stack</strong> - Click to expand</summary>
<br>

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=lists&logoColor=white) |
| **Data Eng & Cloud** | ![Apache NiFi](https://img.shields.io/badge/Apache_NiFi-A11F3C?style=flat-square&logo=apache-nifi&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-FF3600?style=flat-square&logo=databricks&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apache-spark&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-F15A24?style=flat-square&logo=timescaledb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Frameworks & ML** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Protocols & DevOps** | ![MQTT](https://img.shields.io/badge/MQTT-3C525C?style=flat-square&logo=mqtt&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

</details>

---

## 🎯 Top Professional Certifications

* **Databricks Academy:** Data Engineering Foundations & Autonomous AI Agents Architecture[cite: 2]
* **AWS Skill Builder:** Technical Essentials for AgriTech & Cloud Practitioner[cite: 2]
* **MongoDB University:** Aggregation Fundamentals (ETL Pipelines) & NoSQL Modeling[cite: 2]
* **MIT & Santander Academy:** Internet of Things (IoT) & Digital Transformation[cite: 2]
