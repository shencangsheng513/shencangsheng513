# Hi there, I'm Shen He (沈鹤) 👋

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Quantitative%20Finance%20%26%20ML%20Systems-blue" />
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LightGBM-4A90E2" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-1.5.9-orange" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## 🎯 Profile Overview

- 🎓 **Education**: Jiangnan University (江南大学 · 211工程) — Big Data Management and Application (大数据管理与应用)
- 💼 **Target Role**: **ByteDance (字节跳动) · AI算法 / 机器学习系统 / 量化工程实习生**
- 🔬 **Core Focus**:
  - **Machine Learning & Quantitative Modeling**: Alpha factor engineering (50+ factors), Conformal Risk prediction (CQR), TreeSHAP 2nd-order interaction analysis, monotonic business constraint modeling.
  - **LLM Application & RAG Systems**: Dense-sparse hybrid search (BM25 + ChromaDB), citation tracking, answerability verification, and token budget management.
  - **Production ML Systems & Rigor**: Deterministic engineering gates (Git pre-commit defenses, zero silent failures), realistic backtesting (stamp duty, commission, slippage), and high-reliability API microservices.

---

## 🌟 Featured Open-Source Repositories

| Repository | Tech Stack | Highlights |
|:---|:---|:---|
| **[QuantFlow](https://github.com/shencangsheng513/QuantFlow)** | Python, PyTorch, LightGBM, Flask, Conformal Prediction | **Production-grade Quantitative ML & Realistic Backtesting Engine**<br>• 50+ alpha features (momentum, volatility, money flow, technical)<br>• Soft-routing Mixture of Experts (MoE) & Conformal Risk (CQR 95% corridor)<br>• Realistic backtest with slippage & commission (8.17% out-of-sample return)<br>• 140+ unit & integration tests with 100% pass rate |
| **[scientific-xai-suite](https://github.com/shencangsheng513/scientific-xai-suite)** | Python, XGBoost, CatBoost, SHAP, Optuna | **Publication-Grade Interpretable ML & Credit Risk Modeling Suite**<br>• TreeSHAP 2nd-order interaction matrix & Centred ICE (c-ICE) heterogeneity analysis<br>• Credit Risk Scorecard with Weight of Evidence (WOE) & Information Value (IV)<br>• Monotonic business constraint auditor & Decision Curve Analysis (DCA)<br>• Interactive web visualization showcase |
| **[financial-rag-engine](https://github.com/shencangsheng513/financial-rag-engine)** | Python, ChromaDB, BM25, Flask, BAAI/bge-small-zh | **Enterprise Financial RAG Engine with Citation & Hallucination Guard**<br>• Dense-sparse hybrid retrieval combining BAAI/bge-small-zh embeddings with BM25<br>• Dynamic cross-encoder reranker with answerability threshold evaluation<br>• Generation token budgeting guard and strict citation symbol verification<br>• 34+ unit tests passing |
| **[news-classifier-service](https://github.com/shencangsheng513/news-classifier-service)** | Python, FastAPI, Docker, Render, Scikit-learn | **Live Production ML Inference Microservice (Cloud Deployed)**<br>• End-to-end containerized text classification service with live demo on Render<br>• Bearer token authentication middleware with zero-token probe paths (`/healthz`, `/ready`)<br>• Full Swagger API documentation and latency profiling (~180ms cloud cold, <25ms local)<br>• Direct Dockerfile recipe with pinned scikit-learn environment |
| **[ml-tutorial](https://github.com/shencangsheng513/ml-tutorial)** | Python, Scikit-learn, PyTorch, MLflow, FastAPI | **Hands-on End-to-End ML Engineering Lab Portfolio**<br>• 4 full-stack projects + 6 engineering labs<br>• FastAPI production deployment with latency benchmarking (<20ms)<br>• Multi-round scientific RAG ablation experiments with hypothesis testing<br>• Model distillation & compression experiments |

---

## 🛠️ Tech Stack & Architecture

```mermaid
flowchart LR
    A["Data Engineering & Pipeline"] --> B["Feature & Factor Zoo"]
    B --> C["Statistical & ML / LLM Models"]
    C --> D["Backtest & Guard Verification"]
    D --> E["Production Deployment & API"]

    subgraph Pipeline ["Full-Lifecycle Delivery"]
        A
        B
        C
        D
        E
    end
```

- **Languages**: Python (Proficient), SQL, TypeScript/JavaScript, Bash/PowerShell
- **ML & Data**: PyTorch, LightGBM, XGBoost, CatBoost, Scikit-Learn, SHAP, Optuna, NumPy, Pandas, PyArrow
- **LLM & RAG**: ChromaDB, BM25, Vector Search, Embedding Models, Hybrid Retrieval
- **Web & Backend**: FastAPI, Flask, Pydantic, SQLAlchemy, PyMySQL, RESTful APIs, Docker

---

## 📬 Contact & Links

- 📧 **Email**: 2273899131@qq.com
- 💻 **GitHub**: [github.com/shencangsheng513](https://github.com/shencangsheng513)
- 📍 **Location**: Wuxi / Shenyang, China
