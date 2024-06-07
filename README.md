This data set contains 416 liver patient records and 167 non liver patient records
This data set contains 441 male patient records and 142 female patient records
Columns:
Age of the patient,Gender of the patient,Total Bilirubin,Direct Bilirubin,Alkaline Phosphotase,Alamine Aminotransferase,Aspartate Aminotransferase,Total Protiens,Albumin,Albumin and Globulin Ratio
libraries
**import pandas as pd**
**import numpy as np**
**import seaborn as sns**
import matplotlib.pyplot as plt
The data set contain missing values to remove it,used mean or median of the features.
The data set contain multi-collinearity thus the percet above 0.87 is removed
Multicollinearity betwwen **'Total_Bilirubin'** and **'Direct_Bilirubin'** is **0.87%**
We use SMote technique(Synthetic Minority Over-sampling Technique)
