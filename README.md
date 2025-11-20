
# **Diabetes Numerical Preprocessing & Visualization Project**

This project performs complete preprocessing of the **Diabetes dataset**, including exploratory analysis, missing value imputation, visualization, and feature scaling using multiple techniques.
All steps strictly follow the assignment requirements.

---

## **📌 Project Structure**

```
Diabetes_Assignment_Package/
│
├── Diabetes_Preprocessing_Assignment_full.ipynb     # Complete Jupyter Notebook
│
├── Diabetes_outputs/                                # Generated outputs
│   ├── diabetes_standard_scaled.csv
│   ├── diabetes_minmax_scaled.csv
│   ├── diabetes_robust_scaled.csv
│   ├── plots_before_imputation/
│   ├── plots_after_imputation/
│   ├── plots_scaling/
│   └── other visual outputs
│
└── Diabetes_Assignment_Package.zip                  # Packaged submission
```

---

## **Assignment Coverage**

### **PART 1 – Data Understanding**

* Loaded dataset (`diabetes_data.csv`)
* Displayed:

  * First 5 rows
  * Shape
  * Data types
  * Summary statistics
  * Missing value counts
* Identified numerical features requiring preprocessing.

---

### **PART 2 – Missing Value Imputation**

For every numerical column with missing values:

* Distribution analyzed
* Best technique chosen (Mean, Median, Mode)
* 2–3 lines justification provided
* Missing values imputed accordingly

---

### **PART 3 – Before & After Imputation Visualization**

For each imputed column:

* Histogram before imputation
* Histogram after imputation
* Observations on:

  * Distribution shift
  * Impact on outliers
  * Whether chosen method was appropriate
  * Improvement in data consistency

---

### **PART 4 – Feature Scaling**

Three scaling techniques applied:

* **StandardScaler**
* **MinMaxScaler**
* **RobustScaler**

Created three new DataFrames:

* `standard_scaled_df`
* `minmax_scaled_df`
* `robust_scaled_df`

---

### **PART 5 – Before & After Scaling Visualization**

For each scaling method:

* Distribution before scaling
* Distribution after scaling
* Observations comparing:

  * Range compression (MinMax)
  * Variance normalization (StandardScaler)
  * Outlier robustness (RobustScaler)

---

### **PART 6 – Saving Scaled Outputs**

Saved the following CSV files:

* `diabetes_standard_scaled.csv`
* `diabetes_minmax_scaled.csv`
* `diabetes_robust_scaled.csv`

---

## **Tools & Libraries Used**

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## **How to Run**

1. Extract the ZIP file.
2. Open the notebook:

   ```
   Diabetes_Preprocessing_Assignment_full.ipynb
   ```
3. Run all cells sequentially.
4. Outputs will be generated inside the `Diabetes_outputs/` folder.

---

## **Final Submission Includes**

* Jupyter Notebook
* All visualizations
* All scaled datasets
* ZIP file containing complete package

---
