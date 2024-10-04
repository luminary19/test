# Profound Hypotension Patient Cohort Analysis

## Student Name: 
[Duc Minh Hoang]
## Student ID:
[1521988]

## Assignment: 
[Assignment 2: Cohort characterisation and clustering]

---
## Dataset Description

The dataset consists of ICU patients who experienced profound hypotension. There are 5106 rows/patients in this dataset, with the following columns:
- “ID”: Patient de-identified number;
- “anchor_age”: Age of the patient (years);
- “gender”: F for female and M for male;
- “dod”: Date of Death (if empty means survived - patient outcome variable);
- “apsiii”: Severity of illness score;
- “LoS”: Length of stay in ICU (days - patient outcome variable);
- “charlson_comorbidity_index”: Co-morbidity index.

---
## Problem Description

In this assignment, we explore the cohort of profound hypotension patients in the ICU with the following goals:
- Summarize the key characteristics of the cohort using descriptive statistics.
- Visualize the distribution of patient age, comorbidity index, APSIII scores, and length of stay.
- Perform K-Means Clustering to identify clusters of patients and assess whether they have clinical meaning.
- Identify the properties of patient clusters and whether they relate to the patients' clinical outcomes.

---

## Instructions for Setting Up the Environment

To successfully run the provided Jupyter Notebook, you need to create a Python environment with the necessary dependencies.

1. Download the `hypotension_patients.csv` dataset and the submission notebook.
   
2. **Create a virtual environment**:
    ```bash
    python3 -m venv env
    ```

3. **Activate the virtual environment**:
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```
   - On Windows:
     ```bash
     .\\env\\Scripts\\activate
     ```
4. **Install Jupyter Notebook**:
   ```bash
   pip install jupyter
   ```
6. **Install required libraries**:
   You can install the necessary packages by running the following command:
   ```bash
   pip install -r requirements.txt
   ```

7. **Launch jupyter notebook**:
    ```bash
   jupyter notebook
   ```
8. **Upload and open file:**
   Upload the submission notebook using the upload button in Jupyter Notebook, then open it by double-clicking.

## Useful Resources

1. **Pandas Documentation**: [Pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html)
2. **Matplotlib Documentation**: [Matplotlib Guide](https://matplotlib.org/stable/users/index.html)
3. **Seaborn Documentation**: [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
4. **K-Means Clustering Explanation**: [K-Means Clustering Overview](https://scikit-learn.org/stable/modules/clustering.html#k-means)
5. **Principal Component Analysis (PCA) Explanation**: [PCA Overview](https://scikit-learn.org/stable/modules/decomposition.html#pca)
