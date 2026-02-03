## 대표 프로젝트 (바로 보기)
**[ctr-seqrec-avazu](https://github.com/yoonjihyung2023/ctr-seqrec-avazu)** — Leakage-safe time-split CTR prediction (SASRec/BERT4Rec)

# 👋 Hi, I’m Jihyung Yoon (윤지형)

## EN (2 lines)
Ads/RecSys ML Engineer focused on CTR prediction + sequential user modeling.  
Reproducible pipeline (data → time-split → train → eval → report) with leakage checks.

## KR (2 lines)
CTR(클릭) 예측과 사용자 행동 시퀀스(Sequential) 모델링을 하는 ML 엔지니어입니다.  
시간(Time) 기반 분할로 **미래 데이터(미래 클릭) 누수 없이** 재현 가능한 실험 파이프라인을 만듭니다.

> Goal: Time-based split (no future data) + reproducible metrics report.

## ⭐ Proof (바로 실행되는 증거)
> Run inside the repo root folder (where `README.md` exists).

**한 줄 실행 → 결과 파일 생성**
```powershell
py -m src.run; Get-Content .\reports\metrics.json
```
- Output: `reports/metrics.json`
- Example output:
```json
{
  "test_auc": 0.5,
  "test_logloss": 0.9339,
  "label_shuffle_auc": 0.5
}
```
- Sanity check: label shuffle(정답 섞기)하면 **AUC ≈ 0.50**이어야 정상  
  (정답을 섞었는데도 점수가 높으면 누수/치팅 의심)

## Tech
Python · PyTorch · SQL · Docker · GitHub Actions

## Contact
- GitHub: **[yoonjihyung2023](https://github.com/yoonjihyung2023)**
