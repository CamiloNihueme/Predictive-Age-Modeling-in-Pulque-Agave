Predictive Age Modeling in Pulque Agave

A comprehensive Data Science and Machine Learning project designed to predict crop age using remote sensing data and georeferenced physical variables.

This repository demonstrates the transition from raw agricultural field data to high-precision predictive assets, optimized for industrial and enterprise-scale management.

## Business and Technical Vision
In the agricultural technology sector, predicting plant development and monitoring vegetation health using remote sensing is fundamental for optimizing yield and resource allocation. This project develops a reliable system that combines spatial coordinates and multispectral indices to provide accurate age classifications and validated information across different crop fields.

## Project Architecture
The development is structured in three phases:
1. Exploratory Data Analysis (EDA): Identifying patterns, class distributions, and feature behavior across different fields using spatial and spectral data.

2. **Predictive Modeling:** Architecture and training of leading machine learning candidates, using optimized classification algorithms.

3. **Robust Validation:** Comprehensive performance evaluation (Accuracy, Balanced Accuracy, F1 Macro) structured by field (*property*) to ensure generalizability and combat overfitting.

--

## Technologies and Methods
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
- **Key Concepts:** Remote Sensing, Spatial Data Analysis, Multiclass Classification, Cross-Validation.

---
## Key Information and Performance
* **Managed Class Distribution:** Effectively manages the age boundaries of multiple classes (e.g., '0-5', '6-9', '10-15'), ensuring balanced evaluations.

* **Production Ready:** Features a clean data export architecture that delivers final predictions in structured business formats (CSV/Excel).

* **Geographically Independent:** Independently validated across different land areas (*properties*) to ensure the model remains robust regardless of geographic changes. Furthermore, it is being improved by adding more properties to create a more robust and stable model under varying conditions.

--

## How to navigate this project
All development phases are thoroughly documented in the `notebooks/` directory. You can review the logic step by step, from data ingestion to rigorous model validation.

*For business inquiries or technical collaboration on AgTech solutions, please feel free to contact us.
