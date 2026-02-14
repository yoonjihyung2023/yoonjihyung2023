# 👋 Jihyung Yoon (윤지형)

**EN**: Ads/RecSys ML Engineer focused on CTR prediction + sequential user modeling.  
Leakage-safe evaluation (**time-based split**, **label-shuffle sanity check**) + reproducible run (creates `reports/metrics.json`).

**KR**: CTR(클릭) 예측 + 사용자 행동 시퀀스(Sequential) 모델링을 합니다.  
**시간 기반 split(미래 금지)** + **라벨 셔플 검증(AUC ≈ 0.50)** 으로 누수 없이 재현 가능한 실험(`reports/metrics.json`)을 만듭니다.

## ⭐ Pinned Project
**[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe CTR + sequential modeling (time-split, label-shuffle, reproducible `metrics.json`)

- ✅ **Kaggle full run (2M rows, Tesla T4):** **Test AUC 0.72659 / LogLoss 0.40009**
- ✅ **Leakage sanity (label-shuffle, train labels only):** **Test AUC 0.53265** (near-random → OK)
- 🧪 **Local demo: weekly experiment loop (SEQ_LEN ablation + metrics.json + label-shuffle sanity)**
- 📌 Run instructions + `reports/metrics.json` snapshot are in the repo README.
- ▶️ Quick run: creates `reports/metrics.json` + label-shuffle sanity (AUC ≈ 0.50) ✅

### Local demo (structure + leakage checks only)
```powershell
py -m src.run
Get-Content .\reports\metrics.json
```

## Tech
Python · PyTorch · SQL · Docker · GitHub Actions

## Contact
- 🔗 GitHub: https://github.com/yoonjihyung2023
- ✉️ Email: yoonjihyung22@yonsei.ac.kr
