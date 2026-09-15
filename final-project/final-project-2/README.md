# 🌍 Global Happiness Report Analysis

A data analysis project exploring the **2015 Global Happiness Report** to understand how economic, social, health, freedom, and government-related factors are associated with happiness across countries.

---

## 📌 Project Overview

This project analyzes happiness data from **158 countries** and uses Python-based data analysis and visualization to identify patterns in national happiness.

The analysis focuses on:

- Happiness rankings and scores
- Economic conditions (GDP per capita)
- Social support / family
- Healthy life expectancy
- Freedom to make life choices
- Trust in government / corruption
- Regional differences
- Correlation between happiness and major contributing factors

> **Note:** Correlation indicates an association between variables; it does not prove that one factor directly causes happiness.

---

## 📂 Dataset

**File:** `2015-selected-columns.csv`

### Dataset Size
- **Rows:** 158 countries
- **Columns:** 10

### Main Columns

| Column | Description |
|---|---|
| `Country` | Country name |
| `Region` | Geographical region |
| `Happiness Rank` | Country's happiness ranking |
| `Happiness Score` | Overall happiness score |
| `Standard Error` | Standard error of the happiness estimate |
| `Economy (GDP per Capita)` | Economic performance indicator |
| `Family` | Social support / family factor |
| `Health (Life Expectancy)` | Healthy life expectancy indicator |
| `Freedom` | Freedom to make life choices |
| `Trust (Government Corruption)` | Perceived government corruption / institutional trust |

---

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – data loading, cleaning, and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization

---

## 📊 Analysis Performed

### 1. Dataset Loading
The dataset is imported into a Pandas DataFrame for analysis.

### 2. Exploratory Data Analysis
The project examines:
- Dataset structure
- Data types
- Missing values
- Basic information about the variables

### 3. Statistical Summary
Descriptive statistics are used to understand the distribution and range of numerical variables.

### 4. Happiest Countries
The **Top 10 countries** by Happiness Score are identified.

### 5. Lowest Happiness Scores
The **Bottom 10 countries** by Happiness Score are analyzed.

### 6. Happiness Score Distribution
A visualization is used to understand how happiness scores are distributed across countries.

### 7. GDP vs Happiness
The relationship between economic conditions and happiness is visualized and analyzed.

### 8. Social Support vs Happiness
The association between the Family/Social Support factor and Happiness Score is examined.

### 9. Life Expectancy vs Happiness
Healthy life expectancy is compared with national happiness.

### 10. Freedom vs Happiness
The relationship between freedom to make life choices and happiness is explored.

### 11. Government Trust vs Happiness
Government corruption/trust is compared with Happiness Score.

### 12. Correlation Heatmap
A correlation matrix provides an overview of relationships among the major numerical variables.

### 13. Regional Happiness Analysis
Average happiness is compared across geographical regions.

### 14. Major Factor Correlations
The correlation of important factors with Happiness Score is calculated to identify stronger and weaker associations.

---

## 🔎 Key Insights

The analysis highlights several important patterns:

- Happiness scores vary substantially between countries.
- Economic conditions show a positive association with happiness.
- Social support is strongly associated with higher happiness scores.
- Health and life expectancy also show a positive relationship with happiness.
- Freedom is positively associated with happiness.
- Government trust/corruption can be compared with happiness to understand institutional relationships.
- Regional analysis reveals differences in average happiness between geographical regions.

These findings should be interpreted as **statistical associations rather than causal relationships**.

---

## 📁 Project Structure

```text
Global-Happiness-Report-Analysis/
│
├── 2015-selected-columns.csv
├── Global_Happiness_Report_Analysis.ipynb
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone or download the project

Make sure the following files are available in the same project directory:

- `2015-selected-columns.csv`
- `Global_Happiness_Report_Analysis.ipynb`

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open:

```text
Global_Happiness_Report_Analysis.ipynb
```

Run the notebook cells from top to bottom.

---

## 📈 Expected Output

The notebook produces analytical outputs and visualizations including:

- Top and bottom happiness rankings
- Happiness score distribution
- GDP vs Happiness scatter plot
- Family/Social Support vs Happiness plot
- Life Expectancy vs Happiness plot
- Freedom vs Happiness plot
- Government Trust vs Happiness plot
- Correlation heatmap
- Regional happiness comparison
- Correlation analysis of major happiness factors

---

## 🎯 Project Objective

The main objective of this project is to demonstrate how **exploratory data analysis (EDA), statistical analysis, and data visualization** can be used to understand real-world datasets and identify meaningful patterns.

---

## 👨‍💻 Project Type

**vishvas solanki**

**guide by girish sir gondaliya**

**Data Analysis / Exploratory Data Analysis (EDA)**

**Dataset:** Global Happiness Report – 2015

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 📜 Disclaimer

This project is intended for educational and analytical purposes. The results describe patterns present in the dataset and should not be interpreted as proof of direct cause-and-effect relationships.

---

⭐ If you found this project useful, consider giving it a star.
