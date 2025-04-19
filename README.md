#  Titanic Exploratory Data Analysis (EDA) 

This repository contains an Exploratory Data Analysis project on the Titanic dataset from Kaggle. The aim is to uncover patterns and insights into what factors affected passenger survival.

---

## 📊 Dataset Description

The dataset includes the following files:

- `train.csv` – Training set (used for EDA)
- `test.csv` – Test set (not used in this EDA)
- `gender_submission.csv` – Sample submission file (not used here)

---


We use the “train.csv” dataset only for our analysis because that’s where the labeled data (Survived) is available for insight generation.
Here’s why we don’t use test.csv during EDA: 
•	Goal of EDA is to understand patterns in labeled data. train.csv has the Survived column — so we can explore how features like Age, Sex, Pclass, Fare etc. relate to survival. test.csv does not have the Survived column — it’s meant for predictive modeling or submission to Kaggle later.
•	We use test.csv for prediction or model validation (e.g., logistic regression, decision trees) and to generate a submission file by predicting Survived on unseen data. 
This is also why we use only train.csv and ignore test.csv and gender_submission.csv for now. 


---


## 🔍 Key Questions Explored

- How does gender, age, or class affect survival?
- Were families more likely to survive than solo travelers?
- Which features have missing data and how should we handle them?



---


## 🛠️ EDA Steps Performed

- Data Cleaning: null handling, type conversion
- Feature Engineering: `FamilySize`, `IsAlone`
- Visualizations:
  - Barplots (`Sex` vs `Survived`)
  - Boxplots (`Age` vs `Survived`)
  - Violinplots (`Fare` vs `Survived`)
  - Heatmaps (correlation matrix)


 ---


 🚀 Tools Used

 Python
