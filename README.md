# Customer Sign-Up Behaviour & Data Quality Audit

## Overview
Data quality audit + behavioural analysis on a SaaS customer sign-up dataset. The goal was to identify data issues (missing values, duplicates, inconsistent categories) and produce actionable insights for Marketing and Onboarding.

## Deliverables
- `customer-signup-audit.ipynb` (Jupyter Notebook)
- PDF report (to be added after final revisions)

## What I did
- Loaded and profiled the dataset (types, missing values, duplicates)
- Cleaned and standardised key fields (plan_selected, gender, source, marketing_opt_in)
- Converted `signup_date` to datetime and created weekly sign-up summaries
- Produced aggregations by source, region, plan, gender, and age
- Answered business questions on acquisition, data gaps, opt-in behaviour, and plan preferences
- Optional stretch: joined support tickets to measure early support demand (within 2 weeks)

## Key Findings (high level)
- Identified top acquisition channels and plan selection patterns
- Found incomplete region values (classified as “Unknown”)
- Measured marketing opt-in rates by age band and demographics
- Quantified early support contact rate and support activity by plan/region

## Tech Stack
- Python
- Pandas, NumPy
- SciPy
- Jupyter Notebook

## How to run
```bash
pip install -r requirements.txt
jupyter notebook

