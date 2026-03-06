# 👋 Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer | CTR Prediction | Sequential Recommendation  
Proof: Avazu CTR 2M (Kaggle, Tesla T4) — AUC 0.72659 / LogLoss 0.40009  
Leakage-safe: time-based split + label-shuffle sanity  
Reproducible: `py -m src.run` → `reports/metrics.json`  
Pinned: `ctr-seqrec-avazu` + `ctr-api`

## 🔗 Featured Projects
- **[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR + sequential modeling (time-split, label-shuffle, reproducible metrics)
- **[ctr-api](https://github.com/yoonjihyung2023/ctr-api)** — FastAPI/Docker serving demo (`/health`, `/model-info`, `/predict`)

## ✅ What I do
- Leakage-safe offline evaluation with **time-based split** and **label-shuffle sanity check**
- End-to-end pipeline: **train → eval → `reports/metrics.json`**
- Serving-ready demo with **FastAPI + Docker**

## ▶️ Quick run
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

## Stack
Python · PyTorch · SQL · Docker · GitHub Actions

## Open to
Ads/RecSys ML Engineer (CTR / Ranking / Seq Modeling / Serving)

## Contact
- ✉️ yoonjihyung22@yonsei.ac.kr
- [Kaggle Notebook](https://www.kaggle.com/code/yoonjihyung/notebook260213)
