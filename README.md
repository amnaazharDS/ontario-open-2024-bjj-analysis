{\rtf1\ansi\ansicpg1252\cocoartf2820
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Ontario Open 2024 - BJJ Tournament Data Analysis\
\
This project scrapes and analyzes competitor and match result data from the Ontario Open 2024 Brazilian Jiu-Jitsu (BJJ) tournament using Smoothcomp data. The goal is to explore performance trends, participant demographics, and build a simple predictive model for match outcomes.\
\
---\
\
## \uc0\u55357 \u56541  Overview\
\
The Ontario Open is one of the largest Brazilian Jiu-Jitsu tournaments in Canada. This project leverages publicly available Smoothcomp data to:\
\
- Understand the competitor landscape (belt levels, affiliations, age divisions, etc.)\
- Explore patterns in match outcomes (submissions, points, DQs)\
- Predict potential match outcomes using lightweight models\
\
---\
\
## \uc0\u55357 \u56513  Files\
\
| File | Description |\
|------|-------------|\
| `OntarioOpen2024_DataExtraction.ipynb` | Web scraping and data transformation |\
| `OntarioOpen2024_EDA.ipynb` | Exploratory Data Analysis on match results and participants |\
| `Predictions.csv` | Sample output of predictive modeling |\
| `smoothcomp_participants.csv` | Cleaned participant dataset |\
| `smoothcomp_results.csv` | Cleaned match result dataset |\
\
---\
\
## \uc0\u55356 \u57263  Project Goals\
\
- Understand participant demographics and tournament structure\
- Visualize trends across belts, age groups, outcomes\
- Build a simple match outcome predictor (Win/Loss) based on public features\
\
---\
\
## \uc0\u55357 \u56550  Getting Started\
\
### Requirements\
\
You'll need Python 3 and Jupyter Notebook. Recommended packages:\
\
```bash\
pandas\
numpy\
matplotlib\
seaborn\
scikit-learn\
\
\uc0\u55357 \u56522  Key Insights\
Most matches end via points (not submissions)\
\
Blue belts represent over 60% of competitors\
\
Adult Male divisions dominate participation\
\
\uc0\u55357 \u56960  Future Work\
Incorporate historical Smoothcomp data for stronger prediction features\
\
Enhance modeling (e.g., using grappling-specific metrics like match time and submission types)\
\
Deploy an interactive dashboard (e.g., using Streamlit or Flask)\
\
\uc0\u55357 \u56420  Author\
Amna Azhar\
amnazhar@hotmail.com}
