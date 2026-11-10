# 안녕하세요, 오재원입니다

**도시공학 학사 · Researcher (공간·도시 데이터 분석)**

GIS와 Python으로 도시·공간 데이터를 분석해 왔고, 지금은 연구원에서 경제성·타당성 분석을 하고 있습니다.
추천시스템, 인과추론, 사용자 행동 로그 분석 등 데이터 사이언스 영역으로 범위를 넓혀 가는 중입니다.

📫 [Portfolio](https://rererererete45.github.io/rerererete45.github.io/) · [GitHub](https://github.com/rererererete45)

---

## 🎓 Education
- **도시공학 학사** — 국립한밭대학교 (2018.03 ~ 2025.02)

---

## 🛠 Tech Stack

**Language**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Data Analysis / ML**
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SPSS](https://img.shields.io/badge/SPSS-052FAD?style=flat)

**GIS / Spatial**
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat&logo=geopandas&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)

---

## 📝 Publications

1. **도시 간 연구 협력 네트워크의 공간 구조 분석: 2015년과 2023년 국가 R&D 사업을 중심으로** (2025)

   이지석 · **오재원** · 백효진, 2025 대한국토·도시계획학회 춘계 학술대회

---

## 🚀 Projects

> 각 프로젝트의 데이터·방법·결과 전체는 [포트폴리오](https://rererererete45.github.io/rerererete45.github.io/#projects)에 정리되어 있습니다.

### 지방소멸 영향 요인 분석: 다중회귀 vs 머신러닝 · *학부 개인 연구*
전국 229개 시군구(2022년)의 독립변수 37개로 소멸위험지수 영향 요인을 세 가지 방법으로 비교 분석.

- 다중회귀: 상관분석·VIF 검증으로 37개 → 8개 변수 축소, **R² 0.849**
- 단계적 회귀: 전진선택·후진제거 결합 12단계 변수 선택, **R² 0.909**
- 머신러닝: GBC·Random Forest·XGBoost를 RandomizedSearchCV로 튜닝, Soft Voting 앙상블 **F1(weighted) 0.892**

`Python` `scikit-learn` `XGBoost` `다중회귀` · 📎 [방법·결과](https://rererererete45.github.io/rerererete45.github.io/#projects)

### 이륜차 사고 위험구간 분석 · *유성구청 인턴 (2025)*
경찰청 사고 이력과 교차로 위치를 공간결합해 교차로별 위험지수(ARI)를 산정하고 상위 2.5%를 고위험 구간으로 분류.

- 유성온천역 인근 **1.9km 구간** 도출: 교차로 비중 1.67%인 구간에 사고의 **14.33%** 집중 (44.2건/km)
- 요일·시간대·연령·위반 유형별 특성을 비교해 자치구 단독/유관기관 협력 대응 전략으로 정리

<img src="https://rererererete45.github.io/rerererete45.github.io/assets/projects/motorcycle-hotspot-route.png" width="480" alt="이륜차 사고 다발 구간 지도">

`QGIS` `공간결합` `Python` · 📎 [방법·결과](https://rererererete45.github.io/rerererete45.github.io/#projects)

### 초등 돌봄 수요예측 및 입지 분석 · *유성구청 인턴 (2025)*
행정동별 초등학생 수를 예측하고 100m 격자 단위로 돌봄센터 우선 입지를 산출.

- 코호트 요인법 + Prophet 시계열로 초등학생 수 예측
- 아동 수·주거밀도·학교 접근성·유사시설 접근성을 구간화하고 FGI·AHP 가중치를 반영해 격자별 입지 점수 산출
- 신규 아파트 단지는 랜덤포레스트 회귀로 초등학생 수 추정

`Prophet` `Random Forest` `GIS 입지분석` · 📎 [방법·결과](https://rererererete45.github.io/rerererete45.github.io/#projects)

### 장대행복주택 국공립어린이집 수요 분석 · *유성구청 인턴 (2025)*
행정안전부 보육 서비스 빅데이터 분석모델을 적용해 집계구별 시설확충최적화지수를 산출하고 입주 전·후 시나리오를 비교.

- 대상 집계구 지수 **28점(3등급) → 44점(4등급)**, 상위 68.4% → **상위 23.7%**

<img src="https://rererererete45.github.io/rerererete45.github.io/assets/projects/childcare-grade-pre.png" width="360" alt="입주 전 등급 지도"> <img src="https://rererererete45.github.io/rerererete45.github.io/assets/projects/childcare-grade-post.png" width="360" alt="입주 후 등급 지도">

`QGIS` `지수 산정` `시나리오 비교` · 📎 [방법·결과](https://rererererete45.github.io/rerererete45.github.io/#projects)

### 도시 간 관계 네트워크 구축 및 중심성 분석 · *학부연구생 (2024 ~ 2025)*
.kr 도메인 웹사이트 간 하이퍼링크를 직접 크롤링하고 교통·항공 관계 데이터와 함께 시군구 단위 네트워크로 구축, 중심성을 계산해 공간 구조를 분석.

- 국가 R&D 사업 기반 연구 협력 네트워크(2015·2023)로 확장해 **대한국토·도시계획학회 2025 춘계학술대회 발표** (공동저자)

`Python` `웹 크롤링` `Network Analysis` `geopandas` · 📎 [방법·결과](https://rererererete45.github.io/rerererete45.github.io/#projects)

### 데이터 사이언스 스터디 노트 · *진행 중*
SQL부터 통계, A/B 테스트, 인과추론, 머신러닝까지 공부한 내용을 장별로 정리.

`SQL` `Statistics` `Machine Learning` · 📎 [ds-study](https://github.com/rererererete45/ds-study) · [certification-notes](https://github.com/rererererete45/certification-notes)

### 개인 도구
- **평양냉면 맛집 인터랙티브 지도** — 전국 평양냉면 식당 웹 지도, 모바일 대응 · 📎 [지도 열어보기](https://rererererete45.github.io/rerererete45.github.io/naengmyeon-map.html)
- **나라장터 입찰공고 자동 수집** — Python·SQLite로 공고를 수집·저장하고 새 공고를 텔레그램으로 알림
- **연도별 항공사진 수집** — 국토지리정보원 API로 특정 좌표의 연도별 항공사진을 모아 A4 PDF로 출력

---

## 💼 Experience
- **한국종합경제연구원 학술연구1팀 연구원** (2025.10 ~ 현재) · 철도 분야 경제성·타당성 분석(NPV, B/C)
- **유성구청 공공빅데이터 청년인턴** (2025.02 ~ 2025.09) · GIS 분석
- **국립한밭대학교 학부연구생** (2024.01 ~ 2025.01)
  - 「빅데이터 기반 인공지능 도시계획 기술 개발」 (국토교통부 · 국토교통과학기술진흥원)
  - 「상호관련성에 기반한 도시의 네트워크와 영향력에 관한 연구」 (한국연구재단)

---

## 🌱 Certifications
- **빅데이터분석기사**
- **도시계획기사**
- **컴퓨터활용능력 1급**
