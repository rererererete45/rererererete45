# 안녕하세요, 오재원입니다

**공간·도시 데이터 분석 · Researcher**

공공데이터와 공간정보로 수요를 예측하고 정책 판단의 근거를 만드는 분석을 해 왔습니다.
지금은 연구원에서 철도 인프라의 경제성(NPV·B/C)을 분석하고 있으며, 추천시스템과 RAG를 공부하며 데이터 사이언스로 범위를 넓히고 있습니다.

📫 [Portfolio](https://rererererete45.github.io/rerererete45.github.io/) · [Email](mailto:yxxyy159@gmail.com)

---

## 🚀 Projects

> 프로젝트별 데이터·방법·결과 전체는 [포트폴리오](https://rererererete45.github.io/rerererete45.github.io/#projects)에 정리되어 있습니다.

### 지방소멸 영향 요인 분석: 회귀 vs 머신러닝 · *개인 연구*
전국 229개 시군구의 37개 변수로 소멸위험지수에 영향을 주는 요인을 찾고, 세 가지 방법의 결과를 비교했습니다.

- 다중회귀 **R² 0.849** (VIF 검증으로 37개 → 8개 변수) · 단계적 회귀 **R² 0.909**
- GBC·Random Forest·XGBoost Soft Voting 앙상블 **F1 0.892**
- 세 방법 모두에서 주거·고용·교육 변수가 유의했고, 빈집·노후주택 비율이 높을수록 소멸 위험이 커졌습니다.

`Python` `scikit-learn` `XGBoost`

### 이륜차 사고 위험구간 분석 · *유성구청 인턴*
경찰청 사고 이력을 교차로에 공간결합해 위험지수(ARI)를 산정하고, 상위 2.5% 교차로를 고위험 구간으로 분류했습니다.

- 유성온천역 인근 **1.9km 구간** 도출: 교차로의 1.67%에 사고의 **14.33%**가 집중
- 요일·시간대·연령·위반 유형을 비교해 자치구가 실행할 수 있는 대응 전략으로 정리

<img src="https://rererererete45.github.io/rerererete45.github.io/assets/projects/motorcycle-hotspot-route.png" width="420" alt="이륜차 사고 다발 구간 지도">

`QGIS` `Python` `공간결합`

### 초등 돌봄 수요예측 및 입지 분석 · *유성구청 인턴*
행정동별 초등학생 수를 예측하고, 100m 격자 단위로 돌봄센터 우선 입지를 산출했습니다.

- 코호트 요인법과 Prophet으로 학생 수 예측, 신규 아파트 단지는 랜덤포레스트 회귀로 추정
- 아동 수·주거밀도·학교 접근성·유사시설 접근성에 FGI·AHP 가중치를 적용해 격자별 입지 점수 산출
- 지역 데이터 구축·적용과 결과 해석 담당

`Prophet` `Random Forest` `GIS 입지분석`

### 국공립어린이집 수요 분석 · *유성구청 인턴*
신축 공공주택 입주 전·후 시나리오로 집계구별 시설확충최적화지수를 비교했습니다.

- 대상 집계구 지수 **28점 → 44점**, 상위 68.4% → **상위 23.7%**로 상승
- 입주 시점에 맞춘 국공립 어린이집 확충 사전 검토를 제안

`QGIS` `지수 산정` `시나리오 비교`

### 도시 간 관계 네트워크 분석 · *학부연구생*
.kr 도메인 웹사이트 간 하이퍼링크를 직접 크롤링하고, 교통·항공 데이터와 함께 시군구 단위 네트워크로 구축해 중심성을 분석했습니다.

- 국가 R&D 사업 기반 연구 협력 네트워크(2015·2023)로 확장해 학술대회에서 발표

`Python` `웹 크롤링` `Network Analysis` `geopandas`

### 개인 도구 · 학습 기록
- [**한글 스타일 문서 자동화**](https://github.com/rererererete45/hwp-style-automation) — 한글 `.sty` 스타일을 분석해 문서에 자동 적용하는 프롬프트·매크로 가이드
- [**평양냉면 맛집 지도**](https://rererererete45.github.io/rerererete45.github.io/naengmyeon-map.html) — 전국 평양냉면 식당을 모은 모바일 대응 웹 지도
- **나라장터 입찰공고 수집** — Python·SQLite로 공고를 저장하고 새 공고를 텔레그램으로 알림
- **연도별 항공사진 수집** — 국토지리정보원 API로 특정 좌표의 연도별 항공사진을 모아 PDF로 출력
- [**ds-study**](https://github.com/rererererete45/ds-study) · [**certification-notes**](https://github.com/rererererete45/certification-notes) — SQL·통계·머신러닝 학습 노트

---

## 🛠 Tech Stack

<table>
<tr>
<th>높음</th><th>보통</th><th>낮음 (학습 중)</th><th>학습 예정</th>
</tr>
<tr valign="top">
<td><img src="https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white" alt="QGIS"><br><img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"><br><img src="https://img.shields.io/badge/Excel-217346?style=flat" alt="Excel"></td>
<td><img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" alt="pandas"><br><img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="scikit-learn"><br><img src="https://img.shields.io/badge/SPSS-052FAD?style=flat" alt="SPSS"><br><img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"><br><img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite"></td>
<td><img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white" alt="SQL"><br><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"><br><img src="https://img.shields.io/badge/PyQGIS-589632?style=flat&logo=qgis&logoColor=white" alt="PyQGIS"><br><img src="https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white" alt="Leaflet"><br><img src="https://img.shields.io/badge/AutoCAD-E51050?style=flat" alt="AutoCAD"></td>
<td><sub>2026.12 ~</sub><br><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face"> <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat" alt="FAISS"> <img src="https://img.shields.io/badge/RAG-1C3C3C?style=flat" alt="RAG"> <img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" alt="Ollama"><br><sub>2027.01 ~</sub><br><img src="https://img.shields.io/badge/통계-6C757D?style=flat" alt="통계"> <img src="https://img.shields.io/badge/하이브리드_검색-1C3C3C?style=flat" alt="하이브리드 검색"><br><sub>2027.02 ~</sub><br><img src="https://img.shields.io/badge/추천시스템_(item--kNN_·_SASRec)-8E44AD?style=flat" alt="추천시스템 (item-kNN · SASRec)"><br><sub>2027.06 ~</sub><br><img src="https://img.shields.io/badge/알고리즘_·_코딩테스트-6C757D?style=flat" alt="알고리즘 · 코딩테스트"> <img src="https://img.shields.io/badge/선형대수_·_확률-6C757D?style=flat" alt="선형대수 · 확률"><br><sub>2027.07 ~</sub><br><img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white" alt="PySpark"> <img src="https://img.shields.io/badge/GRU4Rec-8E44AD?style=flat" alt="GRU4Rec"> <img src="https://img.shields.io/badge/A/B_테스트-2C7BE5?style=flat" alt="A/B 테스트"> <img src="https://img.shields.io/badge/인과추론-2C7BE5?style=flat" alt="인과추론"><br><sub>2027.08 ~</sub><br><img src="https://img.shields.io/badge/리랭커_·_LLM_평가-1C3C3C?style=flat" alt="리랭커 · LLM 평가"> <img src="https://img.shields.io/badge/오프라인_정책_평가_(Open_Bandit)-2C7BE5?style=flat" alt="오프라인 정책 평가 (Open Bandit)"></td>
</tr>
</table>

---

## 💼 Experience
- **한국종합경제연구원 학술연구1팀 연구원** (2025.10 ~ 현재)
  - 노후전동차 경제성평가, 노후 철도시설 개량투자 효과분석 연구용역에서 대안별 NPV·B/C·LCC 산정과 민감도 분석 수행
- **유성구청 공공빅데이터 청년인턴** (2025.02 ~ 2025.09)
  - 교통·돌봄 행정 데이터를 GIS와 수요예측 모델로 분석해 정책 제안
- **국립한밭대학교 학부연구생** (2024.01 ~ 2025.01)
  - 「빅데이터 기반 인공지능 도시계획 기술 개발」 (국토교통과학기술진흥원) · 정보통신 지표 설계, 지역균형발전 점수 산출
  - 「상호관련성에 기반한 도시의 네트워크와 영향력에 관한 예측 연구」 (한국연구재단) · 관계 데이터 구축, 중심성 분석

---

## 📝 Presentation
- **도시 간 연구 협력 네트워크의 공간 구조 분석: 2015년과 2023년 국가 R&D 사업을 중심으로**
  이지석 · **오재원** · 백효진, 대한국토·도시계획학회 2025 춘계학술대회

---

## 🎓 Education · Certifications
- **국립한밭대학교 도시공학과 학사** (2018.03 ~ 2025.02)
- **빅데이터분석기사** (2024.12) · **도시계획기사** (2024.09) · **컴퓨터활용능력 1급** (2023.12)
