# Email Campaign Uplift Analysis

## Overview

This project analyzes the effectiveness of an email marketing campaign using A/B testing and uplift modeling. The goal is to measure the causal impact of email campaigns on customer conversion and identify which customer segments benefit the most.

This project demonstrates industry-standard experimentation analysis used by companies like Amazon, Netflix, Uber, and Meta.

---

## Business Problem

Marketing teams often send emails to all customers without knowing which customers actually benefit from them.

This leads to:

- Inefficient marketing spend
- Lower ROI
- Customer fatigue

The objective of this project is to:

- Measure the impact of email campaigns using A/B testing
- Identify high-impact customers using uplift modeling
- Provide data-driven recommendations for targeted marketing

---

## Dataset

Dataset: Kevin Hillstrom MineThatData Email Analytics Dataset

Contains 64,000 customers with:

- Customer demographics
- Purchase history
- Email treatment assignment
- Conversion outcome

Key columns:

- `treatment` — Email received (1) or not (0)
- `conversion` — Customer purchased (1) or not (0)
- `recency` — Months since last purchase
- `history` — Customer spending history
- `channel` — Acquisition channel
- `newbie` — New or existing customer

---

## Methodology

The project follows a standard experimentation and uplift modeling workflow:

### Phase 1: Data Understanding and Preparation
- Loaded and explored experiment dataset
- Created treatment and control groups
- Verified dataset integrity

### Phase 2: A/B Test Analysis
- Calculated conversion rates
- Measured uplift
- Performed statistical significance testing
- Estimated confidence intervals

### Phase 3: Uplift Modeling
- Built T-Learner uplift model using Random Forest
- Estimated individual treatment effect
- Identified high-impact customers

### Phase 4: Segment Analysis
- Analyzed uplift across customer segments
- Identified high-response customer profiles

### Phase 5: Business Recommendation
- Provided actionable marketing strategy recommendations
- Estimated expected business impact

---

## Key Results

Control Conversion Rate: 0.57%  
Treatment Conversion Rate: 1.07%

Absolute Uplift: +0.50 percentage points  
Relative Uplift: +86.53%

Statistical Significance: p-value < 0.05 (statistically significant)

Key insight:

Email campaigns significantly increase conversion rates, but impact varies across customers.

Targeting high-uplift customers can significantly improve marketing efficiency.

---

## Business Impact

By targeting high-uplift customers instead of all customers, companies can:

- Increase conversion rates
- Improve marketing ROI
- Reduce unnecessary email costs
- Enable personalized marketing strategies

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

email-marketing-uplift/
│
├── data/
│ └── raw/
│
├── notebooks/
│ └── 01_ab_test_analysis.ipynb
|
├── README.md
└── requirements.txt


---

## Key Skills Demonstrated

- A/B Testing
- Hypothesis Testing
- Statistical Analysis
- Uplift Modeling
- Causal Inference
- Machine Learning
- Marketing Analytics
- Business Decision Making

---

## Conclusion

This project demonstrates how experimentation and uplift modeling can be used to optimize marketing strategies and improve business outcomes.

The approach enables data-driven decision making and personalized customer targeting.

---

## Author

Tej Pratap
Data Science Project — Experimentation & Uplift Modeling
