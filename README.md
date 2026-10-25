# 🚀 STAC WARS: Hackathon Team Submission (Jugaad.exe)

Welcome to our team submission for the STAC WARS Hackathon! This repository contains complete analytical pipelines, machine learning models, and executive reports for **Problem Statements 2, 3, and 4**.

---

## 📂 Team Submissions Breakdown

### ☀️ Problem Statement 2: Solar Radiation Analysis and Prediction
- **Folder:** [`/PS2_Solar_Radiation`](./PS2_Solar_Radiation)
- **Primary Notebook:** `solar_radiation_analysis.ipynb`
- **Report:** `solar_radiation_report.pdf`
- **Key Findings:**
  - **Diurnal Irradiance:** Solar radiation peaks consistently between 10:00 AM and 2:00 PM, with Hour 12 recording the highest average irradiance (**727.47 W/m²**).
  - **Environmental Correlation:** Temperature shows a strong positive correlation ($r = +0.7350$), while humidity displays an inverse relationship ($r = -0.2262$).
  - **Peak Solar Activity Event:** September 4, 2016 at 12:15:04 PM recorded maximum radiation of **1601.26 W/m²** (6 hours, 7 minutes, 4 seconds post-sunrise).
  - **Machine Learning Model:** Random Forest Regressor achieved **$R^2 = 0.7301$** and **$\text{RMSE} = 137.92\text{ W/m}^2$** using time-aware chronological splits to eliminate target leakage.

---

### 🛰️ Problem Statement 3: [Insert Title of PS3]
- **Folder:** [`/PS3_Astronomy`](./PS3_Astronomy)
- **Report:** `[PS3_Report_Astronomy].pdf`
- **Key Findings & Summary:**
  - Used data in the given PS such as Stellar Properties, Brightness Observations, and Constants
  - Detected exoplanets
  - Determined Planet size
  - Determined the Planetary Orbits
  - Found the most promising world

---

### 🌌 Problem Statement 4: [Insert Title of PS4]
- **Folder:** [`/PS4_Product_Ideathon`](./PS4_Product_Ideathon)
- **Report:** `project_CENTRIFUGE-Visuals.pptx`
- **Key Findings & Summary:**
  - [Insert 2-3 key highlights or metrics from your teammate solving PS4]

---

## 🛠️ Technology Stack
- **Languages & Frameworks:** Python 3.x, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Google Colab, Jupyter Notebook
- **Exporting Tools:** ReportLab, Base64 HTML PDF Compiler
