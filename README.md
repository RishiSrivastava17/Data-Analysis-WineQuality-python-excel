# 🍷 Wine Quality Data Analysis (Python + Excel)
## 📌 Project Overview
This project analyzes the Wine Quality Dataset (both Red Wine and White Wine) using Python (pandas, matplotlib, seaborn) and Excel.
The dataset contains physicochemical properties of wine samples (e.g., acidity, sugar, chlorides, alcohol) along with their quality scores rated between 0–10.
The main objective is to explore the dataset, understand feature correlations, detect patterns affecting wine quality, and visualize insights.

## 📂 Dataset
- Red Wine: winequality-red.csv (1599 samples)
- White Wine: winequality-white.csv (4898 samples)
Source: Kaggle

## Features
Each record contains the following physicochemical attributes:
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
12. Quality (target variable: score between 0–10)

## ⚙️ Steps Performed
🔹 Data Preprocessing
- Read dataset using pandas (pd.read_csv(..., delimiter=';'))
- Checked for missing values → none found
- Verified dataset structure (df.info(), df.describe())

🔹 Exploratory Data Analysis (EDA)
- Distribution of features using histograms
- Correlation analysis (df.corr())
- Heatmap visualization (seaborn) for features with correlation > 0.7
- Compared Red Wine vs White Wine feature statistics

🔹 Excel Analysis
- Imported data into Excel for pivot tables & charts
- Plotted trends for alcohol content, acidity, sugar vs quality

## 📊 Key Insights
- Alcohol content strongly correlates with higher quality ratings.
- Volatile acidity negatively impacts quality.
- Residual sugar has higher variation in white wines compared to red wines.
- No missing data → clean dataset.

## 🛠️ Tools & Libraries
- Python 3
- pandas
- matplotlib
- seaborn
- Excel (for quick analysis & charting)

## 🚀 How to Run

Clone the repo:

git clone https://github.com/RishiSrivastava17/Data-Analysis-WineQuality-python-excel.git
cd Data-Analysis-WineQuality-python-excel

Install dependencies:
```bash
pip install pandas matplotlib seaborn
```
Run the Jupyter Notebook / Python script to generate analysis:
python analysis.py

## 🙌 Acknowledgements

- Dataset: Kaggle
- Inspiration from Kaggle notebooks & open-source EDA practices.
