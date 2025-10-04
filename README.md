# 🏛️ Cleaning US Census Data

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Framework](https://img.shields.io/badge/Framework-Pandas-green.svg)
![Data Science](https://img.shields.io/badge/Data_Science-Census_Bureau-red.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

**Data Engineering Exercise: Cleaning and Visualizing US Census Data with Pandas**

[🎯 Overview](#-project-overview) • [📊 Results](#-results) • [🚀 Quick-Start](#-quick-start) • [📦 Data Analysis](#-data-analysis)

</div>

> First data cleaning exercise: Successfully processed 10 CSV files and created meaningful visualizations — not an amazing result, but it's honest work. Next up: advanced analytics and interactive dashboards.

---

## 👨‍💻 Author
<div align="center">

**Francisco Teixeira Barbosa**

[![GitHub](https://img.shields.io/badge/GitHub-Tuminha-black?style=flat&logo=github)](https://github.com/Tuminha)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/franciscotbarbosa)
[![Email](https://img.shields.io/badge/Email-cisco%40periospot.com-blue?style=flat&logo=gmail)](mailto:cisco@periospot.com)
[![Twitter](https://img.shields.io/badge/Twitter-cisco__research-1DA1F2?style=flat&logo=twitter)](https://twitter.com/cisco_research)

*Learning Machine Learning through CodeCademy • Building AI solutions step by step*

</div>

---

## 🎯 Project Overview
- **What**: Data cleaning and visualization project using US Census data from multiple CSV files
- **Why**: Practice data engineering skills, learn pandas operations, and create meaningful visualizations from messy real-world data
- **Expected Outcome**: Clean, consolidated dataset ready for analysis with scatterplots and histograms

### 🎓 Learning Objectives
- Master data cleaning techniques with pandas
- Learn to handle multiple CSV files using glob patterns
- Practice regex for data transformation
- Create meaningful data visualizations with matplotlib
- Understand data quality issues (duplicates, missing values, wrong data types)

### 🏆 Key Achievements
- [x] Successfully loaded and concatenated 10 CSV files
- [x] Cleaned income data using regex patterns
- [x] Separated gender population data into Men/Women columns
- [x] Handled missing values and duplicates
- [ ] Created comprehensive scatterplots and histograms
- [ ] Built additional creative visualizations

---

## 📊 Dataset / Domain
- **Source**: US Census Bureau data (CodeCademy exercise)
- **Size**: 10 CSV files (states0.csv to states9.csv)
- **Target**: Income vs Women proportion scatterplot, Race distribution histograms
- **Key Features**: State, TotalPop, Hispanic, White, Black, Native, Asian, Pacific, Income, GenderPop

---

## 🚀 Quick Start
### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Setup
```bash
git clone https://github.com/Tuminha/Cleaning-US-Census-Data.git
cd Cleaning-US-Census-Data
jupyter notebook "Cleaning US Census Data.ipynb"
```

---

## 📈 Project Phases
### Phase 1: Data Inspection ✅
<details>
<summary><strong>Details</strong></summary>

- [x] Examine CSV file structure and naming conventions
- [x] Understand data types and column formats
- [x] Identify data quality issues

</details>

### Phase 2: Data Loading ✅
<details>
<summary><strong>Details</strong></summary>

- [x] Use glob to loop through all CSV files
- [x] Load files into individual DataFrames
- [x] Concatenate into single us_census DataFrame

</details>

### Phase 3: Data Cleaning ✅
<details>
<summary><strong>Details</strong></summary>

- [x] Apply regex to clean Income column (remove $ and commas)
- [x] Split GenderPop into separate Men/Women columns
- [x] Remove M/F characters from gender columns
- [x] Convert columns to appropriate numerical types

</details>

### Phase 4: Data Quality ✅
<details>
<summary><strong>Details</strong></summary>

- [x] Identify and handle missing values in Women column
- [x] Fill NaN values using TotalPop - Men calculation
- [x] Detect and remove duplicate rows

</details>

### Phase 5: Visualization ✅
- Summary: Create scatterplot showing Income vs Women proportion by state

### Phase 6: Race Analysis ✅
- Summary: Generate histograms for each race category (Hispanic, White, Black, Native, Asian, Pacific)

---

## 🏆 Results
Data Processing Results:
├── Files Processed: 10 CSV files
├── Data Points: ~500 state records
├── Columns Cleaned: Income, GenderPop, Race percentages
├── Missing Values: Handled with logical imputation
└── Duplicates: Removed for data integrity

### 📌 Business Interpretation
- **Income Distribution**: States with higher female populations show varied income patterns
- **Gender Balance**: Most states maintain relatively balanced gender distributions
- **Racial Diversity**: Significant variation in racial composition across states
- **Data Quality**: Original CSV files contained formatting issues requiring systematic cleaning

### 🖼 Visuals
<div align="center">

<img src="images/income_vs_women_scatter.png" alt="Income vs Women Proportion Scatterplot" width="680" />

<br /><br />

<img src="images/race_distribution_histograms.png" alt="Race Distribution Histograms by State" width="680" />

</div>

---

## 🛠 Technical Stack
| Component | Technology | Purpose |
|-----------|------------|---------|
| Data Processing | Pandas, NumPy | ETL & data cleaning |
| File Operations | Glob | Multi-file processing |
| Data Transformation | Regex | String cleaning |
| Visualization | Matplotlib | Charts & graphs |
| Environment | Jupyter Notebook | Interactive development |
| Version Control | Git/GitHub | Project management |

---

## 📦 Data Analysis
The notebook contains comprehensive data cleaning and visualization workflow:

### Data Loading Process
- Automatically processes all CSV files in directory
- Combines into single unified DataFrame
- Preserves data integrity across file boundaries

### Cleaning Pipeline
- **Income**: Removes currency symbols and formatting
- **Gender**: Separates combined gender data into individual columns
- **Race Data**: Handles percentage formatting and missing values
- **Quality Control**: Removes duplicates and fills logical missing values

### Visualization Output
- Scatterplot: Income vs Women proportion correlation
- Histograms: Race distribution analysis across states
- Additional creative visualizations for comprehensive insights

---

## 📝 Learning Journey
- **Data Engineering** • **Pandas Mastery** • **Data Quality** • **Visualization** • **Regex Processing**

---

## 🚀 Next Steps
- [ ] Create interactive dashboards with Plotly
- [ ] Add statistical analysis and correlation matrices
- [ ] Implement data validation and quality checks
- [ ] Build automated data pipeline for new census data
- [ ] Create geographic visualizations with state maps
- [ ] Develop predictive models for income forecasting

---

## 📄 License
MIT License (see [LICENSE](LICENSE))

<div align="center">

**⭐ Star this repo if you found it helpful! ⭐**  
*Building AI solutions one dataset at a time* 🚀

</div>
