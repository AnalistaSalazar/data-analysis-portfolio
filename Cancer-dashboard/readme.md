Cancer Dataset Analysis & Power BI Dashboard
📌 Project Overview

This repository contains the cancer dataset (cancer.csv) sourced from a Kaggle tutorial by Alexis Cook. It includes clinical measurements used to study breast cancer characteristics and distinguish between malignant and benign tumors. 


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

❗ Disclaimer: box and whisker chart made by Jan-Peter Posthuma doesn't allow to keep a preset order on how columns are shown, that's why some charts are M/B and other are B/M

📌 This dataset usually contains ~569 records with 30+ descriptive measurements per record. 
