# 👋 Hi, I’m Jihyung Yoon (윤지형)

**Ads/RecSys ML Engineer** focused on CTR prediction + sequential user modeling.  
**Leakage-safe, reproducible pipeline** (data → time-split → train → eval → report).

> Goal: Time-based split (no future data) + reproducible metrics report.

## ⭐ Pinned Project
**[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Avazu CTR prediction with sequential modeling (SASRec/BERT4Rec-style)  
- ✅ **Kaggle full run (2M rows, Tesla T4):** **Test AUC 0.72659 / LogLoss 0.40009**  
- ✅ **Leakage sanity (label-shuffle, train labels only):** **Test AUC 0.53265** (≈ random → OK)  
- 📌 Run instructions + `reports/metrics.json` snapshot are in the repo README.

### Local demo (structure + leakage checks only)
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

- Output: `reports/metrics.json` *(demo numbers may differ from Kaggle full run)*
- Sanity check: label-shuffle → AUC ≈ 0.50 (if higher, suspect leakage)

## Tech
Python · PyTorch · SQL · Docker · GitHub Actions

## Contact
GitHub: https://github.com/yoonjihyung2023
