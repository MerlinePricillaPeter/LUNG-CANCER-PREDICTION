# LUNG-CANCER-PREDICTION
This project aims to predict lung cancer using various machine learning models such as Naive Bayes, Gradient Boosting, SVM, XGBoost, Decision Trees, and more. The dataset is processed, features are engineered, and different algorithms are trained and evaluated for accuracy. Additionally, techniques like SMOTE (Synthetic Minority Over-sampling Technique) are used to handle class imbalance, and hyperparameter tuning is performed to improve model performance.
# INSTALLATION
Prerequisites
 1.	Python 3.7 or higher
 2.	Imbalanced Learn 
 3.	Required Python libraries as listed
# FEATURES FROM THE DATASET THAT WAS USED:
1.Gender
2.Age
3.Smoking
4.Yellow Fingers
5.Anxiety
6.Peer Pressure
7.Chronic Disease
8.Fatigue
9.Allergy
10.Wheezing
11.Alcohol Consuming
12.Coughing
13.Shortness of Breath
14.Swallowing Difficulty
15.Chest Pain
16.Lung Cancer (Target Variable)

# KEY OBJECTIVES OF THE PROJECT:
 1.Data Preprocessing: The project entails cleaning and preprocessing a dataset, which includes class imbalances, scaling numerical characteristics, managing missing values, and encoding categorical variables.
 
 2.Data Exploration and Visualisation: The project's goal is to understand data distributions, feature correlations, and the connections between symptoms and lung cancer using a variety of visualisations, including pie charts, count plots, heatmaps, and histograms.
 
 3.Multiple Classification Models: A number of machine learning models are trained and evaluated, such as Decision Trees, XGBoost, Support Vector Machines (SVM), Naive Bayes, and Gradient Boosting.
 
 4.Hyperparameter tuning: To determine the optimal model configuration, hyperparameters of models are adjusted using methods such as GridSearchCV and RandomizedSearchCV.
 
 5.Model Evaluation: Metrics including accuracy, precision, recall, F1-score, and confusion matrices are used to assess the models. This makes it easier to evaluate each model's overall performance and highlight the top-performing models.
 
 6.Handling Class Imbalance: To enhance model performance, methods such as SMOTE are utilised to create synthetic data for the minority class because the dataset has class imbalance.
 
 7.Feature Importance: Permutation importance is used to determine which characteristics are most important in lung cancer prediction after the models have been trained.
# CHALLENGES ADDRESSED:
 1.Imbalanced Classes: The model may perform poorly on the minority class if there are more non-cancer cases in the sample than cancer cases. By creating synthetic examples for the minority class, SMOTE is used to balance the classes.
 
 2.Feature Selection: The model's performance may suffer from redundant or irrelevant features. Permutation importance and other feature importance algorithms are useful for identifying important factors contributing to predictions.
# SUMMARY
By the end of the project, we want to have created an accurate machine learning model that can predict lung cancer. This model will be chosen based on performance metrics and enhanced through hyperparameter tuning. The research serves as an example of the use of machine learning to healthcare, particularly in the area of risk prediction. It highlights how crucial model assessment, data the pretreatment process, and improvement are to the machine learning process.
# Contributions
Contributions are welcome! Please feel free to submit a pull request or raise an issue.

# License
This project is licensed under the MIT License.
