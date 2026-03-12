# Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer focused on trustworthy CTR prediction and sequential recommendation  
Proof: Avazu 2M (Kaggle, Tesla T4) — AUC 0.72659 / LogLoss 0.40009  
Leakage-safe & reproducible: time-split + label-shuffle sanity + `reports/metrics.json`

## Featured Projects
- **[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — leakage-safe CTR benchmark with sequential modeling
- **[ctr-api](https://github.com/yoonjihyung2023/ctr-api)** — FastAPI + Docker serving demo for CTR-style inference
- **[ranking-eval-toolkit](https://github.com/yoonjihyung2023/ranking-eval-toolkit)** — reusable ranking metrics toolkit (AUC, LogLoss, Precision@K, Recall@K, NDCG@K)

## What I build
- **Trustworthy offline CTR evaluation** with **time-based split** and **label-shuffle sanity**
- **Sequential user modeling** for CTR / RecSys experiments
- **Reproducible ML pipeline**: train → eval → `reports/metrics.json`
- **Serving-ready demo** with **FastAPI + Docker**
- **Reusable evaluation utilities** for ranking metrics and offline experiments

## Core Stack
Python, PyTorch, pandas, scikit-learn, FastAPI, Docker, GitHub Actions, Kaggle

## Focus
I am building practical ML proof for **Ads / RecSys ML Engineer** roles:
- leakage-safe offline evaluation
- sequential recommendation / CTR prediction
- reproducible experimentation
- simple production-minded serving
