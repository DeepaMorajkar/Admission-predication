# Admission-predication

The "Admission Prediction" project is a machine learning project focused on predicting the chances of admission to a graduate program from an Indian perspective. The project involves analyzing a dataset containing various factors such as GRE scores, TOEFL scores, university ratings, statement of purpose (SOP), letter of recommendation (LOR), CGPA, research experience, and the chance of admission.

The project follows the following steps:

Exploratory Data Analysis (EDA): This step involves data cleaning, checking for missing values, and performing descriptive statistics to gain insights into the dataset. Data visualization techniques such as histograms, scatter plots, and correlation analysis are used to understand the relationships between different variables.

Feature Engineering: In this step, a new feature called "Cumulative Rating" is created by summing the values of SOP, LOR, and university ratings. This feature aims to capture the overall rating of the applicant.

Feature Importance: A random forest regressor model is used to determine the importance of different features in predicting the chance of admission. The feature importances are calculated, and a bar plot is created to visualize the results.

Dimensionality Reduction: Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset. This technique helps visualize the data in a lower-dimensional space.

Model Building: A random forest regressor model is trained on the dataset to predict the chance of admission. The dataset is split into training and testing sets, and the model is evaluated using Mean Squared Error (MSE) and R-squared metrics.

Model Evaluation: The MSE and R-squared values are calculated to assess the performance of the model. Lower MSE values and higher R-squared values indicate better model performance.
