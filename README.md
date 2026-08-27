# Startup Profit Analysis — Power BI & Regression

An end-to-end analytics project analyzing startup profitability in relation to R&D, Marketing, and Administration spending, combining Power BI visualization with Linear Regression for predictive analysis.

## Project Overview

The project analyzes startup expenditure and profitability across New York, California, and Florida.

The main objectives were to:

- Analyze the relationship between startup spending and profit
- Compare profitability across states
- Identify which spending category has the strongest relationship with profit
- Build a Linear Regression model to predict profit
- Evaluate the performance of the regression model
- Generate profit predictions for new investment scenarios
- Present the analysis through an interactive Power BI dashboard
- Provide business recommendations based on the findings

## Dataset

The dataset contains **50 startups** with the following variables:

- R&D Spend
- Administration Spend
- Marketing Spend
- State
- Profit

**Target variable:** Profit

## Tools & Technologies

- Power BI
- Orange
- Linear Regression
- 5-Fold Cross Validation

## Analysis Workflow

### 1. Exploratory Analysis

The startup data was analyzed to understand the relationship between different expenditure categories and profitability.

The Power BI dashboard includes:

- Total Profit
- Total Marketing Spend
- Total Administration Spend
- Total R&D Spend
- Profit by State
- Spending vs Profit analysis
- State-level filtering

### 2. Power BI Dashboard

The dashboard provides an interactive overview of startup profitability and expenditure.

![Power BI Dashboard](Power%20BI%20Dashboard.png)

### 3. Linear Regression

A Linear Regression model was developed using:

**Features**
- R&D Spend
- Administration Spend
- Marketing Spend

**Target**
- Profit

The model was evaluated using **5-fold cross validation**.

![Regression Workflow](Orange%20Workflow.png)

### 4. Model Evaluation

The regression model achieved:

- **R² = 0.943**
- **RMSE ≈ 9,538**
- **MAPE ≈ 11.45%**

An R² of 0.943 indicates that the model explains approximately 94.3% of the variation in startup profit within this dataset.

![Model Evaluation](Test%20%26%20Score%20Screenshot.png)

### 5. Profit Prediction

The trained model was used to generate profit predictions for the investment scenarios provided in the analysis.

| R&D Spend | Administration Spend | Marketing Spend | Predicted Profit |
|---:|---:|---:|---:|
| 21,892.92 | 81,910.77 | 164,270.70 | 70,037.90 |
| 23,940.93 | 96,489.63 | 137,001.10 | 70,554.57 |

![Profit Predictions](Regression%20Profit%20Prediction%20for%20Mentioned%20Inputs.png)

## Key Findings

- R&D Spend showed the strongest positive relationship with Profit.
- Marketing Spend showed a positive relationship with Profit.
- Administration Spend showed a comparatively weaker relationship with Profit.
- New York generated the highest total profit among the three states analyzed.
- The regression model produced an R² of 0.943 on the evaluation performed.

## Business Recommendations

Based on the analysis:

- Prioritize R&D investment when evaluating opportunities for increasing profitability.
- Evaluate marketing expenditure based on its contribution to profit.
- Review administrative expenditure for potential efficiency improvements.
- Use predictive analysis as an additional input when evaluating future investment scenarios.

## Project Files

- `Startup-Profit-Analysis Power BI.pbix` — Power BI report
- `Startup-Profit-Analysis Regression Analysis.ows` — Orange regression workflow
- `Power BI Dashboard.png` — Power BI dashboard screenshot
- `Orange Workflow.png` — Regression workflow screenshot
- `Test & Score Screenshot.png` — Model evaluation results
- `Regression Profit Prediction for Mentioned Inputs.png` — Prediction output

## Project Outcome

This project demonstrates an end-to-end analytics workflow combining **exploratory analysis, data visualization, statistical modeling, model evaluation, prediction, and business recommendations**.
