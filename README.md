# Python Statistics Projects

This repository contains three statistical analysis projects. Each project demonstrates proficiency in statistical modelling, data visualisation, and Python programming.

## 📊 Projects Overview

### 1. Analysis of Regional Property Price Trends
**File:** `Analysis of Regional Property Price Trends.ipynb`

An analysis of regional property price changes in England between July 2017 and July 2018.

**Key Features:**
- Statistical analysis of flat price changes across 9 English regions
- Chi-square test and permutation test for independence testing
- Custom visualisations including dot plots and regional bar charts
- G-statistic calculation for hypothesis testing

**Technologies:** `pandas`, `numpy`, `matplotlib`, `scipy`

---

### 2. Demographic Analysis of UK Population Using 2021 Census Data
**File:** `Demographic Analysis of UK Population Using 2021 Census Data.ipynb`

A demographic analysis leveraging the 2021 UK Census data to explore population characteristics and trends.

**Key Features:**
- Analysis of census data at LSOA (Lower Layer Super Output Area) level
- Demographic trend identification and visualisation
- Spatial data analysis using geographic datasets

**Technologies:** `pandas`, `numpy`, `matplotlib`, `geopandas`

---

### 3. Statistical Analysis of Texas Bridges Using Regression Modelling
**File:** `Statistical Analysis of Texas Bridges Using Regression Modelling.ipynb`

A statistical investigation of Texas bridge infrastructure using regression modelling techniques to understand factors affecting bridge conditions.

**Key Features:**
- Regression analysis of bridge infrastructure data
- Model building and validation
- Statistical inference and interpretation

**Technologies:** `pandas`, `numpy`, `matplotlib`, `scipy`, `statsmodels`

---

## 📁 Repository Structure

```
Python Stats Projects/
├── README.md
├── data/
│   ├── average_flat_prices.csv
│   ├── LSOA_data.csv
│   ├── LSOA_England_geom.gpkg
│   └── tx19_bridges_sample.csv
├── notebooks/
│   ├── Analysis of Regional Property Price Trends.ipynb
│   ├── Demographic Analysis of UK Population Using 2021 Census Data.ipynb
│   └── Statistical Analysis of Texas Bridges Using Regression Modelling.ipynb
└── html_exports/
    ├── Analysis_of_Regional_Property_Price_Trends.html
    ├── Demographic_Analysis_of_UK_Population_Using_2021_Census_Data.html
    └── Statistical_Analysis_of_Texas_Bridges_Using_Regression_Modelling.html
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Required Packages

Install the required packages using pip:

```bash
pip install pandas numpy matplotlib scipy geopandas statsmodels
```

---

## 📈 Key Statistical Methods Used

- **Hypothesis Testing:** Chi-square tests, permutation tests
- **Regression Analysis:** Linear and multiple regression modelling
- **Descriptive Statistics:** Central tendency, dispersion, distribution analysis
- **Data Visualisation:** Custom plots using matplotlib
- **Spatial Analysis:** Geographic data manipulation and visualisation


---

## 🙏 Acknowledgments

- UK Ministry of Housing, Communities & Local Government for property price data
- Office for National Statistics for 2021 Census data
- Texas Department of Transportation for bridge infrastructure data