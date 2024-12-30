# -Task-1--Titanic-Survival-Prediction

## Project Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. By analyzing passenger data such as age, gender, ticket class, and fare, we build a predictive model to classify survival outcomes with high accuracy.

## Dataset Details
The Titanic dataset contains information about passengers, including:

- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Gender
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

This data is preprocessed to handle missing values and normalize features for effective model training.


## Approach
1. **Data Preprocessing**:
   - Handled missing values for features like `Age` and `Embarked`.
   - Encoded categorical variables such as `Sex` and `Embarked`.
   - Standardized numerical features for better model performance.

2. **Feature Selection**:
   - Selected key features (`Pclass`, `Sex`, `Age`, `Fare`, etc.) based on their correlation with survival.

3. **Model Building**:
   - Trained multiple machine learning models, including:
     - Logistic Regression
     - Random Forest Classifier
     - Gradient Boosting Classifier
   - Evaluated models using accuracy, precision, recall, and F1-score.

4. **Model Evaluation**:
   - Selected the best-performing model based on evaluation metrics.
   - Fine-tuned hyperparameters for optimal performance.


## Results
The final model achieved an accuracy of ****1.00%**** on the test set. Other metrics include:

- **Precision**: 1.00%
- **Recall**: 1.00%
- **F1-score**: 1.00%

The Random Forest Classifier was identified as the best model due to its robust performance across all metrics.

## Challenges Faced
- Handling missing values in the `Age` and `Cabin` features.
- Balancing the dataset to address class imbalance.
- Hyperparameter tuning for improving model accuracy.

To address these challenges, techniques such as imputation, feature engineering, and cross-validation were used.
