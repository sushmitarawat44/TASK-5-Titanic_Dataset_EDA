# 🚢 Titanic - Exploratory Data Analysis (EDA)

This project performs exploratory data analysis on the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/overview) from Kaggle using Python and Jupyter Notebook.

## 📌 Objective

- Understand the structure and trends in the Titanic dataset.
- Visualize relationships between variables like age, gender, class, and survival.
- Extract insights through data cleaning, statistical summaries, and plots.

## 📁 Dataset

- File: train.csv
- Cleaned manually:
  - Filled missing Age values with the median (28)
  - Replaced missing Cabin values with "Unknown"

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn
- JupyterLab (via Anaconda)

## 🔍 Key EDA Techniques

- .describe(), .info(), .value_counts()
- Histograms, Boxplots, Countplots, Heatmaps, Pairplots
- Correlation analysis

## 📊 Visualizations Include:

- Survival distribution by gender and class
- Age and fare distributions
- Correlation heatmap
- Embarkation point vs survival

## 📄 Output

- Jupyter Notebook: titanic_eda.ipynb
- PDF Report: Titanic_EDA_Report.pdf

## ✅ Observations Summary

- Females had significantly higher survival rates.
- Higher class passengers had better chances of survival.
- Median age was 28.
- "Unknown" cabin values indicate missingness that might hide important patterns.

## 📎 Credits

- Dataset from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview)
- Analysis and documentation by Sushmita Rawat

---

## 📌 How to Run

1. Clone the repo or download files.
2. Open titanic_eda.ipynb in JupyterLab or Jupyter Notebook.
3. Run the cells in order.

