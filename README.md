# Medical Cost & Health Insurance Charges Analysis

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a healthcare dataset containing demographic and health metrics to determine the primary drivers of medical insurance charges. The analysis investigates relationships between customer attributes such as age, regional location, and family size and their final annual insurance bills.

The codebase is built entirely in Python using Jupyter Notebooks, leveraging data manipulation and statistical visualization libraries to extract actionable business intelligence.

## Core Dataset
The analysis utilizes the `insurance.csv` dataset, which contains 1,338 historical patient records across the following features:
* **Demographics:** `age`, `sex`, `children` (number of dependents), `region` (US geographic zones)
* **Health Metrics:** `bmi` (Body Mass Index), `smoker` (smoking status)
* **Target Metric:** `charges` (annual individual medical costs billed by health insurance)

## Key Findings & Insights
* **The Age Bracket Impact:** There is a distinct, positive linear correlation between age and healthcare insulation costs. As an individual ages, the minimum baseline cost consistently shifts upward across all cohorts.
* **Geographic Distribution Equality:** The dataset exhibits an exceptionally balanced distribution across all four major US regions (Northeast, Northwest, Southeast, and Southwest), ensuring that regional analysis is free from sample size bias.
* **Dependent Volatility:** While overall medical costs scale with major life changes, having a higher number of children (4 or 5) does not linearly increase extreme billing spikes. Instead, maximum variance decreases due to a smaller, more uniform sample size at higher dependent counts.
* **Cost Skewness:** Annual charges are heavily right-skewed; the vast majority of insured individuals incur routine annual expenses below $15,000, while a high-risk group forms a volatile tail extending out past $40,000 to $60,000.


## Technologies & Environment

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Core Libraries:**
  * `pandas`: Data ingestion, structural manipulation, and cleaning.
  * `seaborn`: Statistical data visualization and distribution styling.
  * `matplotlib.pyplot`: Underlying plot engine customization and figure sizing.

## Getting Started & How to Run

To clone and run this project locally, follow these simple steps:

### 1. Clone the Repository
Open Git Bash (or your terminal) and run the following command to download the project folder to your computer:
```bash
git clone [https://github.com/YOUR-USERNAME/medical-cost-analysis.git](https://github.com/YOUR-USERNAME/medical-cost-analysis.git)


## Repository Structure
```text
├── README.md               # Executive project overview and summary of findings
├── medical_case_study.ipynb # Interactive Jupyter Notebook containing EDA and plots
└── insurance.csv           # Clean, raw tabular insurance dataset

