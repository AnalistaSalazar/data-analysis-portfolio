Cancer Dataset Analysis & Power BI Dashboard
📌 Project Overview

This repository contains the cancer dataset (cancer.csv) sourced from  Kaggle. It includes clinical measurements used to study breast cancer characteristics and distinguish between malignant and benign tumors. 

The goal of this project is to explore and analyze the dataset and build an interactive dashboard in Power BI that summarizes key insights, visualizes feature distributions, and supports decision-making through compelling visual analytics.

🧠 Dataset Description

The dataset primarily relates to a breast cancer diagnostic dataset originally from the Breast Cancer Wisconsin (Diagnostic) Data Set hosted on Kaggle and the UCI Machine Learning Repository. It contains clinical measurements computed from digitized images of breast tissue to classify tumors as malignant (cancerous) or benign (non-cancerous). 


Typical properties include:

✔️ id: Unique identifier for each sample.

✔️ diagnosis: Target variable; indicates whether the tumor is Malignant (M) or Benign (B).

✔️ Multiple feature columns: Numerical measurements such as:

Mean values of features like radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, fractal dimension.

Standard Error (_se) values for these features.

Worst (largest) observed values for these features (e.g., radius_worst, texture_worst, etc.).

📌 This dataset usually contains ~569 records with 30+ descriptive measurements per record. 

❗ Disclaimer: box and whisker chart made by Jan-Peter Posthuma doesn't allow to keep a preset order on how columns are shown, that's why some charts are M/B and other are B/M


🧬 Dataset

Source: Kaggle — Cancer.csv https://www.kaggle.com/code/alexisbcook/creating-your-own-notebooks/data

Data Type: Numeric measurements from digital breast mass images


📍 Key variables:

Variable	Meaning
Radius	Average radius of the mass
Perimeter	Boundary length
Concavity	Degree of indentations in the contour
Concave points	Number of concave portions
Smoothness	Surface texture consistency
Symmetry	Shape symmetry
Diagnosis	Target class (Benign/Malignant)

🛠 Data cleaning included fixing numeric parsing issues during import.

📊 Dashboard Insights

Visual components include:

✔ Boxplots by diagnosis type
✔ Stacked bar comparisons
✔ Statistical indicators (mean/median)

🔎 Key Findings

Malignant tumors show:

❗ More irregular borders

❗ Lower smoothness and symmetry

❗ More concave deformation

➡ These traits reflect typical invasive cancer behavior

“Tumor geometry serves as a crucial indicator for breast cancer identification”.

🚀 Conclusions

✔ Morphological structure strongly correlates with diagnosis
✔ Concavity-based features are most impactful in classification
✔ Power BI enhances interpretability of medical patterns


