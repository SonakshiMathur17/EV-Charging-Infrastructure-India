# EV Charging Infrastructure Analytics – India

## Project Overview

This project focuses on identifying investment opportunities for electric vehicle (EV) charging infrastructure expansion across India. It uses unsupervised machine learning to segment Indian states and union territories based on EV adoption, charging infrastructure availability, market size and growth momentum.

The objective is to identify underserved markets and develop data-driven investment priorities for charging infrastructure expansion.

## Project Objectives

- Analyse state-wise EV adoption and charging infrastructure availability.
- Identify disparities between EV demand and charging station supply.
- Segment states based on their EV ecosystem characteristics.
- Identify underserved markets with infrastructure gaps.
- Develop investment priorities for EV charging infrastructure expansion.

## Dataset Overview

The analysis integrates three government-sourced datasets:

- EV Sales by State (2014–2024)
- Operational Public Charging Stations
- State Population Data

**Final Analytical Dataset:**
- 31 States and Union Territories
- 8 Engineered Features
- 0 Missing Values

## Tools & Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Principal Component Analysis (PCA)
- K-Means Clustering
- Data Visualisation
- Unsupervised Machine Learning

## Methodology

### 1. Data Collection and Integration
Combined EV sales, public charging station and population datasets using a common state-level geographic key.

### 2. Data Cleaning and Validation
Standardised state boundaries, reconciled geographic inconsistencies and validated the datasets against published government totals.

### 3. Feature Engineering
Developed eight analytical features covering:
- EV adoption intensity
- Market size
- Vehicle category composition
- Charging infrastructure density
- EV-to-charging-station ratio
- Market growth momentum

### 4. Principal Component Analysis (PCA)
Applied PCA to reduce dimensionality and address correlations among the eight engineered features.

The first three principal components retained 81.4% of the total variance.

### 5. K-Means Clustering
Applied K-Means clustering to segment states according to their EV ecosystem characteristics. Four clusters were selected by balancing clustering performance with business interpretability.

### 6. Investment Prioritisation
Translated the clustering results into investment priority scores and a four-tier action framework to support charging infrastructure expansion decisions.

## Key Analytical Areas

- State-wise EV adoption patterns
- Charging infrastructure availability
- Demand-supply imbalance
- Infrastructure coverage gaps
- EV market growth momentum
- State segmentation
- Investment opportunity prioritisation

## Project Deliverable

The repository contains the project presentation documenting the research problem, dataset integration, feature engineering, PCA, clustering methodology and investment prioritisation framework.

## Conclusion

The project demonstrates how unsupervised machine learning can support strategic infrastructure planning. By combining EV demand, charging infrastructure availability and market growth indicators, the analysis identifies differences across state-level EV ecosystems and provides a structured approach to prioritising future charging infrastructure investments.
