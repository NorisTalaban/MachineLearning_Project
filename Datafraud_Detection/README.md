**Introduction**  
Project for detecting fraud in credit card transactions using **XGBoost** and advanced **feature engineering**.  
The code is written **without a formal pipeline** to allow for **better readability** of each step.

**Note:** For best performance, it is recommended to use the **T4 GPU accelerator** in Google Colab when running the notebook.


- **Clean**: minimal notebook, ready to run  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NorisTalaban/MachineLearning_Project/blob/main/Datafraud_Detection/DataFraud_Clean.ipynb)

- **Tell**: detailed notebook with step-by-step comments and explanations
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NorisTalaban/MachineLearning_Project/blob/main/Datafraud_Detection/DataFraud_Tell.ipynb)

---

**Main Contents**  
- Exploratory Data Analysis (EDA) and fraud distribution  
- Preprocessing and feature creation (distance, z-score, temporal and categorical anomalies)  
- Handling imbalanced classes with SMOTE  
- XGBoost model with evaluation (F1, ROC-AUC, confusion matrix)  
- Feature importance and conclusions