# 👋 Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer — CTR Prediction + Sequential Recommendation  
Proof: Avazu 2M (Kaggle, Tesla T4) — AUC 0.72659 / LogLoss 0.40009  
Leakage-safe & reproducible: time-split + label-shuffle sanity + `py -m src.run` → `reports/metrics.json`

## 🔗 Featured Projects
- **[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR benchmark with sequential modeling (`time-split`, `label-shuffle`, `reports/metrics.json`)
- **[ctr-api](https://github.com/yoonjihyung2023/ctr-api)** — FastAPI + Docker serving demo (`/health`, `/model-info`, `/predict`)

## ✅ What I do
- Leakage-safe offline evaluation with **time-based split** and **label-shuffle sanity**
- End-to-end pipeline: **train → eval → `reports/metrics.json`**
- ML serving demo with **FastAPI + Docker**

## ▶️ Quick run
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

## Stack
Python · PyTorch · FastAPI · Docker · SQL · GitHub Actions

## Open to
Ads/RecSys ML Engineer roles (CTR / Ranking / Sequential Modeling / Serving)

## Contact
- ✉️ yoonjihyung22@yonsei.ac.kr
- [Kaggle Notebook](https://www.kaggle.com/code/yoonjihyung/notebook260213)
