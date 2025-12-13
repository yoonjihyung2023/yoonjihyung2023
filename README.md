# Yoon Jihyung (윤지형)
Data Scientist / AI Engineer  
CTR 예측·추천(Sequential RecSys) 문제에서 **데이터 파이프라인 → 모델링 → 실험/검증 → 재현성**까지 한 번에 정리하는 것을 지향합니다.

## 🔎 What I do
- **CTR Prediction / RecSys**: 사용자 행동(Sequence)을 반영한 예측 모델링
- **Experiment & Reproducibility**: 누수 방지 split, seed 반복, 실험 로그/리포트 자동화
- **Model Optimization**: 불균형 대응, 하이퍼파라미터 탐색(Optuna), 앙상블/개선 실험

## 🧠 Thesis
**석사 논문: 순차적 추천 모델의 성능 향상 연구: CTR 예측**  
- Dataset: Avazu CTR (대규모 범주형 특성, 고카디널리티 처리 중심)
- Models: BERT4Rec / SASRec 기반 순차 모델 + (선택) 하이브리드 구성
- Metrics: AUC-ROC, LogLoss  
- Focus: 인코딩/불균형 처리/튜닝을 포함한 실험 파이프라인 구축과 성능 개선

## 🚀 Featured Projects (Pinned)
> 아래 3개를 만들어서 GitHub에서 "Pin"으로 고정하면 포트폴리오가 완성됩니다.

1) **ctr-seqrec-avazu**  
논문 기반 메인 구현: 전처리(인코딩) + 학습/평가 + 튜닝 + 리포트  
- Repo: https://github.com/yoonjihyung2023/ctr-seqrec-avazu

2) **recsys-experiments-playbook**  
누수 방지 검증(time/group split), train-only 리샘플링, ablation 템플릿  
- Repo: https://github.com/yoonjihyung2023/recsys-experiments-playbook

3) **ctr-serving-demo**  
FastAPI + Docker 로 `/predict` API 서빙 데모(+ CI 선택)  
- Repo: https://github.com/yoonjihyung2023/ctr-serving-demo

## 🧰 Tech Stack
- **Python**: pandas, numpy, scikit-learn
- **Deep Learning**: PyTorch (or TensorFlow), Transformer 기반 모델링
- **Experiment**: Optuna, reproducible configs
- **Engineering**: Git, (optional) Docker, FastAPI, GitHub Actions
- **Data**: SQL (basic/analysis)

## 📌 Interests
CTR/RecSys, sequential modeling, ranking & calibration, leakage-safe evaluation, MLOps basics

## 📫 Contact
- Email: [your-email]
- LinkedIn: [your-link]

