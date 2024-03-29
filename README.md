# Bank-Marketing-Benchmark
 Bank marketing prediction of client subscribing a term deposit.

#### Source
Bank Marketing: https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing

#### Analysis
Eight machine learning models were used to make the prediction. In addition to data processing, statistical techniques such as grid search were used to obtain the best accuracy for each model. After this, a cross-validation (evaluation) was carried out to verify whether the results of the models were, in fact, statistically different.


| Model                     | Accuracy | Evaluation |
| :------------------------ |:--------:|:----------:|
| Naive Bayes               | 75.48%   | 76.46%     |
| Decision Trees            | 86.85%   | 86.31%     |
| Random Forest             | 88.47%   | 88.25%     |
| XGBoost                   | 88.58%   | 88.26%     |
| K-Nearest Neighbors       | 84.48%   | 84.30%     |
| Logistic Regression       | 85.72%   | 85.53%     |
| Support Vector Machine    | 88.04%   | 87.07%     |
| Artificial Neural Network | 87.28%   | 86.76%     |

The best models are Random Forest and XGBoost with almost insignificant difference. Using the Tukey test, it is verified that these models are statistically equal. This means that the chosen model will be based on decision making. If correctly predicting whether the customer will subscribe a deposit term (yes) is more important, the model chosen is Random Forest. Otherwise, the best model will be XGBoost.

#### Note
This project is for educational purposes. You can check the resolution of the problem in the code.