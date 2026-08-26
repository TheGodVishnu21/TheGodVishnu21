<div align="center">

<img src="Untitled266_20240306192312.png" alt="logo" width="110"/>

# Ishaan Sandhwar

**B.Tech CSE — AI/ML specialization @ Lovely Professional University · Class of 2028**

Algorithms se pehle library nahi. PSO, Dijkstra, heaps, hash maps — scratch se likhta hoon, phir libraries use karta hoon.

[![Email](https://img.shields.io/badge/Email-thegodempire17@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:thegodempire17@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-HANDLE-HERE)
[![X](https://img.shields.io/badge/X-@TheGodVishnu21-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/thegodvishnu21)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/FMVyVEX3ua)

</div>

---

## 📌 Featured Projects

### 🚨 LifeLine — Smart City Disaster Response & Evacuation Simulator
Zero-dependency **C++17** backend serving a REST API *and* a built React (Vite) frontend from a single static binary. Fictional city of 40 locations and 83 roads.

- Custom **min-heap, max-heap, djb2 hash map, trie, Union-Find** — written from scratch, no STL containers
- Dijkstra, A\*, Bellman-Ford, Floyd-Warshall, Edmonds-Karp max-flow/min-cut, BFS disaster spread, Tarjan bridges, Prim/Kruskal MST, 0/1 knapsack DP
- **96 checks across 5 test suites**, cross-verified against `networkx` over 1,600+ node pairs
- A\* settles **8 nodes vs Dijkstra's 24** on the same 4.78 km path

`C++17` `React` `Vite` `Leaflet` `REST`
→ **[Code](https://github.com/TheGodVishnu21/lifeline)** · [Live demo](https://github.com/TheGodVishnu21/lifeline#demo)

---

### 💳 PSO Credit Card Fraud Detection
Binary **Particle Swarm Optimization implemented from scratch** (sigmoid transfer function, repair mask, early stopping) for feature selection on a heavily imbalanced fraud dataset — 50,000 rows, 492 fraud cases (0.98% positive rate).

- 30 features → **7 selected**; swarm converged at iteration 18 (30 particles, 50 max iters)
- PSO + Random Forest: **ROC-AUC 0.977 · PR-AUC 0.886 · F1 0.888 · MCC 0.888**
- Logistic-regression baseline on all 30 features: ROC-AUC 0.974 · PR-AUC 0.881 — documented honestly, including where precision *drops*
- SMOTE applied to the training split only, 7 unit tests on the PSO core, Parquet caching for 5–10× faster repeat runs, 4-tab Streamlit dashboard

`Python` `scikit-learn` `imbalanced-learn` `Streamlit` `pytest`
→ **[Code](https://github.com/TheGodVishnu21/PSO_Credit_Card_Fraud_Detection)**

---

### 🛍️ Product Intelligence Engine
LLM + RAG pipeline for automated product catalogue enrichment — messy listings in, structured attributes out.

`Python` `LLM` `RAG` `embeddings`
→ **[Code](https://github.com/TheGodVishnu21/product-intelligence-engine)**

<!-- TODO Ishaan: SUBMISSION.md se 3 real bullets uthaake yahan daal — architecture, dataset size, accuracy/latency number. -->

---

### 🤖 Agentic AI for Academic Benefit Nomination · *in progress*
Five-stage agentic system for my university's academic benefits pipeline: VLM document extraction → deterministic eligibility rule engine → bi-encoder + cross-encoder course mapping with contrastive fine-tuning → calibrated approval prediction → agent orchestration with mandatory human confirmation.

Evaluated on Precision@3 / MRR / NDCG@5 with forward-chaining validation, not random splits. Prompt-injection defences built in at the document-parsing layer. Shipping October 2026.

`Python` `sentence-transformers` `LLM agents` `FastAPI`

---

## 🛠️ Stack

**Comfortable**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

**Currently learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📜 Certifications

| Credential | Issuer | Date |
|---|---|---|
| Oracle Cloud Infrastructure 2025 Certified **AI Foundations Associate** | Oracle | Nov 2025 |
| Oracle Data Platform 2025 Certified **Foundations Associate** | Oracle | May 2026 |
| DSA Placement Bootcamp — **Grade O (90%+)** | LPU Centre for Professional Enhancement | Jul 2026 |
| AI Mentorship Internship | Launched Global × Deevelo X | May–Jun 2025 |

---

## 🎯 Currently

- 🔬 Shipping the agentic nomination system — prototype Aug, deployment Oct 2026
- 📈 Andrew Ng's ML Specialization → Deep Learning Specialization
- 🧮 **GATE DA** — 2027 practice run, 2028 for real
- ⚔️ DSA in C++, arrays se shuru, har topic cover karna hai
- 💬 Open to AI/ML internships and research collaborations

---

## 📊 GitHub

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=TheGodVishnu21&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&icon_color=00d9ff&title_color=00d9ff&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheGodVishnu21&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&langs_count=8" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=TheGodVishnu21&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=00d9ff&point=c9d1d9&area=true" />

</div>

---

<div align="center">

*Off the clock: chess, PC gaming, and dark anime.*

</div>
