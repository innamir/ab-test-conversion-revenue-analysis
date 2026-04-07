# A/B Test: Conversion vs Revenue Trade-off

## 📌 Project Overview

This project analyzes an A/B test to evaluate the impact of a new product feature on user behavior.

Users were randomly assigned to:
- Group A — control group
- Group B — treatment group (new feature)

The goal of the experiment is to understand how the feature affects:
- conversion
- retention
- revenue

The dataset is synthetically generated to simulate a real product scenario.

---

## 🎯 Business Goal

The main objective is to determine whether the new feature improves business performance.

We aim to answer:
- Does the feature increase user activation?
- Does it affect retention?
- Does it improve monetization (paid conversion, ARPU, ARPPU)?
- Are the effects consistent across different user segments?

---

## 📊 Key Metrics

The analysis focuses on the following metrics:

- **Activation Rate** — share of users who completed activation
- **Paid Conversion** — share of users who made a purchase
- **Retention (7-day)** — share of users who returned after 7 days
- **ARPU** — average revenue per user
- **ARPPU** — average revenue per paying user

---

## 🧪 Methodology

The analysis includes:

- Exploratory data analysis (EDA)
- Data quality checks
- Hypothesis testing:
  - Z-test for proportions (conversion metrics)
  - Mann–Whitney U test (revenue)
- Confidence intervals analysis
- Segment analysis (country, device, age)

---

## 🔍 Key Findings

- **Conversion increased** in group B (statistically significant)
- **Retention decreased**, indicating a potential negative impact on user engagement
- **Paid conversion** showed no statistically significant improvement
- **ARPPU decreased**, but the difference is not statistically significant
- Segment analysis did not reveal consistent statistically significant differences

---

## ⚖️ Business Decision

The feature shows mixed results.

While it increases conversion, it negatively affects retention and does not clearly improve revenue.

This suggests a trade-off between growth and user quality.

---

## 📌 Recommendation

A full rollout is not recommended at this stage.

Next steps:
- Continue the experiment to collect more data
- Investigate the decline in retention
- Analyze user behavior in more detail
- Evaluate long-term impact on revenue and LTV

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Jupyter Notebook

---

## 📁 Project Structure

- `ab_test_analysis.ipynb` — main analysis notebook

---
