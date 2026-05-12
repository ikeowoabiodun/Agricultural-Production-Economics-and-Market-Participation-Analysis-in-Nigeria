## 🌾 Agricultural Productivity, Profitability, Institutional Access, and Market Participation Analysis in Nigeria

## 📌 Project Overview

This project applies econometric and statistical techniques to analyze agricultural productivity, farm profitability, institutional access, and market participation among Nigerian farmers using Python.

The study integrates concepts from agricultural production economics, development economics, and applied econometrics to examine how production inputs, institutional support systems, and market conditions influence farm-level outcomes.

The dataset was structurally generated to simulate realistic economic relationships among agricultural variables, making the project suitable for:

- Agricultural economics research
- Econometrics portfolios
- Data science portfolios
- Graduate school applications
- Development economics demonstrations

### 🎯 Research Objectives

1. Analyze the socioeconomic characteristics of farmers.
2. Examine the determinants of agricultural productivity.
3. Analyze the factors influencing farm profitability.
4. Assess the effect of institutional access on productivity and profit.
5. Examine market participation and marketed surplus among farmers.

### 🗂 Dataset Information

The dataset contains 2,000 farm-level observations and 31 variables related to:

- Farmer demographics
- Farm production characteristics
- Institutional access
- Market participation
- Production inputs
- Revenue and cost structures
- Profitability indicators

### 📊 Key Variables

### 👨‍🌾 Socioeconomic Variables

- Age
- Gender
- Education_Years
- Household_Size
- Years_Farming
- State
- Crop_Type

### 🚜 Farm Production Variables

- Farm_Size_Hectares
- Fertilizer_Use_KG
- Mechanization_Level
- Irrigation_Access
- Rainfall_mm
- Yield_per_Hectare_Tons
- Total_Output_KG

### 🏛 Institutional Variables

- Credit_Access
- Extension_Access
- Cooperative_Membership
- Training_Attendance_Days

### 🛒 Market Variables

- Market_Access_Score
- Distance_to_Market_KM
- Transport_Cost_NGN
- Marketed_Surplus_KG

### 💰 Financial Variables

- Total_Revenue_NGN
- Total_Cost_NGN
- Net_Profit_NGN

## ⚙️ Methodology

### 📈 Descriptive Analysis

- Summary statistics
- Frequency distributions
- Percentage analysis
- Correlation analysis

## 📉 Econometric Techniques

The study employs Ordinary Least Squares (OLS) regression to estimate:

- Determinants of productivity
- Determinants of profitability
- Institutional effects on productivity
- Determinants of marketed surplus

## 🧪 Diagnostic Tests

- Variance Inflation Factor (VIF)
- Jarque–Bera Normality Test
- Breusch–Pagan Heteroskedasticity Test
- Correlation Matrix Analysis

## 🧠 Structural Dataset Design

Unlike purely randomized synthetic datasets, this dataset was generated using structural economic relationships to simulate realistic agricultural systems.

Embedded relationships include:

- Fertilizer use positively affects yield
- Rainfall influences productivity
- Irrigation improves output
- Yield influences profitability
- Farm size affects marketed surplus
- Institutional access improves productivity

Behavioral and market variations were also introduced to improve realism through:

- Household consumption variation
- Market inefficiencies
- Post-harvest losses
- Production shocks
- Institutional heterogeneity

## 📈 Econometric Results Summary

### 📊 Objective 1: Socioeconomic Characteristics of Farmers

### 📊 Descriptive Statistics

| Variable                     | Mean | Std. Dev |
| ---------------------------- | ----: | --------: |
| Age                          | 45.24 |     14.04 |
| Education Years              |  8.42 |      5.21 |
| Household Size               |  7.12 |      3.15 |
| Farming Experience (Years)   | 21.97 |     13.78 |
| Farm Size (Hectares)         | 12.71 |      6.91 |
| Training Attendance (Days)   | 10.02 |      4.86 |

### 👥 Gender Distribution

| Category | Percentage (%) |
| -------- | -------------: |
| Male     |          50.35 |
| Female   |          49.65 |

### 🏛 Institutional Access Distribution

| Variable                  | Percentage (%) |
| ------------------------- | -------------: |
| Credit Access             |          55.35 |
| Extension Access          |          61.50 |
| Cooperative Membership    |          51.25 |
| Irrigation Access         |          46.70 |

### Key Insight

The dataset reflects balanced demographic and institutional distributions suitable for robust econometric analysis.

## 🌱 Objective 2: Determinants of Agricultural Productivity

### 📌 Dependent Variable

- Yield_per_Hectare_Tons

### 📌 Independent Variables

- Fertilizer_Use_KG
- Farm_Size_Hectares
- Rainfall_mm
- Mechanization_Level
- Training_Attendance_Days
- Credit_Access
- Irrigation_Access
- Education_Years

## 📉 Correlation and Multicollinearity

High correlation was observed between:

- Fertilizer_Use_KG and Farm_Size_Hectares
- Mechanization_Level and Farm_Size_Hectares

### 📊 Variance Inflation Factor (VIF)

| Variable                | VIF |
| ----------------------- | --: |
| Fertilizer_Use_KG       | 13.03 |
| Farm_Size_Hectares      | 13.72 |
| Mechanization_Level     |  2.99 |

Moderate multicollinearity was observed among production variables.

### 📈 Productivity Regression Results

| Metric | Value |
| ------ | ----: |
| R-squared | 0.632 |
| Adjusted R-squared | 0.630 |
| F-statistic | 427.2 |
| Prob (F-statistic) | 0.000 |

### 📊 Significant Variables

| Variable                     | Coefficient | P-value | Interpretation |
| ---------------------------- | ----------: | ------: | -------------- |
| Fertilizer_Use_KG            |      0.0040 |   0.000 | Positive significant effect |
| Rainfall_mm                  |      0.0008 |   0.000 | Positive significant effect |
| Training_Attendance_Days     |      0.0149 |   0.000 | Positive significant effect |
| Mechanization_Level          |      0.2679 |   0.000 | Positive significant effect |
| Irrigation_Access            |      0.4007 |   0.000 | Positive significant effect |
| Education_Years              |      0.0308 |   0.000 | Positive significant effect |

### 🧪 Diagnostic Tests

| Test | Statistic | P-value |
| ---- | --------: | ------: |
| Jarque–Bera | 0.636 | 0.728 |
| Breusch–Pagan LM | 12.82 | 0.118 |
| Breusch–Pagan F | 1.61 | 0.118 |

### Interpretation

Higher fertilizer use, irrigation access, mechanization, education, rainfall, and agricultural training significantly improved productivity.

## 💰 Objective 3: Factors Influencing Farm Profitability

## 📌 Dependent Variable

- Net_Profit_NGN

### 📈 Profitability Regression Results

| Metric | Value |
| ------ | ----: |
| R-squared | 0.895 |
| Adjusted R-squared | 0.895 |
| F-statistic | 1885 |
| Prob (F-statistic) | 0.000 |

### 📊 Significant Variables

| Variable                  | Coefficient | P-value |
| ------------------------- | ----------: | ------: |
| Yield_per_Hectare_Tons    |   4.08e+06 |   0.000 |
| Farm_Size_Hectares        |   1.799e+06 |   0.000 |

### 🧪 Diagnostic Tests

| Test | Statistic | P-value |
| ---- | --------: | ------: |
| Jarque–Bera | 608.94 | 5.89e-133 |
| Breusch–Pagan LM | 289.90 | 3.61e-57 |
| Breusch–Pagan F | 37.48 | 6.83e-62 |

### Interpretation

Higher productivity levels and larger farm sizes significantly increased farm profitability.

Evidence of heteroskedasticity was detected, which is common in agricultural income models.

## 🏛️ Objective 4: Institutional Access and Productivity

## 📌 Institutional Variables Included

- Credit_Access
- Extension_Access
- Cooperative_Membership
- Training_Attendance_Days
- Irrigation_Access

### 📈 Institutional Access Regression Results

| Metric | Value |
| ------ | ----: |
| R-squared | 0.085 |
| Adjusted R-squared | 0.082 |
| F-statistic | 36.87 |
| Prob (F-statistic) | 0.000 |

### 📊 Significant Variables

| Variable                     | Coefficient | P-value |
| ---------------------------- | ----------: | ------: |
| Credit_Access                |      0.3969 |   0.000 |
| Training_Attendance_Days     |      0.0258 |   0.036 |
| Irrigation_Access            |      0.3838 |   0.000 |

### 🧪 Diagnostic Tests

| Test | Statistic | P-value |
| ---- | --------: | ------: |
| Jarque–Bera | 8.39 | 0.015 |
| Breusch–Pagan LM | 1.81 | 0.875 |
| Breusch–Pagan F | 0.36 | 0.875 |

### Interpretation

Farmers with access to credit, irrigation facilities, and agricultural training achieved significantly higher productivity levels.

## 🛒 Objective 5: Market Participation and Marketed Surplus

### 📌 Dependent Variable

- Marketed_Surplus_KG

### 📈 Market Participation Regression Results

| Metric | Value |
| ------ | ----: |
| R-squared | 0.980 |
| Adjusted R-squared | 0.980 |
| F-statistic | 12100 |
| Prob (F-statistic) | 0.000 |

### 📊 Significant Variables

| Variable                  | Coefficient | P-value |
| ------------------------- | ----------: | ------: |
| Farm_Size_Hectares        |      5169.07 |   0.000 |
| Market_Access_Score       |      -141.62 |   0.011 |
| Yield_per_Hectare_Tons    |   1.227e+04 |   0.000 |

### 🧪 Diagnostic Tests

| Test | Statistic | P-value |
| ---- | --------: | ------: |
| Jarque–Bera | 440.56 | 2.15e-96 |

### Interpretation

Farm size and productivity strongly increased marketed surplus among farmers, indicating that more productive farmers participate more actively in agricultural markets.

## 📉 Econometric Diagnostics Summary

- ✔ Strong model fit across major regressions
- ✔ Acceptable multicollinearity after refinement
- ✔ Mostly stable residual distributions
- ✔ Realistic heteroskedasticity in profitability models
- ✔ Structurally meaningful economic relationships

## 🔬 Key Contributions of the Project

This project demonstrates:

- Agricultural econometric modeling
- Structural dataset engineering
- Regression diagnostics
- Productivity analysis
- Profitability modeling
- Institutional economics analysis
- Market participation analysis
- Applied data science for agriculture

## 🛠️ Tools and Libraries

- pandas
- numpy
- statsmodels
- scipy
- matplotlib
- seaborn

## 📁 Project Structure

├── data/
│   └── agricultural_dataset.csv
├── notebooks/
│   └── agricultural_analysis.ipynb
├── outputs/
│   ├── tables/
│   ├── regression_results/
│   └── visualizations/
├── README.md
└── requirements.txt
