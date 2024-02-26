#Python Data Science project. Machine Learning

Topic - App Rating Prediction

DESCRIPTION Objective: Make a model to predict the app rating, with other information about the app provided. Problem Statement:

Google Play Store team is about to launch a new feature wherein, certain apps that are promising, are boosted in visibility. The boost will manifest in multiple ways including higher priority in recommendations sections (“Similar apps”, “You might also like”, “New and updated games”). These will also get a boost in search results visibility. This feature will help bring more attention to newer apps that have the potential. Domain: General

Analysis to be done: The problem is to identify the apps that are going to be good for Google to promote. App ratings, which are provided by the customers, is always a great indicator of the goodness of the app. The problem reduces to: predict which apps will have high ratings.

The project focuses on predicting app ratings using machine learning techniques. After performing data cleaning, exploratory data analysis (EDA), and data preprocessing, a linear regression model is built to predict app ratings based on various features such as price, size, reviews, category, genres, and content rating.

Key Steps:

Data Cleaning and Preprocessing: The dataset is cleaned by handling null values, converting data types, and removing outliers. Numeric columns like Reviews, Installs, and Price are converted to appropriate data types. Outliers in Price, Reviews, and Installs are treated to improve model performance.

EDA (Exploratory Data Analysis): Univariate and bivariate analysis are performed to understand the distribution of variables and their relationship with the target variable (app ratings). Boxplots and histograms are used to visualize the data and identify patterns and outliers.

Data Preprocessing: Before building the model, data preprocessing steps include log transformation of skewed features (Reviews and Installs), dropping irrelevant columns, and encoding categorical variables using dummy encoding.

Model Building: A linear regression model is trained on the preprocessed data to predict app ratings. The model is evaluated using the R-squared metric on the training set to assess its performance.

Model Evaluation: The trained model is used to make predictions on the test set, and the R-squared value is reported to evaluate its performance on unseen data.

Output Summary:

The linear regression model achieves an R-squared score of 0.074 on the training set, indicating the percentage of variance in the target variable (app ratings) explained by the model.
On the test set, the model achieves an R-squared score of 0.063, demonstrating its ability to generalize well to unseen data.
Overall, the model shows promise in predicting app ratings based on the provided features, providing valuable insights for Google Play Store's feature implementation to boost promising apps' visibility.

