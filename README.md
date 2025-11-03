# Abstract

This study predicts wine quality using machine learning on the **UCI Wine Quality Dataset** (Cortez et al., 2009), containing **1,599 red wine samples** and **11 physicochemical features** such as acidity, sulphates, and alcohol content.  

In this work, the same dataset was processed using an **automated PyCaret pipeline** with z-score normalization and feature selection to reduce multicollinearity. Multiple models were evaluated, and a **Voting Classifier** combining top performers (**Extra Trees Classifier**, **Random Forest**, **LightGBM**) achieved:  

- **Accuracy:** 89.9%  
- **AUC:** 0.98  
- **Kappa:** 0.84  

These results confirm that ensemble learning, when combined with proper preprocessing, can accurately replicate expert sensory assessments of wine quality and provide valuable support for automated quality control in the wine industry.  

**Project Link (Sheridan College SharePoint):**  
<https://sheridanc-my.sharepoint.com/:v:/g/personal/morrthom_shernet_sheridancollege_ca/Ec755RUIkMFJloMxfe81DfcBcOuBRWwe7pshFQOyEHm-yw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=ZtHy16>
