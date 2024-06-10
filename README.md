# classification-challenge
Module 13 Challenge 

# Spam Detector

This project involves building and comparing two models for detecting spam emails: Logistic Regression and Random Forest Classifier.

## Data

The data is located at https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv and is sourced from the UCI Machine Learning Library. It contains various features related to word and character frequencies in emails.

## Preprocessing

The data is split into training and testing sets, and the features are scaled using StandardScaler.

## Models

### Logistic Regression

A Logistic Regression model is trained on the scaled training data, and its accuracy is evaluated on the test data.

### Random Forest Classifier

A Random Forest Classifier model is trained on the scaled training data, and its accuracy is evaluated on the test data.

## Results

The Random Forest Classifier model performed better than Logistic Regression in terms of accuracy on the test data (95.44% vs 91.97%).[1]

While the Random Forest model fit the training data extremely well (99.95% training score), there was a risk of overfitting. However, it still maintained higher accuracy on the test data compared to Logistic Regression.[1]

The Random Forest model's strengths, such as handling complex relationships and automatically determining important features (like word/character frequencies), likely contributed to its better performance. Additionally, the ensemble learning nature of Random Forests, combining multiple decision trees, provided better generalization and robustness compared to the single Logistic Regression model.[1]

## Conclusion

The Random Forest Classifier demonstrated superior performance in detecting spam emails, reinforcing the value of ensemble methods like Random Forests for complex, high-dimensional data.[1]
```
