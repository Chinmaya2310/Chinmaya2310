# Hi, I'm Chinmaya Kumar Nayak 👋

I'm doing an **M.Tech in Cyber Laws & Information Security at IIIT Allahabad**. My research is on **adversarial attacks against GNN-based malware detectors**.
Before this I was a Digital Specialist Engineer at **Infosys** (Java / AEM). I build full-stack systems and security tooling in **Python, Java and C++**.

- 🔬 **Thesis:** evading GNN malware detectors with active opcode insertion
- 🧑‍🏫 Teaching Assistant at IIIT Allahabad for Operating Systems, Cyber Security, and Design & Analysis of Algorithms
- 🏆 GATE 2025 (CS): score 582, top 2.2% nationwide
- 🎓 B.E. Information Science & Engineering, New Horizon College of Engineering (GPA 9.02/10)
- 📫 chinmayanayak018@gmail.com

---

## 🚀 Featured Projects

### 🔐 [BidirectAuth](https://github.com/Chinmaya2310/BidirectAuth): Mutual Authentication for MQTT
Arrowhead Framework · HiveMQ · Java · Python · RSA · JWE/JWT
- Clients authenticate with Arrowhead-issued **JWE tokens** (RSA-OAEP-256 + AES-256-CBC). The broker proves its identity with **RSA signatures over per-connection nonces**.
- A custom **HiveMQ broker extension** enforces per-packet topic authorization and keeps a 5-minute replay-protection cache.
- Found and fixed a **fail-open vulnerability** that let telemetry leak to a rogue broker.

### 💊 [Pharma Prescriber Analytics & Forecasting Copilot](https://github.com/Chinmaya2310/pharma-prescriber-copilot)
FastAPI · Streamlit · Groq LLM · scikit-learn · XGBoost · Prophet · PyArrow
- **Text-to-SQL** assistant over real CMS Medicare Part D data, with SQL validation and injection-safety checks.
- Prescriber segmentation and drug-level demand forecasting.
- A chunked PyArrow ETL cut peak memory by **70% (763 MB → 225 MB)** with zero data loss.
- 🌐 [Live dashboard](https://pharma-prescriber-copilot-dwzwektf9uyprjavcp9ytr.streamlit.app) · [API docs](https://pharma-prescriber-copilot.onrender.com/docs)

### 🦠 MalAOI: Adversarial Evasion of GNN-Based Malware Detectors *(M.Tech thesis, in progress)*
PyTorch · LIEF · Keystone · BODMAS
- Reproducing and extending a 2025 *Scientific Reports* attack (active opcode insertion + RL) against **GCN, GAT and DGCNN** detectors on real binaries.
- Got the real-binary attack pipeline running end-to-end, with byte-level PE patching in LIEF and Keystone.
- Built a static verification framework that traces instruction-level control and data flow to confirm the modified binaries still work.

### 🧠 More
- [Codebase Understanding Engine](https://github.com/Chinmaya2310/Codebase-Understanding-Engine): AI-powered code intelligence to explore, analyze and query any GitHub repo (FastAPI + React)
- [Product Analytics & A/B Testing Platform](https://github.com/Chinmaya2310/Product-Analytics-A-B-Testing-Platform): funnels, retention and statistically valid A/B experiments

---

## 🛠️ Skills

- **Languages:** C/C++ · Python · Java · SQL
- **Security:** Malware Analysis · Adversarial ML · PE Binary Patching (LIEF, Keystone) · Static Analysis · Applied Cryptography (RSA, JWE/JWT) · MQTT Security
- **Frameworks & ML:** FastAPI · Django · Node.js · React · Streamlit · PyTorch · scikit-learn · XGBoost
- **Databases & Tools:** PostgreSQL · MongoDB · SQLite · Git · HiveMQ
