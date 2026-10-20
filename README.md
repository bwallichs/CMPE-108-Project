# Predicting How SJSU Students Commute: Analysis of Machine Learning Accuracy and Fairness

**CMPE 108 – AI, Data Engineering, and Ethics (Fall 2026)**
Brian Wallichs & Seline Venzon

## Overview
SJSU is mostly a commuter campus, and students get to school in different ways
depending on distance, housing, and financial means. This project trains machine
learning models to predict a student's primary commute mode (drive, carpool,
transit, walk, bike) and tests whether the models perform equally well across
student groups such as income level, age, and gender.

## Data
- **Current:** 2017 National Household Travel Survey (NHTS), filtered to school trips
- **Requested:** Anonymized response-level data from SJSU Transportation Solutions
- Raw data files are not stored in this repo because of their size.

## Pipeline
load_data → clean → train → evaluate → fairness

## Models
- Logistic regression (baseline)
- Decision tree

## Repository Structure
- `data/` – raw data (not uploaded)
- `notebooks/` – data exploration
- `src/` – pipeline code
- `results/` – tables and charts for the report
