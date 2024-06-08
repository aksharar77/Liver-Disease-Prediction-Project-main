**Dataset Overview:**

Contains 416 liver patient records and 167 non-liver patient records.
Comprises 441 male patient records and 142 female patient records.

**Columns:**

Age of the patient,
Gender of the patient,
Total Bilirubin,
Direct Bilirubin,
Alkaline Phosphotase,
Alamine Aminotransferase,
Aspartate Aminotransferase,
Total Proteins,
Albumin,
Albumin and Globulin Ratio

**Libraries Used:**

import pandas as pd,
import numpy as np,
import seaborn as sns,
import matplotlib.pyplot as plt

**Data Preprocessing:**

Missing Values: The dataset contains missing values which were handled by using the mean or median of the respective features.
Multicollinearity: Identified and addressed multicollinearity by removing features with a correlation coefficient above 0.85. Multicollinearity between 'Total Bilirubin' and 'Direct Bilirubin' is 0.87%.

**Data Balancing Technique:**

Utilized SMOTE technique (Synthetic Minority Over-sampling Technique) for addressing class imbalance.

**Ensemble Techniques:**

Ensemble techniques can enhance predictive performance by combining the predictions of multiple models.
Ensembles can improve generalization by reducing overfitting. This approach is particularly beneficial when facing noisy or uncertain data, as it can increase robustness and reliability.
Used RandomForest classifier to predict liver disease and no liver disease.

**Feature Selection:**

SelectKBest algorithm is particularly useful in situations where the dataset contains a large number of features. It helps reduce dimensionality while retaining the most informative features, improving model performance, reducing training time, and mitigating the risk of overfitting.
Performance Evaluation:

**Performance** was evaluated using a confusion matrix to assess the accuracy of the model predictions. The confusion matrix helps in understanding the model's performance by highlighting true positives, true negatives, false positives, and false negatives.




