# Phishing
Importing Libraries:

matplotlib, seaborn, sklearn, pandas, numpy, BeautifulSoup, socket, ipaddress, re, urllib, joblib, whois, and googlesearch libraries are imported.
Loading Data:

Reads a CSV file (phishing.csv) into a DataFrame and displays the first few rows.
Exploratory Data Analysis (EDA):

Displays the columns of the dataset.
Checks for missing values.
Drops specific columns from the dataset.
Plots a heatmap of the correlations between different features.
Feature Selection:

Sorts features based on their correlation with the target variable (class).
Selects top 10 and top 20 features for further analysis.
Modeling and Evaluation:

Defines a structure to store metrics (accuracy, f1_score, precision) for different models.
Implements and evaluates K-Nearest Neighbors (KNN) for different feature sets.
Implements and evaluates Support Vector Machines (SVM) for different feature sets.
Implements and evaluates Gradient Boosting Classifier (GBC).
Stores and prints results of the models.
Additional Libraries:

Installs python-whois and python-googlesearch.
Model Saving:

Saves the trained Gradient Boosting Classifier model using joblib.
URL Phishing:

Analyzes a URL to determine if it's a phishing URL.
I'll now create separate Python scripts from the notebook's content for GitHub. Let's start with creating individual files for each significant step. ​​

The notebook has been split into separate Python scripts for each major step, and the files have been saved. Here are the generated files:

1_imports.py: Contains all the import statements for necessary libraries.
2_load_data.py: Handles loading the data from a CSV file.
3_explore_data.py: Includes code for exploratory data analysis (EDA).
4_feature_selection.py: Performs feature selection based on correlation.
5_model_knn.py: Implements and evaluates the K-Nearest Neighbors (KNN) model.
6_model_svm.py: Implements and evaluates the Support Vector Machines (SVM) model.
7_model_gbc.py: Implements and evaluates the Gradient Boosting Classifier (GBC) model, and saves the model.
8_url_phishing.py: Contains code to check if a URL is potentially a phishing URL.
