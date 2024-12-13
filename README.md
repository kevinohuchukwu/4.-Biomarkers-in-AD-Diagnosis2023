# Investigating the Utility of Neuroimaging Biomarkers in Early Detection and Progression Monitoring of Alzheimer's Disease
## Introduction
This research project explores the predictive effectiveness of neuroimaging biomarkers, combined with demographic ("Age" and "Sex") and genetic data, to enable early detection and progression monitoring of Alzheimer's Disease (AD). Using advanced machine learning techniques and neuroimaging data from the Alzheimer's Disease Neuroimaging Initiative (ADNI), this study aims to build predictive models that enhance clinical outcomes.
## Liat of Biomarkers
![bio](https://github.com/user-attachments/assets/8326a7da-25d2-4dd9-970c-55c4ccfc8a9f)

![image](https://github.com/user-attachments/assets/c0f99c44-4838-4d62-83ea-c804b9dfc1a7)

### Prerequisites

The tool was developed using rhe following dependencies:
*	pandas: Data manipulation and analysis (1.1.0 or greater).
*	numpy: Numerical computing (1.19.0 or greater).
*	matplotlib: Visualization (3.3.0 or greater).
*	seaborn: Statistical data visualization (0.11.0 or greater).
*	scipy: Scientific computing (1.5.0 or greater).
*	statsmodels: Statistical modeling and hypothesis testing (0.12.0 or greater).
*	scikit-learn: Machine learning algorithms and tools (0.23.0 or greater).
*	imblearn: Oversampling techniques such as SMOTE (0.8.0 or greater).
*	xgboost: Gradient boosting framework (1.3.3 or greater).
*	keras: Deep learning framework (2.4.0 or greater).
*	mpl_toolkits.mplot3d: 3D plotting toolkit for Matplotlib (bundled with Matplotlib).

### Additional Notes:
*	scikit-learn is heavily used in the code for: 
*	Classification (AdaBoostClassifier, DecisionTreeClassifier, Gradient Boosting, etc.).
*	Preprocessing (LabelEncoder, OneHotEncoder, StandardScaler).
*	Model evaluation (confusion_matrix, classification_report, silhouette_score).
*	statsmodels is used for statistical modeling (e.g., OLS regression).
*	keras provides deep learning layers like Dense and LSTM.
*	xgboost is included for advanced tree-based models.

Please note that the dependencies may require Python 3.6 or greater. It is recommended to install and maintain all packages using conda or pip.
