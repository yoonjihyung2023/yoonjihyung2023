# 👋 Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer — **CTR prediction + Sequential user modeling**  
✅ **Proof:** Kaggle (Avazu, 2M rows, Tesla T4) — **Test AUC 0.72659 / LogLoss 0.40009**  
🎯 Focus: leakage-safe offline eval + production-ready pipeline (train → eval → metrics.json)

🔗 **Pinned repos**
- **[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR + sequential modeling (time-split, label-shuffle, reproducible `metrics.json`)
- **[ctr-api](https://github.com/yoonjihyung2023/ctr-api)** — FastAPI/Docker serving demo (`/health`, `/model-info`, `/predict`)

Leakage-safe + reproducible: **time-based split** + **label-shuffle sanity** → outputs **`reports/metrics.json`**  
Open to: Ads/RecSys ML Engineer (CTR / Ranking / Seq Modeling / Serving)

## 📌 Details (Repro & Sanity)
- ✅ Kaggle full run (2M rows, Tesla T4): **Test AUC 0.72659 / LogLoss 0.40009**
- ✅ Leakage sanity (label-shuffle): **Test AUC 0.53265** (near-random → OK)
- ▶️ Quick run: creates **`reports/metrics.json`** + runs label-shuffle sanity check  
  → See: **[ctr-seqrec-avazu README](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** → Quickstart → `reports/metrics.json`

### Quick run (local)
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

## Stack & Focus
Python · PyTorch · SQL · Docker · GitHub Actions  
CTR / Ranking · Sequential modeling · Online serving (API / Docker)

## Contact
- ✉️ Email: yoonjihyung22@yonsei.ac.kr
