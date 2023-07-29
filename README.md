# customer-churn-classificatin-
comparing the performance of 3 binary classification machine learning algorithms for classifying customer churn
The aim of the study was to compare the effectiveness of three machine learning algorithms (k-nearest neighbor, logistic regression, and decision tree) in binary classification for predicting customer churn. The data used in the study was characterized by an imbalance in class representation, with class 1 constituting only 16.9% of the data. This imbalance could potentially result in biased predictions, particularly toward class 0. Despite this issue, the model performance was evaluated before addressing the class imbalance.

Furthermore, the features used in the models were heterogeneous. While logistic regression and decision tree models do not require standardized data, scaling the data might improve their performance. Therefore, the models were trained on both scaled and unscaled data.

The study utilized a pipeline to fit the scaling and machine learning algorithms. Hyperparameters were fine-tuned using grid search cross-validation technique, and the models were evaluated based on several metrics such as AUC, ROC curve, precision-recall, and F1 score.

The results indicated that k-nearest neighbor algorithm outperformed the other algorithms with an accuracy of 88%, precision of 79%, and area under curve of 0.85 in predicting true positive values.
