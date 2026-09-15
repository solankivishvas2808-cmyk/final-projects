# COVID-19 Data Analysis & Visualization

<div align="center">

## 📊 Project 1 — COVID-19 Data Analysis and Visualization

**Prepared by:** Vishvaskumar Solanki  
**Guided by:** Girish Sir Gondaliya  

**Technology:** Python · Pandas · NumPy · Matplotlib · Seaborn  
**Environment:** Jupyter Notebook

</div>

---

## 📌 Project Overview

This project presents a structured **COVID-19 Data Analysis and Visualization** workflow using Python.

The objective is to transform raw COVID-19 data into meaningful information through:

- Data loading and inspection
- Data cleaning and preprocessing
- Country-wise analysis
- Continent-wise analysis
- Statistical calculations
- COVID-19 recovery and death rate analysis
- Population-normalized case analysis
- Correlation analysis
- Data visualization

The project is designed to demonstrate practical **data analysis, data preprocessing, exploratory data analysis (EDA), and visualization** skills using widely adopted Python libraries.

---

## 🎯 Objectives

The major objectives of this project are:

1. Understand the structure and quality of the COVID-19 dataset.
2. Clean and prepare the data for analysis.
3. Calculate useful COVID-19 performance metrics.
4. Compare reported cases across countries.
5. Compare reported deaths across countries.
6. Analyze COVID-19 statistics by continent.
7. Calculate recovery and death rates.
8. Analyze cases relative to population size.
9. Study relationships between important numerical variables.
10. Present analytical findings through clear visualizations.

---

## 🗂️ Dataset

The project uses the file:

```text
covid_19.csv
```

### Dataset Dimensions

- **Rows:** 238
- **Columns:** 9
- **Date represented:** 2024-06-30

### Dataset Columns

| Column | Description |
|---|---|
| `day` | Date of the recorded data |
| `time` | Time information |
| `continent` | Continent associated with the country |
| `country` | Country or geographic record |
| `population` | Population of the country |
| `Cases` | Reported COVID-19 cases |
| `Recovered` | Reported recoveries |
| `Deaths` | Reported deaths |
| `Tests` | Reported COVID-19 tests |

> **Note:** The dataset contains aggregate records in addition to country-level records. During preprocessing, aggregate rows are excluded from country-level analysis to prevent double counting.

---

## 🧰 Technologies & Libraries

The project uses the following tools:

| Technology | Purpose |
|---|---|
| **Python** | Core programming language |
| **Pandas** | Data loading, cleaning, transformation and analysis |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **Jupyter Notebook** | Interactive development and presentation |

---

## 🔄 Project Workflow

```text
Raw COVID-19 Dataset
        │
        ▼
Load Dataset
        │
        ▼
Inspect Data
        │
        ▼
Clean & Preprocess
        │
        ▼
Create Analytical Metrics
        │
        ▼
Country-wise Analysis
        │
        ▼
Continent-wise Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Visualization
        │
        ▼
Key Findings & Conclusion
```

---

## 🧹 Data Preprocessing

The preprocessing stage includes:

- Copying the original dataset for analysis
- Converting date and time fields
- Converting numerical columns into appropriate numeric types
- Handling missing values
- Removing aggregate/summary records from country-level analysis
- Separating usable country and continent data

This ensures that the analytical results are more reliable and avoids treating summary rows as individual countries.

---

## 📐 Analytical Metrics

The project calculates the following derived metrics.

### Recovery Rate

```text
Recovery Rate (%) =
(Recovered / Cases) × 100
```

### Death Rate

```text
Death Rate (%) =
(Deaths / Cases) × 100
```

### Cases per 100,000 Population

```text
Cases per 100K =
(Cases / Population) × 100,000
```

These metrics allow the project to move beyond raw totals and provide more meaningful comparisons.

---

## 📊 Analysis Performed

### 1. Overall COVID-19 Statistics

The project calculates:

- Total cases
- Total recovered
- Total deaths
- Total tests
- Overall recovery rate
- Overall death rate

### 2. Top 10 Countries by Cases

Countries are ranked according to reported COVID-19 cases and visualized using a bar chart.

### 3. Top 10 Countries by Deaths

Countries are ranked according to reported COVID-19 deaths and visualized for comparison.

### 4. Continent-wise Analysis

COVID-19 cases, recoveries, deaths and tests are aggregated by continent.

### 5. Cases by Continent

A visualization compares the reported COVID-19 cases across continents.

### 6. Cases, Recoveries and Deaths

A comparative visualization presents major COVID-19 measures for each continent.

### 7. Recovery Rate vs Death Rate

Recovery and death percentages are compared across continents.

### 8. Cases per 100,000 Population

The project identifies countries with high reported cases relative to their population.

### 9. Correlation Analysis

A correlation matrix and heatmap are used to examine relationships between:

- Cases
- Recovered
- Deaths
- Tests
- Population

### 10. Cases vs Deaths

A scatter plot is used to visually examine the relationship between reported cases and deaths across countries.

---

## 📈 Visualizations Included

The notebook includes visualizations such as:

- 📊 Top 10 Countries by COVID-19 Cases
- 📊 Top 10 Countries by COVID-19 Deaths
- 🌍 COVID-19 Cases by Continent
- 📊 Cases, Recoveries and Deaths by Continent
- 📊 Recovery Rate vs Death Rate
- 👥 Cases per 100,000 Population
- 🔥 Correlation Heatmap
- 📉 Cases vs Deaths Scatter Plot

---

## 📁 Project Structure

```text
COVID-19-Data-Analysis/
│
├── covid_19.csv
├── pr-1.ipynb
├── README.md
│
└── outputs/
    └── charts-and-analysis-results
```

---

## ▶️ How to Run the Project

### Step 1 — Install Python

Make sure Python is installed on your system.

### Step 2 — Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3 — Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4 — Open the Project

Open:

```text
pr-1.ipynb
```

### Step 5 — Keep the Dataset in the Same Folder

Make sure:

```text
covid_19.csv
```

and

```text
pr-1.ipynb
```

are located in the same project directory.

### Step 6 — Run the Notebook

Run the cells from top to bottom.

---

## 📌 Key Findings

The notebook automatically identifies:

- Country with the highest reported cases
- Country with the highest reported deaths
- Continent with the highest reported cases
- Overall recovery rate
- Overall death rate
- Dataset date

The exact findings are generated directly from the dataset when the notebook is executed.

---

## ⚠️ Dataset Limitation

This particular dataset represents data for a single date rather than a long multi-date time series.

Therefore, this project is suitable for **cross-sectional comparison** of countries and continents, but it should **not** be interpreted as a complete analysis of COVID-19 trends over time.

It also does not, by itself, establish causal relationships between COVID-19 outcomes and government policies, healthcare systems, or other external factors.

---

## 🎓 Academic Purpose

This project demonstrates practical skills in:

- Python programming
- Data cleaning
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Statistical calculations
- Data visualization
- Interpretation of analytical results
- Presenting a data analysis workflow in Jupyter Notebook

---

## 👨‍💻 Project Information

| Detail | Information |
|---|---|
| **Project Title** | COVID-19 Data Analysis and Visualization |
| **Project Number** | Project 1 |
| **Student** | Vishvaskumar Solanki |
| **Guide** | Girish Sir Gondaliya |
| **Language** | Python |
| **Notebook** | `pr-1.ipynb` |
| **Dataset** | `covid_19.csv` |
| **Primary Libraries** | Pandas, NumPy, Matplotlib, Seaborn |

---

## 🙏 Acknowledgement

I sincerely express my gratitude to **Girish Sir Gondaliya** for his guidance, support, and valuable direction throughout this project.

His guidance helped in understanding the practical workflow of data analysis, visualization, and project presentation.

I am also thankful to everyone who contributed directly or indirectly to the completion of this project.

---

## ✨ Author

### **Vishvaskumar Solanki**

*Student | Data Analysis Project*

---

<div align="center">

### 📊 Turning Data into Meaningful Insights

**COVID-19 Data Analysis & Visualization**

**Guided by Girish Sir Gondaliya**

</div>
