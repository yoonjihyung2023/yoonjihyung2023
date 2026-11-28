# Jihyung Yoon (윤지형)

**Applied Machine Learning | Recommendation Systems | Ads AI**

CTR Prediction · Sequential Recommendation · Ranking Evaluation · ML Serving

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/%EC%A7%80%ED%98%95-%EC%9C%A4-878902372/)

## About Me

My research at Yonsei University focused on sequential recommendation and click-through rate (CTR) prediction.

I am interested in building and evaluating machine learning models for recommendation systems, advertising, and personalized ranking.

My portfolio covers offline experimentation, baseline comparison, ranking metrics, and containerized inference API development.

- Two first-author research publications
- CTR benchmark on 2 million Avazu advertising impressions
- PyTorch-based sequential modeling
- Chronological evaluation and data leakage prevention
- FastAPI and Docker-based serving demonstrations

## Featured Projects

| Project | Description | Technologies |
|---|---|---|
| [CTR & Sequential Recommendation](https://github.com/yoonjihyung2023/ctr-seqrec-avazu) | Chronological CTR benchmark comparing three models on 2M impressions | PyTorch, LightGBM, scikit-learn |
| [CTR Inference API](https://github.com/yoonjihyung2023/ctr-api) | Containerized inference API demonstration with a stub model | FastAPI, Docker, GitHub Actions |
| [Ranking Evaluation Toolkit](https://github.com/yoonjihyung2023/ranking-eval-toolkit) | Offline evaluation utilities for CTR and recommendation models | Python, Ranking Metrics |

## Latest Benchmark

**Avazu CTR Prediction — November 28, 2026**

Compared three CTR prediction models using the first 2,000,000 Avazu advertising impressions and a chronological train/validation/test split.

| Model | ROC AUC ↑ | LogLoss ↓ |
|---|---:|---:|
| Logistic Regression | 0.740531 | 0.396285 |
| LightGBM | 0.720676 | 0.402776 |
| **SASRec-DIN-inspired** | **0.742281** | **0.392768** |

### Key Findings

- **0.89% lower LogLoss** than Logistic Regression.
- **2.48% lower LogLoss** than LightGBM.
- Best observed AUC: **0.742281**.
- Best observed LogLoss: **0.392768**.

### Experimental Design

- 2,000,000 advertising impressions
- 1,435,205 training samples
- 416,555 validation samples
- 148,240 held-out test samples
- Chronological data splitting
- Train-only categorical vocabulary
- Strictly earlier-hour behavioral histories
- Validation-based checkpoint selection
- Evaluation including cold-start events
- NVIDIA Tesla T4 GPU
- Random seed: 42

[View Project and Experimental Results](https://github.com/yoonjihyung2023/ctr-seqrec-avazu) | [Benchmark Code and Results](https://github.com/yoonjihyung2023/ctr-seqrec-avazu/blob/main/github_ctr_update.zip)

**Limitations:** This is a single-seed experiment over a short chronological window. Device IDs are behavioral proxies rather than verified user identities. The sequential model uses additional historical features. Statistical significance and multi-day generalization remain unverified.

## Research Publications

### IEEE Access — 2023

**Evolution of Deep Learning-Based Sequential Recommender Systems**

First Author

[Read Paper](https://doi.org/10.1109/ACCESS.2023.3281981)

### Journal of Internet Computing and Services — 2022

**A Comparison Study of RNN, CNN, and GAN Models in Sequential Recommendation**

First Author · KCI-indexed Journal

[Read Paper](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002872765)

## Technical Skills

### Machine Learning & Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-249B45?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### ML Serving & Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Areas of Focus

- Click-Through Rate Prediction
- Sequential Recommender Systems
- Transformer-based Modeling
- Attention Mechanisms
- Ranking and Personalization
- Offline Model Evaluation
- ROC AUC, LogLoss, Precision@K, Recall@K, NDCG@K
- ML Inference APIs

## Career Interests

- Machine Learning Engineer
- Recommendation System Engineer
- Ads ML Engineer
- Applied AI Engineer
- Data Scientist

## Contact

- [LinkedIn](https://www.linkedin.com/in/%EC%A7%80%ED%98%95-%EC%9C%A4-878902372/)
- [GitHub](https://github.com/yoonjihyung2023)
