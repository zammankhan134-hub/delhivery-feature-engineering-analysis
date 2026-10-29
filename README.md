# Delhivery Logistics Data Analysis — Root Cause Analysis & Feature Engineering

A Python-based data analytics project exploring logistics operations using the Delhivery dataset. The project examines delivery performance, route behavior, actual versus estimated operational metrics, and potential causes of delivery variability.

## Project Overview

The goal of this project is to use data analytics techniques to understand logistics performance and identify patterns that may help improve transportation planning and operational efficiency.

## Objectives

- Inspect and preprocess logistics data.
- Analyze missing values, duplicates, data types, and numerical summaries.
- Explore delivery-time distributions, route types, and potential outliers.
- Compare actual delivery time and distance with OSRM estimates.
- Examine relationships between numerical operational variables.
- Engineer time-based and geographic features from available fields.
- Aggregate segment-level records into trip-level summaries.
- Apply categorical encoding, numerical standardization, and hypothesis-testing techniques.
- Summarize operational insights and recommendations.

## Tools & Techniques

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Exploratory Data Analysis (EDA)
- Data preprocessing and quality checks
- Feature engineering
- Trip-level aggregation
- Correlation analysis and outlier detection
- Hypothesis testing with t-tests
- One-hot encoding and standardization with scikit-learn

## Main Observations Reported

- Actual delivery times show substantial variability, including unusually long durations.
- Actual delivery time tends to increase with estimated delivery time.
- Actual and OSRM-estimated distances show a strong positive relationship, with some deviations.
- Comparing actual and estimated operational metrics can help identify trips or routes that merit further investigation.
- Time-based features, state extraction, and trip-level aggregation help organize the data for operational analysis.

These are exploratory observations from the accompanying report, not proof that any single factor caused delays. The report should be consulted for the analysis and statistical output.

## Recommendations Discussed

- Monitor routes and trips with unusually long delivery durations.
- Improve delivery-time estimates by considering real-world operational conditions.
- Review route deviations and transportation planning.
- Improve warehouse coordination and shipment scheduling.
- Consider predictive analytics for forecasting delivery delays.

## Project Report

The full 70-page report, including analysis descriptions, code screenshots, visualizations, hypothesis-testing sections, and recommendations, is available here:

[**Read the Delhivery Feature Engineering Report (PDF)**](Delhivery_Feature_Engineering_Report.pdf)

## Important Notes

- This repository contains the project report. Add the original notebook or source code separately if you want others to reproduce the analysis.
- Statistical conclusions should be interpreted in the context of the test assumptions and the exact implementation used.
- Do not upload credentials, API keys, or private/company-confidential data.
