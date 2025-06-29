# COVID-19 U.S. Data Analysis – SQL + Python Project

This project explores how vaccination coverage across U.S. states influenced COVID-19 case severity and fatality outcomes. By integrating **CDC API data**, cleaning and transforming it using **Python**, analyzing patterns using **SQL**, and applying a **machine learning model**, this project provides insights relevant to public health policy and pandemic response.

---

## Objective
To examine how state-level vaccination rates impact COVID-19 case counts and death rates across the U.S., and to uncover disparities in public health outcomes.

---

## Tools & Technologies
- **Python (Pandas, Matplotlib, Seaborn, SQLite, Scikit-Learn)**
- **SQL** (CTEs, window functions, aggregation)
- **CDC APIs** (Live data pull and processing)
- **Jupyter Notebook** (for analysis and reporting)

---

## Key Project Components
- **Data Preprocessing**: Cleaned and merged COVID-19 case, death, and vaccination data from CDC APIs  
- **Feature Engineering**: Created new metrics like case fatality rate, elderly protection index, and vaccination categories  
- **Exploratory Data Analysis (EDA)**: Visualized patterns across states and time using Python  
- **SQL Queries**: 12 analytical queries to explore weekly spikes, fatality trends, and state-level impacts  
- **Machine Learning Model**: Linear regression model to predict weekly new cases based on vaccination and time trends  

---

## Highlighted Insights
- States with high vaccination rates had significantly lower fatality risks  
- Booster coverage moderately correlated with reduced case counts  
- CA, TX, and FL had the highest COVID-19 deaths, but CFRs varied based on vaccination strength  
- The linear model captured low/moderate case weeks well, but struggled with high-variance spikes

---

## Target Audience
- Public Health Officials
- Healthcare Policymakers
- Data Analysts interested in real-world epidemiology use cases

---

## Project Files
- `Final Report - Bisma Rana.ipynb` – Full narrative analysis + visualizations  
- `SQL Queries - Bisma Rana.ipynb` – Executed SQL queries with explanations  
- `Final Project.pdf` – Slide-format summary of the entire project

---

## Future Improvements
- Normalize for population size and socio-economic indicators  
- Apply classification/time series models for more accurate predictions  
- Explore causal modeling to isolate vaccination impact from confounding factors
