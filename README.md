# Investigating the Utility of Neuroimaging Biomarkers in Early Detection and Progression Monitoring of Alzheimer's Disease
## Introduction
This research project explores the predictive effectiveness of neuroimaging biomarkers, combined with demographic ("Age" and "Sex") and genetic data, to enable early detection and progression monitoring of Alzheimer's Disease (AD). Using advanced machine learning techniques and neuroimaging data from the Alzheimer's Disease Neuroimaging Initiative (ADNI), this study aims to build predictive models that enhance clinical outcomes..

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

### Additional Notes
*	scikit-learn is heavily used in the code for: 
*	Classification (AdaBoostClassifier, DecisionTreeClassifier, Gradient Boosting, etc.).
*	Preprocessing (LabelEncoder, OneHotEncoder, StandardScaler).
*	Model evaluation (confusion_matrix, classification_report, silhouette_score).
*	statsmodels is used for statistical modeling (e.g., OLS regression).
*	keras provides deep learning layers like Dense and LSTM.
*	xgboost is included for advanced tree-based models.

Please note that the dependencies may require Python 3.6 or greater. It is recommended to install and maintain all packages using conda or pip.


## Understanding the data
Understanding the data in this context involves the following key observations and insights:
### Segregation of Data
1.	Baseline and Non-Baseline Data:
*	The dataset is divided into two distinct classifications: 
*	Baseline data: Includes 2,155 entries where the variable 'VISCODE' is 'bl'. This represents the initial condition of participants before any interventions or noticeable disease progression.
*	Non-baseline data: Contains 11,760 entries where 'VISCODE' is not 'bl', representing follow-up observations.
*	The analysis prioritizes baseline data to focus on participants' initial states.
2.	Variable Focus:
*	Key variables of interest include: 
*	AGE
*	PTGENDER
*	APOE4
*	Baseline-related measures.
### Preliminary Insights
3.	Participants:
*	The dataset comprises 2,155 unique patients, each identified by 'PTID'.
*	Among 26 visit codes, 'VISCODE' is primarily 'bl', reinforcing the emphasis on baseline data.
#### 	ADNI-2 Trial Insights:
*	The trial includes 710 participants and focuses on cognitive conditions at varying stages: 
#####  SMC (Significant Memory Concern): 
*	Participants self-reported memory issues but scored within a normal cognitive range (CDR = 0).
*	These participants showed no persistent memory loss or forgetfulness.
*	CN (Cognitively Normal): 
*	Participants with no significant cognitive impairment.
*	MCI (Mild Cognitive Impairment): 
*	Further classified into early (EMCI) and late (LMCI) subtypes.
*	Represents cognitive decline stages without severe memory loss.
  
## Purpose and Objectives
### 	Research Goals:
*	The focus is on identifying initial conditions and understanding the baseline characteristics of participants.
*	The analysis aims to: 
    *	Address potential concerns or data gaps.
    *	Generate preliminary insights.
    *	Formulate hypotheses about the dataset to support predictive modeling.
   
## Data Selection and Quality
*	The study involves careful curation of variables relevant to research objectives, ensuring irrelevant columns are removed.
*	Prioritized baseline data provides a foundation for evaluating participants' conditions at the study's onset. These insights will be integrated with neuroimaging and genetic data to 
  train machine learning models for prediction and monitoring.



