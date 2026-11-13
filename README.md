# Team10_PyMasters_Python-Hackathon_SEP2026 -  Hospitalized Patients with Heart Failure Dataset

# Team 10 PyMasters: Heart Failure Analysis

Analysis of 3 years of heart-failure patient data (2,008 patients): from data cleaning to descriptive, prescriptive and predictive insights.

## 1. Data Cleaning
**Notebook:** `Team10_PyMaster_1.DataCleaning.ipynb`
- Load and inspect raw data
- Handle missing values and outliers
- Generate cleaned datasets used in later analyses

**Output:** `10_pymasters_cleaned_Heartdata.csv`, `10_PyMasters_Cleaned_Prescriptions.csv`

## 2. Descriptive Analysis
**Notebook:** `Team10_PyMaster_2.DescriptiveAnalysis.ipynb`
- Explore data distributions and patterns of heart failure
- Visualize relationships between vitals, labs and readmission
- Identify basic correlations and patterns

**Includes:** 10 visual summaries and insights

## 3. Prescriptive Analysis
**Notebook:** `Team10_PyMaster_3.PrescriptiveAnalysis.ipynb`
- Analyze heart-failure patterns (admission, readmission, vitals, labs, comorbidities)
- Answer prescriptive questions, each ending in a clear recommendation
  (e.g. ward benchmarking, troponin threshold, kidney impairment, discharge destination)
- Support every decision with a chart or table

## 4. Predictive Analysis
**Notebook:** `Team10_PyMaster_4.PredictiveAnalysis.ipynb`
- Random Forest model to predict 6-month readmission, with the top 10 predictors
- Random Forest model to identify kidney impairment using only non-kidney data
- Evaluate with cross-validation and ROC-AUC, and interpret the results

## How to run
Run the notebooks in order (1 to 4). Notebook 1 creates the cleaned files that notebooks 2 to 4 use.
