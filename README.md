![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Hyojoon%20Kim&fontSize=50&fontAlignY=40&desc=Math%20%7C%20AI%20%7C%20Data%20Science&descAlignY=60&animation=twinkling)
# Hi, I'm Hyojoon Kim 👋

🎓 Mathematics Major · 💻 AI & Data Science Enthusiast · 🏆 Competition-driven Learner

---

## 🎓 Education & Bootcamp
- **B.S. Intensive Major in Mathematics**
- **SSAFY 13th**, Samsung Software/AI Academy for Youth

---

## 💻 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white)

---

## 🏆 Competitions & Achievements

<details>
<summary>📊 13th MOTIE Public Data Utilization Idea Contest — <b>Grand Prize (Minister of Trade, Industry and Energy Award)</b></summary>

- [Competition Link](https://datacontest.kr/)  
- **Role:** Team Leader  
- **Project:** Correction of weather forecast errors caused by the distance between prediction and observation points  
- **Goal:** Improve day-ahead (24-hour) weather prediction accuracy for industrial sites (solar power, gas turbines), enabling better operational safety and combustion stability  
- **Model:** Ensemble of **XGBoost** (capturing structured patterns via GBDT) + **MLP** (capturing nonlinear & latent patterns)  
- **Achievement:** **Grand Prize (산업통상자원부 장관상)** for excellence in data utilization and industrial impact  
</details>

<details>
<summary>💳 SSAFY Big Data Project — <b>Excellence Award (Samsung Electronics Co., Ltd.)</b></summary>

- **Project:** FinCoach - AI-powered financial coaching service (Credit card delinquency prediction & spending pattern improvement recommendation service based on user MyData)
- **Role:** DA & DE
- **Duration:** 2025.08 ~ 2025.10  | Team of 6 (FE 2, BE 2, Data 2)

**Key Achievements:**
- **Realistic MyData generation pipeline (DE):** Combined AI HUB financial synthetic data + Statistics Korea household survey data, reflecting age-specific spending patterns with individual preference-based diversity using the principle "individuals behave uniquely, groups follow statistics"
- **Credit card delinquency prediction model (ML):** HistGradientBoostingClassifier-based model with **46 engineered features** (13 personal info + 33 monthly derived variables including early/mid/late-month spending ratios, credit/debit ratios, 7 major category amounts/ratios, average transaction size, weekend/night spending ratios, HHI, entropy, 3-month rolling, EOM prediction, etc.)
- **Spending habit improvement recommendation system:** Hybrid CF + CBF approach using cosine similarity to extract top 5% similar users, analyzing 4 comparative perspectives: (1) current month vs similar users (2) 3-month average vs similar users (3) current month vs last month (4) current month vs personal 3-month average
- **FastAPI-based prediction/recommendation API:** Developed endpoints for delinquency prediction and spending comparison recommendations with real-time MySQL integration

**Tech Stack:** Python, scikit-learn, pandas, NumPy, FastAPI, pydantic, MySQL

**Acheivement:** **Excellence Award (우수상)** from Samsung Electronics
</details>

<details>
<summary>🌦 KMA 2025 Weather Data Contest — <b>Finalist, Honorable Mention</b></summary>

- [Competition Link](https://bd.kma.go.kr/contest/main.do)  
- **Project:** Predicted subway congestion levels using time-series weather and observational data  
- **Reasoning:** Dataset had numerous categorical variables, outliers, and missing values → CatBoost was more effective than specialized time-series models in this case  
- **Model:** **CatBoost** (robust for categorical features, missing values, and outliers)  
- **Achievement:** **Finalist & Honorable Mention**  
</details>

<details>
<summary>🚧 2025 SSAFY AI Challenge (Kaggle, pothole detection) — <b>8th place (Top 3%)</b></summary>

- [Competition Link](https://www.kaggle.com/c/pothole-detection-challenge)  
- **Role:** Team Leader  
- **Project:** Developed an object detection model to identify potholes using real-world road images  
- **Model:** **YOLOv8**  
- **Achievement:** **8th place (Top 3%)**  
</details>

<details>
<summary>🖱️ Toss NEXT ML CHALLENGE (Dacon, CTR Prediction) — <b>Top 7.7%</b></summary>

- [Competition Link](https://dacon.io/competitions/official/236575/overview/description)
- **Role:** Team Leader
- **Project:** Advertisement Click-Through Rate (CTR) Prediction Model
- **Goal:** Predict user ad click probability using user demographics, ad attributes, domain features, and behavioral sequences
- **Model Architecture:** Ensemble of two approaches
  - **Model 1:** CatBoost (base) + Transformer (sequence processing)
  - **Model 2:** xDeepFM (base) + Attention mechanism (sequence processing)
- **Key Features:**
  - Sequence modeling with Transformer encoder for user behavior patterns
  - Deep feature interaction modeling with xDeepFM's Compressed Interaction Network (CIN)
  - Attention-based pooling for sequence aggregation
  - Hybrid ensemble combining tree-based and deep learning approaches
- **Achievement:** **Top 7.7%** ranking in private leaderboard through effective fusion of tabular and sequential modeling
- **Tech Stack:** Python, PyTorch, CatBoost, pandas, NumPy, scikit-learn

</details>

<details>
<summary>🚗 Hecto AI Challenge (Dacon, 2025 Hecto Recruitment AI Competition) — <b>Top 13%</b></summary>

- [Competition Link](https://dacon.io/competitions/official/236493/overview/description)  
- **Role:** Team Leader  
- **Project:** Classified used car types through image-based computer vision modeling  
- **Model:** Ensemble of **Swin Transformer** and **ConvNeXt**  
- **Achievement:** **Top 13%**  
</details>

<details>
<summary>🏎 2025 SUMMER SSAFY RACE Basic Map — <b>2nd place</b></summary>

- **Role:** Team Leader  
- **Project:** Designed obstacle-avoidance and high-speed driving logic in a virtual autonomous driving environment  
- **Achievement:** **2nd place**  
</details>

<details>
<summary>💡 2025 Shinhan Hackathon with SSAFY — <b>Final Round</b></summary>

- **Project:** Built a 6-month quest-based savings product where users earn EXP by completing Life/Growth/Surprise quests, level up for preferential interest rates, and contribute bonus interest to school-level donation pools  
- **My Role:**  
  - Developed and maintained the recommendation system end-to-end (hybrid CF+CBF with cold-start fallback, FastAPI + SQLAlchemy, interaction logging)  
  - Contributed to the app’s front-end by handling design-oriented tasks in React Native (screens, components, styling)  
- **Achievement:** **Final Round (On-site)**  
</details>

<details>
<summary>📐 2023 JBNU Science Research Fair — <b>Outstanding Presentation Award</b></summary>

- **Study:** Endomorphism of the 4-torsion group of elliptic curves  
- **Context:** Participated as an undergraduate in a graduate-level academic conference  
- **Achievement:** **Outstanding Presentation Award (우수발표상)**
</details>


---

## 📈 Algorithm Practice
[![Solved.ac 프로필](http://mazassumnida.wtf/api/mini/generate_badge?boj=jkim720)](https://solved.ac/jkim720)  
🔗 [Algorithm Repository](https://github.com/hjkim720/algorithm)

---

## 🌍 Languages
- **English** — Fluent  
  - **TOEIC 990** (Acquired 2023.02)  
  - **OPIC AL** (Acquired 2025.09)  
  - 1.5 year study abroad & living experience in **San Diego, CA**

- **Korean** — Native  

- **Spanish** — Beginner (*aprendiendo*)

---

## 🔥 Passions & Interests
- Competing in AI and data science challenges 🚀  
- Applying mathematical thinking to model optimization  
- Continuous learning & collaborative growth  

---

## 📫 Contact
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:joonbutjuly@gmail.com)
💡 Open to collaboration on **AI/ML competitions** and **data challenges** — feel free to reach out!
