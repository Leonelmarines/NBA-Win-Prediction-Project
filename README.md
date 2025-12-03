# NBA Team Win Prediction Project
### Machine Learning • Data Cleaning • Feature Engineering • Predictive Modeling

This project predicts NBA team win totals using multi-season performance data (2014–2025). The goal is to identify which team-level metrics most strongly influence success and to build a highly accurate predictive model capable of forecasting future wins. Using advanced statistics and machine learning, the analysis highlights how scoring efficiency, defensive performance, possessions, and turnovers affect team outcomes.

---

## Project Overview
- Built a full **data pipeline** to clean, transform, and prepare game-level data  
- Engineered metrics such as **Net Rating, TS%, eFG%, ORtg, DRtg, TOV%, Pace, REB%**  
- Aggregated game logs into **team-season summaries**  
- Trained multiple ML models and selected the **Random Forest Regressor** as the top performer  
- Achieved **R² ≈ 0.99** with an average prediction error of **~2–3 wins**  
- Predicted win totals for the **2025–26 NBA season**

---

## My Role
**Project Lead**  
- Managed the full workflow, notebook structure, and team direction  
- Cleaned and prepared every dataset used in the project  
- Created season labels, fixed date formats, standardized team IDs  
- Engineered all advanced statistics used for modeling  
- Contributed to the development and tuning of the **Random Forest model**  
- Helped build and format **Altair visualizations** for results and predictions  

---

## Key Findings
The Random Forest model identified several major predictors of team success:

- **True Shooting % (TS%)** – strongest indicator of offensive efficiency  
- **Turnover % (TOV%)** – ball security highly correlated with wins  
- **Net Rating (ORtg − DRtg)** – comprehensive performance indicator  
- **Rebound %** – more possessions translate into more wins  
- Efficiency and possession metrics were more predictive than raw scoring totals

---

## Model Performance
**Random Forest Regressor**
- **R²:** ~0.99  
- **MAE:** ~2–3 wins  
- **Interpretability:** Feature importance clearly highlights key drivers of success  

---

## Tech Stack
- **Python**
- Pandas, NumPy  
- Scikit-learn  
- Altair  
- Jupyter Notebook  

---

## Repository Structure
nba-win-prediction/
│
├── data/ # Cleaned or sample datasets
├── notebook/ # Jupyter Notebook (full project)
├── images/ # Exported Altair charts (optional)
└── README.md # Project documentation

---

## 📦 Files
- **COP4283_Final_Report.ipynb** — full end-to-end notebook  
- **TeamStatistics_clean.csv** or sample — processed dataset  
- Visualizations, charts, and exported figures (optional)

---

## 🏁 Summary
This project demonstrates a complete machine-learning workflow applied to sports analytics, achieving near-perfect predictive accuracy. It highlights the importance of efficiency, turnovers, and net rating in determining NBA team success and provides a strong portfolio example of data cleaning, feature engineering, predictive modeling, and visualization.

---

If you have any questions or want to explore the model, feel free to reach out!

