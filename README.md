# 👋 Jihyung Yoon (윤지형)

Ads/RecSys ML Engineer — **CTR prediction + Sequential user modeling**  
Leakage-safe evaluation: **time-based split** + **label-shuffle sanity**  
Reproducible pipeline: runs end-to-end and outputs **`reports/metrics.json`**  
Proof: **Kaggle AUC 0.72659 / LogLoss 0.40009**  
Open to roles: Ads/RecSys ML Engineer (CTR / Ranking / Sequential Modeling)  

## ⭐ Proof (Pinned Project)
**[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR + sequential modeling (time-split, label-shuffle, reproducible `metrics.json`)

- ✅ Kaggle full run (2M rows, Tesla T4): **Test AUC 0.72659 / LogLoss 0.40009**
- ✅ Leakage sanity (label-shuffle): **Test AUC 0.53265** (near-random → OK)
- ▶️ Quick run: creates **`reports/metrics.json`** + runs label-shuffle sanity check

> See: Repo README → Quickstart → `reports/metrics.json` → label-shuffle sanity

### Quick run (local)
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

## Tech
Python · PyTorch · SQL · Docker · GitHub Actions

## Interests
- CTR / Ranking
- Sequential modeling
- Online serving (API / Docker)

## Contact
- ✉️ Email: yoonjihyung22@yonsei.ac.kr
