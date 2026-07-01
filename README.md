# Advertisement Effectiveness Analysis using A/B Testing

## Overview

This project analyzes the effectiveness of an online advertising campaign using A/B testing. The objective is to determine whether displaying advertisements results in a statistically significant increase in user conversions compared to Public Service Announcements (PSA).

The analysis covers exploratory data analysis, conversion behavior, statistical hypothesis testing, confidence interval estimation, and business recommendations.

---

## Problem Statement

Businesses invest heavily in digital advertising, but it is essential to verify whether advertisements actually improve conversion rates.

This project answers:

- Do advertisements increase conversions?
- Is the observed improvement statistically significant?
- What is the expected business impact?
- Should the advertisement strategy be deployed?

---

## Dataset

The dataset contains user-level experiment data including:

- Experiment Group (Advertisement / PSA)
- Conversion Status
- Day of Week
- Hour of Day
- Number of Advertisements Viewed
- Total Advertisements Served

---

## Project Workflow

### 1. Data Cleaning
- Removed inconsistencies
- Checked missing values
- Prepared experiment groups for analysis

### 2. Exploratory Data Analysis
- Experiment group distribution
- Conversion rates by group
- Day-wise conversion analysis
- Hour-wise conversion trends
- Advertisement exposure analysis
- Total advertisement distribution

### 3. Statistical Analysis
- Two-Proportion Z-Test
- Hypothesis testing
- p-value interpretation
- 95% Confidence Interval for conversion lift

### 4. Business Recommendation
Translate statistical findings into actionable business decisions.

---

## Key Findings

- Advertisement group achieved a higher conversion rate than PSA.
- **Absolute Conversion Lift:** **0.77 percentage points**
- **Relative Improvement:** **43.09%**
- The improvement is **statistically significant (p < 0.05)**.
- **95% Confidence Interval:** **0.59% – 0.94%**, indicating a consistently positive treatment effect.

---

## Business Recommendation

The A/B test demonstrates that advertisements significantly outperform the PSA campaign.

**Recommendation:**

- Deploy the advertisement strategy.
- Continue monitoring long-term conversion performance.
- Run future experiments to optimize advertisement frequency and delivery timing.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels

---

## Statistical Methods

- Exploratory Data Analysis (EDA)
- Conversion Rate Analysis
- Two-Proportion Z-Test
- Confidence Interval Estimation
- A/B Testing

---

## Project Structure

```
├── ADS-AB-testing.ipynb
├── README.md
```

---

## Skills Demonstrated

- Experimental Design
- A/B Testing
- Statistical Hypothesis Testing
- Business Analytics
- Data Visualization
- Conversion Funnel Analysis
- Python Data Analysis
