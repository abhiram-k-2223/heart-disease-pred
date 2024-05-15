# Heart Disease Prediction

This project focuses on predicting the presence of heart disease in individuals using machine learning algorithms. Two classification models, logistic regression and decision tree classifier, are implemented and compared based on their accuracy scores.

## Dataset

The dataset used for this project is `heart_disease.csv`, containing various attributes such as age, sex, chest pain type, resting blood pressure, serum cholesterol levels, etc., along with the target variable indicating the presence or absence of heart disease.

## Steps Taken

1. **Data Preprocessing**: The dataset is loaded into a pandas DataFrame and preprocessed by splitting it into training and testing sets using the `train_test_split` function from scikit-learn.

2. **Logistic Regression Model**: A logistic regression model is trained on the training data to predict the presence of heart disease. The accuracy score of the model is calculated using the testing data.

3. **Decision Tree Classifier Model**: A decision tree classifier is trained on the same training data to predict the presence of heart disease. Similarly, the accuracy score of this model is calculated using the testing data.

4. **Comparison**: The accuracy scores of both models are compared to evaluate their performance in predicting heart disease.

## Factors Affecting Model Performance

Several factors may influence the variation in accuracy between the logistic regression and decision tree classifier models:

- **Model Complexity**: Logistic regression assumes a linear relationship between features and the target variable, while decision trees can capture non-linear relationships.

- **Feature Importance**: Decision trees can automatically select important features, whereas logistic regression treats all features equally.

- **Overfitting**: Decision trees are prone to overfitting, which may lead to decreased performance on unseen data.

- **Data Distribution**: The performance of models depends on the distribution of features and the presence of non-linear relationships.

- **Hyperparameters**: The performance of decision trees can be sensitive to hyperparameters like tree depth and minimum samples per leaf.

## Conclusion

In this project, logistic regression achieved an accuracy of X%, while the decision tree classifier achieved an accuracy of Y%. Further analysis and experimentation may be required to improve the performance of both models, including feature engineering, hyperparameter tuning, and assessing the data distribution.
