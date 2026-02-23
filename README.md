# 👋 Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer — **CTR prediction + Sequential user modeling**  
**Proof:** Kaggle (Avazu CTR, 2M, Tesla T4) — **Test AUC 0.72659 / LogLoss 0.40009**  
**Repro:** `py -m src.run` → `reports/metrics.json` (time-based split + label-shuffle sanity)

🔗 **Pinned**
- **[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR + seq modeling (time-split, label-shuffle, reproducible metrics)
- **[ctr-api](https://github.com/yoonjihyung2023/ctr-api)** — FastAPI/Docker serving demo (`/health`, `/model-info`, `/predict`)

## ✅ What I do
- Leakage-safe offline evaluation (**time-based split**) + sanity check (**label-shuffle AUC ≈ 0.53 (OK)**)
- End-to-end pipeline: **train → eval → `reports/metrics.json`**
- Serving-ready demo with **FastAPI + Docker**

## ▶️ Quick run (local)
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
