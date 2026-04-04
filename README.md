<div align="center">

<!-- ANIMATED HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=🚀%20SpaceX%20Falcon%209%20Landing%20Predictor&fontSize=36&fontColor=00d4ff&fontAlignY=38&desc=IBM%20Data%20Science%20Capstone%20|%20Machine%20Learning%20End-to-End%20Pipeline&descAlignY=60&descSize=16&animation=fadeIn" width="100%"/>

<br/>

<!-- LIVE BADGES ROW 1 -->
[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white&labelColor=0d1117)](https://jupyter.org)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=0d1117)](https://scikit-learn.org)
[![Plotly](https://img.shields.io/badge/Plotly-Dash-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=0d1117)](https://plotly.com)

<!-- BADGE ROW 2 -->
[![Folium](https://img.shields.io/badge/Folium-Interactive%20Maps-77B829?style=for-the-badge&logo=leaflet&logoColor=white&labelColor=0d1117)](https://python-visualization.github.io/folium/)
[![SQL](https://img.shields.io/badge/SQL-Database%20Analysis-336791?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0d1117)](https://www.sqlite.org/)
[![IBM](https://img.shields.io/badge/IBM-Capstone%20Project-052FAD?style=for-the-badge&logo=ibm&logoColor=white&labelColor=0d1117)](https://www.coursera.org/professional-certificates/ibm-data-science)
[![Status](https://img.shields.io/badge/Status-Completed%20✓-00ff88?style=for-the-badge&labelColor=0d1117)]()

<br/>

<!-- REPO STATS -->
![GitHub repo size](https://img.shields.io/github/repo-size/puneethkrishna369-dotcom/Project-one?style=flat-square&color=00d4ff&labelColor=0d1117)
![GitHub last commit](https://img.shields.io/github/last-commit/puneethkrishna369-dotcom/Project-one?style=flat-square&color=00ff88&labelColor=0d1117)
![GitHub stars](https://img.shields.io/github/stars/puneethkrishna369-dotcom/Project-one?style=flat-square&color=ffd700&labelColor=0d1117)

</div>

---

## 🧠 Project Intelligence Brief

> **Can we predict whether SpaceX's Falcon 9 first stage will successfully land — before a rocket even launches?**
> This end-to-end Data Science pipeline answers that question using real SpaceX launch data, interactive geospatial maps, correlation heatmaps, and multiple ML classifiers battle-tested head-to-head.

---

## 🗂️ Pipeline Architecture
```mermaid
flowchart LR
    A([🌐 SpaceX REST API\n+ Web Scraping]) -->|Raw JSON & HTML| B([🧹 Data Wrangling\nFeature Engineering])
    B -->|Clean DataFrame| C([🗄️ SQL Analysis\nSQLite Queries])
    C --> D([📊 EDA\nSeaborn · Matplotlib])
    D --> E([🗺️ Folium Maps\nGeospatial Analysis])
    E --> F([⚡ Plotly Dash\nInteractive Dashboard])
    F --> G([🤖 ML Classification\nModels])
    G --> H([🏆 Best Model\n& Predictions])

    style A fill:#0d1117,stroke:#00d4ff,color:#00d4ff
    style B fill:#0d1117,stroke:#7c3aed,color:#7c3aed
    style C fill:#0d1117,stroke:#0ea5e9,color:#0ea5e9
    style D fill:#0d1117,stroke:#f59e0b,color:#f59e0b
    style E fill:#0d1117,stroke:#10b981,color:#10b981
    style F fill:#0d1117,stroke:#ef4444,color:#ef4444
    style G fill:#0d1117,stroke:#8b5cf6,color:#8b5cf6
    style H fill:#0d1117,stroke:#ffd700,color:#ffd700
```

---

## 🗺️ Geospatial Launch Site Analysis

> **Folium-powered interactive maps** visualizing all SpaceX launch sites — proximity to coastlines, railways, highways, and cities. Each site plotted with success/failure markers to uncover geographic launch patterns.

| 📍 Launch Site | 🌍 Location | ✅ Successes | ❌ Failures |
|:-:|:-:|:-:|:-:|
| KSC LC-39A | Cape Canaveral, FL | 10 | 3 |
| CCAFS SLC-40 | Cape Canaveral, FL | 20 | 14 |
| VAFB SLC-4E | Vandenberg, CA | 10 | 5 |
| CCAFS LC-40 | Cape Canaveral, FL | 1 | 2 |

---

## 📊 Exploratory Data Analysis — Key Visual Insights

### 🔥 Correlation Heatmap

The feature correlation heatmap revealed critical relationships:

### 📈 Flight Number vs. Launch Success

> **Clear upward trend** — SpaceX's success rate climbs dramatically with more flights. Engineering iteration at work.

### 🪐 Orbit-wise Success Rates

### 🏋️ Payload Mass vs. Success

---

## ⚡ Interactive Plotly Dash Dashboard

A **fully interactive web dashboard** built with Plotly Dash featuring:

- 🎛️ **Dropdown** → Filter by launch site
- 🥧 **Pie Chart** → Total success vs. failure breakdown per site
- 🔘 **Range Slider** → Filter by payload mass (0 – 10,000 kg)
- 📉 **Scatter Plot** → Payload mass vs. outcome correlation, color-coded by booster version

---

## 🤖 Machine Learning — Model Showdown

> Four classifiers entered the arena. Only one wore the crown.

### 📋 Model Performance Comparison

| 🏅 Rank | 🤖 Model | 🎯 Accuracy | 🔁 Best CV Score | ⚙️ Best Parameters |
|:---:|:---|:---:|:---:|:---|
| 🥇 1st | **Decision Tree** | **87.5%** | **0.875** | `max_depth=6, criterion=entropy` |
| 🥈 2nd | **SVM** | **83.3%** | **0.848** | `C=1.0, kernel=rbf` |
| 🥈 2nd | **KNN** | **83.3%** | **0.847** | `n_neighbors=10` |
| 🥈 2nd | **Logistic Regression** | **83.3%** | **0.846` | `C=0.01, solver=liblinear` |

### 🔢 Confusion Matrix — Decision Tree (Best Model)

### 📐 Accuracy Score Visualization

---

## 🗄️ SQL Analysis Highlights
```sql
-- Launch success rate per site
SELECT Launch_Site,
       COUNT(*) AS Total_Launches,
       SUM(CASE WHEN Landing_Outcome = 'Success' THEN 1 ELSE 0 END) AS Successes,
       ROUND(AVG(CASE WHEN Landing_Outcome = 'Success' THEN 100.0 ELSE 0 END), 2) AS Success_Rate
FROM SPACEXTABLE
GROUP BY Launch_Site
ORDER BY Success_Rate DESC;

-- Max payload by customer
SELECT Customer, MAX(PAYLOAD_MASS__KG_) AS Max_Payload
FROM SPACEXTABLE
GROUP BY Customer;

-- Boosters that landed on drone ship
SELECT Booster_Version, Landing_Outcome
FROM SPACEXTABLE
WHERE Landing_Outcome LIKE '%drone ship%'
  AND Date BETWEEN '2010-06-04' AND '2017-03-20';
```

---

## 📁 Project Structure

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/puneethkrishna369-dotcom/Project-one.git
cd Project-one

# Install dependencies
pip install pandas numpy scikit-learn plotly dash folium requests beautifulsoup4 seaborn matplotlib

# Run notebooks in order (01 → 08)
jupyter notebook

# Launch interactive dashboard
python 07_plotly_dash_dashboard.py
```

---

## 📌 Key Findings

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer&text=Built%20with%20🔥%20by%20Puneeth%20Krishna&fontSize=20&fontColor=00d4ff&fontAlignY=65" width="100%"/>

</div>
