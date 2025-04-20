
# The Critical Influence of Air Pollution and Socioeconomic Status on Cardiovascular Mortality Rates in the U.S.


## Overview

This project investigates the intersection of air pollution,specifically particulate matter 2.5 (PM2.5) and socioeconomic status (SES) on cardiovascular disease (CVD) mortality across U.S. states. Leveraging national datasets from 1990 to 2010, the research reveals how environmental and economic disparities contribute to significant health outcomes — with major implications for **public health policy and social justice**.

---

## Research Question

> How do air pollution and socioeconomic status interact to influence cardiovascular disease morbidity and mortality rates across U.S. states, and what are the public health and social justice implications of these disparities?

---

##  Data Sources

The analysis is based on five publicly available datasets:

- **American Community Survey (ACS) 2009–2010**  
  [Census.gov ACS Data](https://www.census.gov/data/developers/data-sets/acs-1year/2009.html)

- **PM2.5 and Cardiovascular Mortality Rate (1990–2010)**  
  [Data.gov PM2.5-CVD](https://catalog.data.gov/dataset/annual-pm2-5-and-cardiovascular-mortality-rate-data-trends-modified-by-county-socioeconomi)

- **Heart Disease Mortality by State (CDC)**  
  [CDC Heart Disease](https://www.cdc.gov/nchs/pressroom/sosmap/heart_disease_mortality/heart_disease.htm)

- **Hypertension Mortality by State (CDC)**  
  [CDC Hypertension](https://www.cdc.gov/nchs/pressroom/sosmap/hypertension_mortality/hypertension.htm)

---

## Methodology

- Cross-sectional integration of datasets (2009–2010).
- Data cleaning, engineering, and exploratory data analysis.
- Correlation and comparative analysis between PM2.5, SES, and CMR.
- Regression modelling between PM2.5, SES, and CMR

---

## Technologies Used

- Python
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `requests` – API integration
- Jupyter Notebooks
- Data from U.S. Census, EPA, CDC

---

## Key Features

- Analysis of numerous county-year records.
- No missing values in the final datasets, enabling robust statistical analysis.
- Feature engineering for:
  - Factor indexing
  - Poverty and insurance rates
  - Education attainment
- Merging datasets by FIPS codes and state codes for consistent granularity.

---

## Results Highlights

- Counties with higher PM2.5 and lower SES show significantly higher CVD mortality.


---

## Social Justice Implications

The findings highlight systemic inequalities in air quality and socioeconomic status may be disproportionately impacting low-income communities, putting them at a higher risk of cardiovascular morbidity and mortality. Policy interventions are needed to address the issues faced by such communities.

---


## How to Run

```python
# Import libraries
import numpy as np                  # Scientific Computing
import pandas as pd                 # Data Analysis
import matplotlib.pyplot as plt     # Plotting
import seaborn as sns               # Statistical Data Visualization
```

Ensure your environment has these packages installed. You can use pip or conda to install them individually based on your preference.

[Ipynb file link](https://github.com/Bayowar/CMRPM25Research/blob/3918f6d6c8186ad2ff1382b29a6f8765d0e64bf5/researchpaperdata2_0_0-2.ipynb).

Markdown file
[researchpaperdata2_0_0.md](https://github.com/Bayowar/CMRPM25Research/blob/5e440d398f12b82880548a7f590ca9815ac0075e/researchpaperdata2_0_0/researchpaperdata2_0_0.md).

[Data science portfolio](https://github.com/Bayowar/Bayowar.github.io.git)

Mentored by Prof. LaKeta Kemp
