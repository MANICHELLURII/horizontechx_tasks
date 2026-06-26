# 🚀 HorizonTechX — AI & Data Science Internship Tasks

[![Internship](https://img.shields.io/badge/Internship-Horizon%20TechX-orange?style=flat-square)](https://www.horizontechx.com)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)]()

> Repository containing all tasks completed during the **Horizon TechX AI & Data Science Virtual Internship Program**.  
> Each task is implemented as a fully executed Jupyter Notebook with real datasets, end-to-end ML pipelines, and publication-quality visualizations.

---

## 👤 Intern Details

| Field | Details |
|---|---|
| **Name** | Mani Chelluri |
| **Program** | AI & Data Science Internship |
| **Organization** | Horizon TechX |
| **GitHub** | [@MANICHELLURII](https://github.com/MANICHELLURII) |

---

## 📁 Repository Structure

```
horizontechx_tasks/
│
├── horizontechx_sentiment_analysis/     # Task 6 — Sentiment Analysis
│   ├── Sentiment_Analysis_Task6.ipynb
│   ├── Tweets.csv
│   └── README.md
│
├── horizontechx_eda_analysis/           # Task 3 — EDA & Data Analysis
│   ├── COVID19_EDA_Task3.ipynb
│   └── README.md
│
├── horizontechx_visualization_dashb/   # Task 4 — Data Visualization Dashboard
│   ├── COVID19_Dashboard_Task4.ipynb
│   └── README.md
│
└── README.md                            ← You are here
```

---

## ✅ Tasks Completed

### Task 6 — Sentiment Analysis
📂 `horizontechx_sentiment_analysis/`

Analyzed **Twitter US Airline Sentiment** data to classify public opinions as Positive, Neutral, or Negative using a full NLP pipeline.

**Highlights:**
- Text preprocessing — URL/mention removal, lemmatization, stopword filtering
- Two models trained: TF-IDF + Logistic Regression and TF-IDF + Naive Bayes
- Logistic Regression achieved **~89% accuracy** and **~88% Macro F1**
- Word clouds, keyword frequency analysis, and confusion matrices
- Custom **trust scoring layer** — classifies each prediction as SAFE / REVIEW NEEDED / FLAGGED based on model confidence

**Stack:** `Python` `NLTK` `Scikit-learn` `Matplotlib` `Seaborn` `WordCloud`

---

### Task 3 — EDA & Data Analysis
📂 `horizontechx_eda_analysis/`

Performed comprehensive Exploratory Data Analysis on the **Our World in Data COVID-19 Dataset** (Jan 2020 – Aug 2024) covering 200+ countries across 67 variables.

**Highlights:**
- Global trend analysis with 7-day rolling averages
- Country-level rankings by cases, deaths, and case fatality rate
- Continent-level breakdown with proportional analysis
- Wave pattern comparison across top 5 most affected countries
- Correlation heatmap — COVID metrics vs GDP, HDI, Median Age, Vaccination Rate
- Vaccination rate vs death rate scatter with trend line
- Monthly heatmap showing pandemic waves across top 10 countries

**Dataset:** [Our World in Data — COVID-19](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv) *(download separately — 94MB)*

**Stack:** `Python` `Pandas` `NumPy` `Matplotlib` `Seaborn`

---

### Task 4 — Data Visualization Dashboard
📂 `horizontechx_visualization_dashb/`

Built 4 dark-theme, multi-panel publication-quality dashboards on the same COVID-19 dataset, designed for decision-making and storytelling.

**Dashboards:**
| # | Title | What it answers |
|---|---|---|
| 1 | Global Overview | How did the pandemic evolve globally over 4 years? |
| 2 | Country Deep-Dive | Which countries were hit hardest and how did waves differ? |
| 3 | Vaccination & Impact | Did vaccination reduce deaths? Who vaccinated fastest? |
| 4 | Socioeconomic Intelligence | How do GDP, HDI, and age correlate with COVID outcomes? |

**Dataset:** [Our World in Data — COVID-19](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv) *(download separately — 94MB)*

**Stack:** `Python` `Pandas` `Matplotlib` `Seaborn` `GridSpec`

---

## 🛠️ Setup & Run

```bash
# Clone the repo
git clone https://github.com/MANICHELLURII/horizontechx_tasks.git
cd horizontechx_tasks

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud jupyter

# Download NLTK assets (run once)
python -c "import nltk; [nltk.download(p) for p in ['punkt','stopwords','wordnet','omw-1.4']]"

# Launch notebooks
jupyter notebook
```

> **Note:** For Tasks 3 & 4, download the COVID-19 dataset from the link above and place `owid-covid-data.csv` in the respective task folder before running.

---

## 📊 Key Results

| Task | Model / Tool | Key Metric |
|---|---|---|
| Sentiment Analysis | TF-IDF + Logistic Regression | Accuracy: 89% · Macro F1: 88% |
| EDA | Pandas + Seaborn | 7 analytical visualizations + full statistical report |
| Dashboard | Matplotlib GridSpec | 4 dark-theme dashboards · 15+ panels |

---

*Built with 🧠 by Mani Chelluri · Horizon TechX AI & Data Science Internship 2026*
