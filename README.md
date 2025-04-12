# Heart Stroke Prediction

This project aims to predict the likelihood of a heart stroke based on various health and demographic factors using machine learning techniques. The dataset used for this project is the **Healthcare Dataset Stroke Data**.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

---

## Overview

The project involves:
- Data preprocessing and cleaning.
- Exploratory Data Analysis (EDA) to understand the relationships between features.
- Training a Logistic Regression model to predict stroke occurrences.
- Evaluating the model's performance using metrics like accuracy, F1 score, and confusion matrix.

---

## Dataset

The dataset used is `healthcare-dataset-stroke-data.csv`, which contains the following features:
- **id**: Unique identifier (dropped during preprocessing).
- **gender**: Male, Female, or Other.
- **age**: Age of the patient.
- **hypertension**: 0 if no hypertension, 1 if hypertension.
- **heart_disease**: 0 if no heart disease, 1 if heart disease.
- **ever_married**: Yes or No.
- **work_type**: Type of work (e.g., Private, Self-employed, etc.).
- **Residence_type**: Urban or Rural.
- **avg_glucose_level**: Average glucose level in the blood.
- **bmi**: Body Mass Index.
- **smoking_status**: Smoking habits (e.g., never smoked, formerly smoked, etc.).
- **stroke**: Target variable (1 if stroke occurred, 0 otherwise).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/heart-stroke-prediction.git
   cd heart-stroke-prediction
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the dataset `healthcare-dataset-stroke-data.csv` is in the project directory.

---

## Usage

1. Open the Jupyter Notebook `HEART STROKE PREDICTION1.ipynb` in your IDE (e.g., Visual Studio Code or Jupyter Lab).
2. Run the cells step by step to:
   - Load and preprocess the data.
   - Perform exploratory data analysis.
   - Train and evaluate the Logistic Regression model.
3. View the visualizations and model evaluation metrics.

---

## Features

- **Data Preprocessing**:
  - Dropping irrelevant columns.
  - Handling missing values (e.g., replacing missing BMI values with the mode).
  - Encoding categorical variables (e.g., gender, smoking status).

- **Exploratory Data Analysis (EDA)**:
  - Correlation heatmaps.
  - Count plots for categorical variables.
  - KDE plots and scatter plots for continuous variables.

- **Model Training**:
  - Logistic Regression model trained on scaled features.
  - Train-test split with an 80-20 ratio.
  - 

- **Model Evaluation**:
  - Accuracy score.
  - Confusion matrix visualization.
  - Metrics like F1 score, Mean Squared Error (MSE), and R² score.


---

##RESULTS(CHARTS)
![038055f1a3f04fb084afa8dad![4edac02fd52b4e6ab49d04e6088babe5](https://github.com/user-attachments/assets/e50e4e47-0dc0-453f-b800-8cc38f98b5d6)
3292f76](https://github.com/user-attachments/assets/7a5fe920-97b4-4a03-870c-3309d55a90fe)
![11b8994efdaa45ca9b129c734c92813e](https://github.com/user-attachments/assets/230bee8c-816f-4f73-a069-9c17425f1af0)
![f6b2618ebcd046dea055aed9afead735](https://github.com/user-attachments/assets/ef45be07-1a0d-473a-854e-344b65f27885)
![5ffd8198ec08413ab7bade823f376418](https://github.com/user-attachments/assets/021a4f66-a3e6-4afe-9336-732cd2f3c8c1)
![a77b781dc6c246879bb2e43318d69b9e](https://github.com/user-attachments/assets/90c0a870-ddb4-4111-8321-37df1903ece1)
![a77b781dc6c246879bb2e43318d![e975cdcbb25b4f2088aa12f6e3f06e82](https://github.com/user-attachments/assets/69330e8b-ae0e-434a-a5dc-0e685fbc0b70)
69b9e](https://github.com/user-attachments/assets/1ec42043-218b-4c38-93c6-0997e4de02d2)

---

## Model Evaluation 


- **Accuracy**: 58.33%
- **Confusion Matrix**: Visualized using heatmaps.
- **Additional Metrics**:
  - F1 Score
  - Mean Absolute Error
  - Mean Squared Error
  - R² Score

---

## Conclusion

The Logistic Regression model achieved an accuracy of **58.33%**. Key insights from the analysis include:
- Stroke likelihood is influenced by factors like age, hypertension, heart disease, and BMI.
- Non-smokers showed higher chances of stroke, which requires further investigation.
- Features like marital status, residence type, and work type also impact stroke likelihood.

---

## Future Work

- Experiment with other machine learning models (e.g., Random Forest, SVM).
- Perform hyperparameter tuning to improve model performance.
- Investigate peculiar findings (e.g., non-smokers having higher stroke chances).

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



