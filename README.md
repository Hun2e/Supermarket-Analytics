# 🛒 Supermarket Analytics

### 데이터 기반 매출 증대 및 고객 이탈 개선 프로젝트

---

## 📌 프로젝트 개요

본 프로젝트는 **대형마트 고객 구매 데이터를 분석하여**
매출 감소 및 고객 이탈의 원인을 정의하고,  
**데이터 기반 개선 전략을 제안**하는 빅데이터 분석 프로젝트입니다.

POSCO Academy Big Data Project의 일환으로 진행되었으며,  
기존의 경험·직관 중심 운영 방식에서 벗어나
**고객 행동을 수치로 설명하고 실행 가능한 전략으로 연결**하는 것을 목표로 했습니다.

* **프로젝트 유형**: 팀 프로젝트 (6명)
* **주제**: 대형마트 매출 증대 및 고객 이탈 개선

---

## 🙋‍♂️ 담당 역할

본 레포지토리는 프로젝트 전체 중
**데이터 전처리(정제), EDA, 연관분석 및 시계열 분석 파트**를 정리한 저장소입니다.

제가 담당한 주요 역할은 다음과 같습니다.

* 고객·상품·거래 데이터 **전처리(결측치·이상치 제거 및 정제)**
* EDA를 통한 고객 및 상품 구매 패턴 분석
* **연관분석**을 통한 상품 조합 및 구매 관계 도출
* **시계열 분석(ARIMA)**을 활용한 주요 상품 수요 예측
* 분석 결과를 **매출 증대 및 고객 이탈 개선 전략으로 정리**

---

## 🧩 데이터 분석 흐름

원본 데이터 수집
→ 데이터 전처리 (결측치·이상치 제거 및 정제)
→ EDA(고객·상품·시간·지점별 구매 패턴 분석)
→ 연관분석을 통한 상품 구매 관계 파악
→ 시계열 분석 기반 수요 예측
→ 매출 증대 및 이탈 개선 전략 도출

단순 지표 나열이 아닌,
**“왜 이런 결과가 나왔는지”를 설명하는 흐름으로 분석을 설계**했습니다.

---

## 📂 레포지토리 구조

```text
Supermarket-Analytics/
│
├── README.md
│
├── data/
│   └── sample_preprocessed.csv
│
├── notebooks/
│   ├── 01_preprocessing_missing_outlier.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_eda_customer_behavior.ipynb
│   ├── 04_churn_prediction_modeling.ipynb
│   ├── 05_product_association_analysis.ipynb
│   └── 06_time_series_arima.ipynb
│
├── docs/
│   └── presentation.pdf
│
└── .gitignore

```

---

## 🛠 사용 기술

* **Language**: Python
* **Data Analysis**: pandas, numpy
* **Modeling**

  * Association Analysis (Apriori)
  * Time Series Analysis (ARIMA)
  * Classification (Random Forest)
* **Visualization**: matplotlib, seaborn

※ 본 레포지토리에는 **원본 데이터 및 개인정보가 포함되어 있지 않습니다.**

---

## 📈 핵심 분석 인사이트

* 고객 구매 데이터 EDA를 통해 **주요 고객층과 핵심 구매 패턴 식별**
* 연관분석 결과를 활용한 **묶음 상품 및 교차 판매 가능성 확인**
* 시계열 분석을 통해 **주요 상품의 수요 변동 및 계절성 파악**
* 구매 패턴 기반 특징량을 활용해 **이탈 가능 고객을 사전에 식별할 수 있는 근거 확보**

---

## 💡 제안 전략

* 고객 구매 패턴을 반영한 **상품 묶음 프로모션 기획**
* 수요 예측 결과를 활용한 **재고 및 발주 전략 개선**
* 이탈 가능 고객 대상 **선제적 혜택 및 마케팅 전략 제안**

---

## 📎 참고 자료

* 프로젝트 발표 자료: `docs/presentation.pdf`

---

## ✨ 배운 점

* 데이터 분석에서 **전처리와 EDA가 전체 분석 품질을 결정**함을 체감
* 분석 결과를 단순 수치가 아닌 **비즈니스 문제 해결 관점으로 해석하는 경험**
* 여러 분석 기법을 목적에 맞게 선택하고 **하나의 스토리로 연결하는 역량 강화
