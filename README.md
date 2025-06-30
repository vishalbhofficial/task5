# Exploratory Data Analysis - Titanic Dataset

# Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to discover patterns, trends, and correlations that can help understand survival chances.

---

# Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Datasets Used
1. train.csv
2. test.csv
3. gender_submission.csv

---

# EDA Highlights
- Checked for missing values and data types using `.info()` and `.isnull().sum()`.
- Explored dataset statistics using `.describe()`.
  
- Visualized:
  - Survival rates by gender and class.
  - Age distribution and class-wise boxplots.
  - Correlation heatmap.
 
- Key plots used: `countplot`, `histplot`, `boxplot`, `heatmap`.

---

# Key Insights
- Gender Matters: Females had significantly higher survival rates than males.
- Class Privilege: Passengers in 1st class had better chances of survival.
- Age Factor: Children and younger passengers had higher survival rates.
- Fare Influence: Higher fare showed slight correlation with survival.

---

# Files Included
- `EDA_Titanic.ipynb` – Jupyter Notebook with full EDA.
- `EDA_Report.pdf` – PDF version of the analysis.
- `train.csv`, `test.csv`, `gender_submission.csv` – Titanic datasets.


