# PIVUS Metabolomics Classification Analysis

This project involves a comparative analysis of machine learning algorithms applied to the **MTBLS90 human serum metabolomics dataset** from the PIVUS study. The primary goal is to **create prediction models** for classifying samples based on sex and to **identify the most significant metabolites** contributing to that separation.

---

## Setup and Execution

To run the full analysis and reproduce the results, follow these steps:

### 1. Clone Base Repository
The analysis relies on a pre-existing environment and structure. Clone the base Git repository to your local system:

    git clone https://github.com/griffithlab/DeepSVR/

### 2. Copy Source Files
Copy the necessary analysis notebooks from this repository's source directory  
`Comparing ML algo performnce - McDonnell Genome Institute (MGI) Dataset/source`  
into the root of the newly cloned DeepSVR folder (the same location where the Data folder is present).

Files to copy:

- Random Forest.ipynb
- Gradient Boosting.ipynb
- Features Comparison.ipynb

### 3. Run Analysis
Execute the notebooks in the following sequence:

1. Run Random Forest.ipynb  
2. Run Gradient Boosting.ipynb  
3. Run Features Comparison.ipynb  
   (This notebook compares the results and features from the first two.)

---

## Methods and Results

### Algorithms Used
The analysis compares the performance of several key machine learning algorithms for binary classification:

- Support Vector Machine (SVM)
- Random Forest (RF)
- Principal Component Regression (PCR)
- Gradient Boosting

A detailed description of all algorithms, preprocessing (log transformation, Z-scale, kNN imputation), cross-validation, performance metrics, and biological interpretation is included in the report.

All methods and detailed results are available in the **PIVUS_report_.pdf** file.
