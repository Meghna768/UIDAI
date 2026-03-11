# UIDAI Aadhaar Enrollment Data Analysis
Data-driven analysis of Aadhaar enrollment patterns across Indian states using statistical normalization and exploratory data analysis.

## Project Overview

This project analyzes Aadhaar enrollment and demographic update datasets published by the Unique Identification Authority of India (UIDAI).  
The goal is to understand enrollment coverage, demographic distribution, and regional disparities across Indian states and districts.
Since raw enrollment numbers are heavily influenced by population size, the project applies normalization and statistical techniques to uncover meaningful patterns, anomalies, and trends.
The analysis highlights how demographic size, infrastructure availability, and regional characteristics influence Aadhaar enrollment behavior across India.

## Problem Statement

UIDAI releases large-scale datasets containing Aadhaar enrollment statistics across states, districts, and age groups. However, raw enrollment numbers often fail to reflect true coverage due to:

- Differences in population size
- Regional infrastructure variations
- Uneven age-group coverage
- Administrative and reporting differences

This project addresses the problem:

**How can Aadhaar enrollment data be analyzed using normalized and statistically meaningful metrics to uncover demographic patterns, detect anomalies, and generate interpretable insights for policy planning?**

## Dataset

The analysis uses the **Aadhaar Enrollment and Demographic Update dataset** published by UIDAI.

### Key Features in Dataset

- State / Union Territory
- District
- Age_0_5 – Enrollment count for children (0–5 years)
- Age_5_17 – Enrollment count for children and adolescents (5–17 years)
- Age_18_Greater – Enrollment count for adults (18+)
- Date – Enrollment/update date

  ## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

  ## Methodology

The project follows a structured data analysis pipeline:
### 1. Data Cleaning
- Removed duplicate records
- Standardized state and region names
- Handled missing values
### 2. Data Preprocessing
- Aggregated enrollment data at state and district level
- Verified dataset consistency
- Converted fields to appropriate data types
### 3. Feature Engineering
- Enrollment per Pincode
- Coverage Ratio
- Z-score normalization for anomaly detection
### 4. Spatial and Demographic Analysis
- State-level enrollment comparisons
- District-level intensity analysis
- Age-group enrollment patterns

  ## Key Insights

- Uttar Pradesh records the highest Aadhaar enrollment across all age groups.
- Azamgarh district in Uttar Pradesh shows the highest enrollment volume.
- Meghalaya shows the highest **enrollment per pincode**, indicating high infrastructure load.
- Early-child Aadhaar enrollment (0–5 age group) dominates across most states.
- Z-score based anomaly detection identifies Uttar Pradesh and Bihar as statistical outliers.
- Urbanized regions like Delhi and Gujarat show adult-heavy demographic profiles.

## Key Findings

- Enrollment disparities are largely influenced by demographic scale rather than access alone.
- High population states require increased infrastructure capacity.
- Small states require better accessibility rather than large-scale infrastructure expansion.
- Enrollment intensity varies significantly across districts and pincodes.
- Population-weighted planning is more effective than uniform national policies.

## Team Members

- Meghna Binu Menon – Computer Science (AI & Robotics)
- Madhumathi B – Computer Science (Core)
- Saroj Gautam – Computer Science (Core)
