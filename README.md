#      Craiglist Used Car Market — Data Pipeline & Analysis

This repository contains a full data science pipeline built to extract, clean, enrich, and analyze used car listings from Craiglist. The project aims to model the second-hand automotive market in the United States by combining web scraping, domain-based normalization, and exploratory data science techniques.

---

##  Project Overview

-  **Scraping**: Automated extraction of car listings across multiple Craiglist subdomains with handling of dynamic web content.
-  **Data Cleaning**: Cleaning inconsistent or incomplete fields with domain-specific rules and imputation logic.
-  **Model Normalization**: Mapping messy `makemodel` strings to a canonical structure using a reference JSON database (e.g. `{ make: [model1, model2, ...] }`).
-  **Market Analysis**: Statistical exploration and visualization of the US used car market (price distribution, location trends, supply by brand/model).
-  **Data Science**:
  - Price prediction models
  - Clustering of listings by technical and economic features
  - Anomaly detection to identify outliers or suspicious listings

---

##  Project Structure
```
craiglist-car-market/
├── data/             # Raw and cleaned datasets
├── notebooks/        # Exploratory notebooks (scraping, cleaning, EDA, ML)
├── outputs/          # Visualizations, model outputs, reports
├── README.md         # Project documentation
└── requirements.txt  # Python dependencies
```
##  Example Insights

- Top 10 most listed car models across the US
- Average price per model adjusted for mileage and region
- Detection of suspiciously underpriced listings
- Price prediction using regression models (Random Forest, XGBoost, etc.)
- K-Means clustering of listings by technical features

---
