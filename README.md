# Supermarket-Analytics

> 대형마트 고객·구매 데이터를 분석해 **매출 증대와 고객 이탈 개선 전략**을 제안한 프로젝트

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

<sub>POSCO Academy 빅데이터 프로젝트 · 팀 6인 · 발표회 4팀 중 1위</sub>

<br/>

## 한눈에 보기

| 항목 | 내용 |
|---|---|
| 문제 | 경험·직관에 의존한 운영으로 매출 감소와 고객 이탈 원인을 설명하지 못함 |
| 접근 | 전처리 → EDA → 연관분석 → 시계열 분석 → 전략 제안 |
| 내 역할 | 데이터 전처리, EDA, 연관분석(Apriori), 시계열 분석(ARIMA) |
| 결과 | 묶음 프로모션 · 재고 발주 · 이탈 고객 선제 혜택 전략 제안, 발표회 1위 |

<br/>

## 분석 내용

- **전처리** — 결측치·이상치를 정리하고, 주소를 지역 단위로 묶고, RFM 등 파생 변수를 만들었습니다.
- **EDA** — 고객층·시간대·지점별 구매 패턴을 비교해 주요 고객층과 핵심 구매 패턴을 찾았습니다.
- **연관분석** — Apriori로 함께 사는 상품 조합을 찾아 교차 판매 후보를 뽑았습니다.
- **시계열 분석** — ARIMA로 주요 상품 수요의 변동과 계절성을 봤습니다.

<br/>

## 노트북

| 노트북 | 내용 |
|---|---|
| [01 전처리](notebooks/01_preprocessing_missing_outlier.ipynb) | 결측치·이상치 처리 |
| [02 파생 변수](notebooks/02_feature_engineering.ipynb) | RFM 등 특징량 생성 |
| [03 EDA](notebooks/03_eda_customer_behavior.ipynb) | 고객 구매 행동 분석 |
| [04 이탈 예측](notebooks/04_churn_prediction_modeling.ipynb) | 분류 모델 (Random Forest) |
| [05 연관분석](notebooks/05_product_association_analysis.ipynb) | Apriori 상품 조합 |
| [06 시계열](notebooks/06_time_series_arima.ipynb) | ARIMA 수요 분석 |

발표 자료는 [`docs/presentation.pdf`](docs/presentation.pdf)에 있습니다.

> 원본 데이터는 저장소에 넣지 않았습니다. 노트북에는 집계 차트만 남기고, 고객 단위 행이 보이는 출력은 지웠습니다.
