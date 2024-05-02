# Data-Science-BreastCancer-Classification
The project focused on classifying breast cancer tumors as malignant or benign using machine learning techniques. The dataset used was sourced from Kaggle, containing various features such as tumor size, shape, and texture.

Challenges included handling missing values, dealing with imbalanced classes, and selecting the most relevant features for classification. To address these challenges, we performed thorough data cleaning, including imputation of missing values and feature scaling.
After data cleaning, we visualized the dataset using informative score calculations and heatmaps to understand feature correlations. This helped in identifying the most influential features for classification. Additionally, we split the dataset into a 70-30 train-test split to
train and evaluate the classification models. Four models - Logistic Regression, Random Forest, KNN, and XGBoost - were trained and evaluated based on accuracy.

The Logistic Regression model achieved the highest accuracy of 96.49%, outperforming other models. To choose the right model, we performed an accuracy vs error tradeoff analysis, considering both the model's accuracy and generalization error. Overall, the project highlighted the importance of data preprocessing, feature selection, and model evaluation in effectively classifying breast cancer tumors, with Logistic Regression emerging as the most suitable model for the task.
