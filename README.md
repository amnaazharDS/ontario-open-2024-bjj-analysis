# Ontario Open 2024 - BJJ Tournament Data Analysis

This project scrapes and analyzes competitor and match result data from the Ontario Open 2024 Brazilian Jiu-Jitsu (BJJ) tournament using Smoothcomp data. The goal is to explore performance trends, participant demographics, and build a simple predictive model for match outcomes.

---

## 📝 Overview

The Ontario Open is one of the largest Brazilian Jiu-Jitsu tournaments in Canada. This project leverages publicly available Smoothcomp data to:

- Understand the competitor landscape (belt levels, affiliations, age divisions, etc.)
- Explore patterns in match outcomes (submissions, points, DQs)
- Predict potential match outcomes using lightweight models

---

## 📁 Files

| File | Description |
|------|-------------|
| `OntarioOpen2024_DataExtraction.ipynb` | Web scraping and data transformation |
| `OntarioOpen2024_EDA.ipynb` | Exploratory Data Analysis on match results and participants |
| `Predictions.csv` | Sample output of predictive modeling |
| `smoothcomp_participants.csv` | Cleaned participant dataset |
| `smoothcomp_results.csv` | Cleaned match result dataset |

---

## 🎯 Project Goals

- Understand participant demographics and tournament structure
- Visualize trends across belts, age groups, outcomes
- Build a simple match outcome predictor (Win/Loss) based on public features

---

## 📦 Getting Started

### Requirements

You'll need Python 3 and Jupyter Notebook. Recommended packages:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn

📊 Key Insights
Most matches end via points (not submissions)

Blue belts represent over 60% of competitors

Adult Male divisions dominate participation

🚀 Future Work
Incorporate historical Smoothcomp data for stronger prediction features

Enhance modeling (e.g., using grappling-specific metrics like match time and submission types)

Deploy an interactive dashboard (e.g., using Streamlit or Flask)

👤 Author
Amna Azhar
amnazhar@hotmail.com