# Predicting-the-Severity-of-Road-Traffic-Accidents
Predicting the Severity of Road Traffic Accidents
Documentation

Data Collection and Preprocessing

The data used in this project was collected from the UK government's official statistics on road traffic accidents. Additionally, Kaggle datasets were utilized to enrich the analysis. The dataset included information about the accidents, the vehicles involved, and the casualties.

The first step in the data preprocessing was to clean the data. Irrelevant columns were removed, and missing values were handled. For categorical variables, label encoding was used to convert them into numerical values. For numerical variables, standard scaling was applied to ensure all features had the same scale.

Exploratory Data Analysis

Exploratory data analysis was performed to understand the data better and identify any patterns or trends. The distribution of the severity of injuries and the correlation between different features were visualized. This helped identify important features for predicting the severity of injuries.

Model Building

The dataset was split into a training set and a test set. Initially, a Random Forest Classifier was chosen as the model due to its ability to handle both categorical and numerical data and its robustness to overfitting. The model was trained on the training set.

Model Evaluation

Model performance was evaluated using metrics like accuracy, precision, recall, and F1 score on the test set. Cross-validation was performed to ensure the model was not overfitting the data.

Model Optimization

To improve the model's performance, hyperparameter tuning was conducted using GridSearchCV. Feature importance was also checked to gain insights into which factors were most influential in predicting the severity of injuries.

Model Deployment

Once the model's performance was satisfactory, it was deployed for real-time prediction. The joblib library was used to save the model to a file, which can be loaded later to make predictions.

Challenges and Solutions

Challenges included the high dimensionality of the data and the imbalance in the target variable. Feature importance helped identify the most important features, and stratified sampling addressed the imbalance in the target variable.

Summary of Feature Coefficients

After training the machine learning model, feature coefficients were obtained to understand each feature's impact on predicting the severity of road traffic accidents. Key findings include the association of certain features like age, location, and vehicle type with accident severity.

Conclusion

This project demonstrated how machine learning can be used to predict the severity of road traffic accidents. The model can assist traffic authorities and policymakers in understanding the factors contributing to accident severity and developing strategies to mitigate their impact. Future work could involve incorporating more data, such as weather and road conditions, to further improve the model's accuracy.

