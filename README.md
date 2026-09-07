<h1 align="center">Ishaan Sandhwar</h1>

<p align="center">
  B.Tech CSE — Artificial Intelligence &amp; Machine Learning<br>
  Lovely Professional University · Class of 2028
</p>

<p align="center">
  <a href="LINKEDIN_URL_YAHAN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:EMAIL_YAHAN"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I build ML systems end to end — data, model, evaluation, and the interface someone actually uses. Most of my work sits around retrieval, LLM pipelines and classical ML, with a bias toward measuring things honestly rather than shipping a demo that only looks good.

Currently working on retrieval fine-tuning, and preparing for GATE DA.

---

## Featured Projects

### Agentic AI for Academic Benefit Nomination
A five-stage system that reads student achievement documents, checks eligibility against published rules, maps achievements to university courses, and drafts a nomination for human approval. Built for LPU's EDU Revolution programme.

`Python` `FastAPI` `PyTorch` `Sentence Transformers` `scikit-learn` `React` `TypeScript`

- Document-type classifier using MiniLM embeddings + keyword hybrid — **macro F1 0.916** against a 0.394 phrase-table baseline, evaluated on a grouped unseen-template split
- Course mapping via a bi-encoder fine-tuned on hard negatives mined from the retriever's own top-20 errors — **+0.454 MRR** over TF-IDF and **+0.133 P@1** over the zero-shot encoder on held-out queries
- Benchmarked a cross-encoder reranker, found it memorised training queries and transferred nothing (held-out separation −0.037), and **shipped it disabled** with the negative result documented
- Extraction cascade (PDF text layer → local OCR → vision LLM), inspectable rule engine, server-side RBAC, 1,071 tests

**[REPO_LINK_YAHAN]**

---

### LifeLine — Smart City Disaster Response & Evacuation Simulator
A disaster response simulator over a fictional city of 40 locations and 83 roads. Zero-dependency C++17 backend serving a REST API and a built React frontend from a single static binary.

`C++17` `React` `Vite` `Leaflet`

- Min-heap, max-heap, djb2 hash map, trie and Union-Find written from scratch instead of using the STL
- Dijkstra, A\*, Bellman-Ford, Floyd-Warshall, Edmonds-Karp max-flow/min-cut, BFS disaster spread, Tarjan bridges, Prim/Kruskal MST, 0/1 knapsack DP
- 96 checks across 5 test suites, verified against networkx over 1,600+ node pairs
- A\* settles 8 nodes where Dijkstra settles 24 on the same 4.78 km path

Team project (5 members). **[github.com/TheGodVishnu21/lifeline](https://github.com/TheGodVishnu21/lifeline)** · [Live demo](DEMO_LINK_YAHAN)

---

### PSO Feature Selection for Credit Card Fraud Detection
Binary Particle Swarm Optimisation implemented from scratch — sigmoid transfer function, repair mask, early stopping — to select features for fraud detection on a heavily imbalanced dataset.

`Python` `scikit-learn` `Streamlit` `imbalanced-learn`

- 50,000-row stratified sample, 492 fraud cases (0.98% positive rate); SMOTE applied to the training split only
- 30 particles over 50 max iterations, converged at iteration 18 and cut 30 features down to 7
- PSO + Random Forest: **ROC-AUC 0.977, PR-AUC 0.886, F1 0.888**, against a full-feature logistic regression baseline at ROC-AUC 0.974 / PR-AUC 0.881 / F1 0.906 — ranking metrics improve, precision trades off
- Four-tab Streamlit dashboard, 7 unit tests on the PSO core, Parquet caching for 5–10× faster repeat runs

Built with one collaborator. **[github.com/TheGodVishnu21/pso-fraud-feature-selection](https://github.com/TheGodVishnu21/pso-fraud-feature-selection)**

---

### Product Intelligence Engine
An LLM/RAG pipeline for enriching product catalogue data.

`Python` `LLMs` `RAG`

- METRIC_YAHAN_DAAL — ek concrete number repo ke README se utha ke yahan likh
- METRIC_YAHAN_DAAL

Team project (4 members). **[github.com/TheGodVishnu21/product-intelligence-engine](https://github.com/TheGodVishnu21/product-intelligence-engine)**

---

## Skills

**Languages** — Python, C++, Java, JavaScript/TypeScript, SQL
**ML** — PyTorch, scikit-learn, Sentence Transformers, pandas, NumPy
**Backend & Tools** — FastAPI, Streamlit, React, Git, Linux, Docker

---

## Certifications

- Oracle Cloud Infrastructure 2025 Certified AI Foundations Associate — *Nov 2025*
- Oracle Data Platform 2025 Certified Foundations Associate — *May 2026*
- DSA Placement Bootcamp, LPU Centre for Professional Enhancement — *Grade O, Jul 2026*

---

## Achievements

- Top 30 Finalist — CodeXtreme 4.0 Java Coding Contest (LPU × iamneo)
- Participant — Algo Arena 2.0, WeInnova8

---

Outside of code I run a Discord community and play more games than I should admit.
