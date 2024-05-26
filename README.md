# ML-Task-Supervised-Unsupervised-Algorithm-implementation

House Price Analysis-
 [Dataset](https://drive.google.com/file/d/1Bif-75zrGS957qUzxiuKHAkbiRR176Ec/view?usp)

# INTRODUCTION
This project delved into scrutinizing property prices in Bangalore with the aid of the house_price.csv dataset. The focal point was on assessing the price per square foot and detecting outliers through various methodologies including mean, percentile, interquartile range, normal distribution, and Z-score analysis. Leveraging these diverse approaches offered a comprehensive understanding of the dataset's distribution and any anomalous observations therein. Additionally, employing visualization techniques such as box plots, histograms, correlation heatmaps, and scatter plots facilitated a more intuitive exploration of the data, enabling the identification of trends, patterns, and potential correlations among variables. By combining analytical methods with visualizations, this project aimed to provide a multifaceted perspective on property price dynamics in Bangalore. Such insights are invaluable for stakeholders in the real estate sector, offering actionable intelligence for decision-making processes related to property investment, pricing strategies, and market trends. Ultimately, this analysis contributes to a deeper understanding of the nuances within Bangalore's real estate market landscape, facilitating more informed and data-driven decision-making.

# Data Preprocessing and Analysis Report
Data Loading and Null Value Examination:
The dataset was successfully loaded and examined for any missing values.
Outlier Detection in Price per Square Feet Column:
Outliers were detected using box plots and histograms for the price per square feet column.
Outlier Removal Techniques:
Employed various methods including mean, percentile, interquartile range, normal distribution, and Z-score to effectively remove outliers.
Visualization of Outliers:
Box plots were plotted for all numerical columns to visually represent the outliers.
Normality Check:
Utilized histograms to assess the normality of the price per square feet column.
Correlation Analysis:
Calculated the correlation between numerical columns and visualized it using a heatmap.
Scatter Plots for Correlation Analysis:
Created scatter plots between variables to further examine their correlation.

## Visualizations
*Box plot of Price per Sqft

*Histogram of Price per Sqft

*Correlation Heatmap

*Pairplot of Numerical Columns

## Conclusion
Overall, this analysis provides insights into the distribution of property prices in Bangalore and highlights the effectiveness of various outlier detection methods. The visualizations help in understanding the relationships between different numerical variables and identifying any potential patterns or trends.

### Hypothesis Testing
This project involves the application of hypothesis testing to scrutinize assertions presented in two distinct scenarios. Hypothesis testing, a statistical methodology, facilitates the extraction of meaningful insights regarding population parameters from limited sample data. By assessing the likelihood of observed outcomes under different hypotheses, it enables informed decision-making processes. Through rigorous analysis, hypothesis testing aids in either corroborating or refuting claims, providing valuable insights into the underlying phenomena. Its utility extends across various domains, serving as a cornerstone for drawing robust conclusions and informing strategic actions based on empirical evidence in diverse contexts.

## Tasks

## Task 1: Child Psychologist's Claim

*Claim: A child psychologist asserts that the average time working mothers spend talking to their children is at least 11 minutes per day.

*Sample: A random sample of 1000 working mothers was selected, revealing an average time of 11.5 minutes spent talking to children per day.

*Population Standard Deviation: Previous research suggests a population standard deviation of 2.3 minutes.

*Hypothesis Test: A hypothesis test was conducted with a significance level (alpha) of 0.05 to ascertain if there is sufficient evidence to support the psychologist's claim.

*Additional Note: Since we have a sample size of 1000, which exceeds 30, and we possess information about the sample mean, standard deviation, and aim to compare the sample mean to a p
opulation value, a Z-test is appropriate.

Result: The calculated z-score (6.88) significantly exceeds the critical value (1.645), leading to the rejection of the null hypothesis. Therefore, there is substantial evidence to conclude that working mothers spend more than 11 minutes per day talking to their children.

## Task 2: Coffee Shop's Claim

*Claim: A coffee shop asserts that their average wait time for customers is less than 5 minutes.

*Sample: A sample of 40 customers was observed, yielding an average wait time of 4.6 minutes with a standard deviation of 0.8 minutes.

*Hypothesis Test: A hypothesis test was conducted at a significance level of 0.05 to determine if there is adequate evidence to support the coffee shop's claim.

*Additional Note: Since the sample size is small (typically <30) and the population standard deviation is unknown, a t-test is appropriate for this scenario.

Result: The calculated t-value (-3.16) is lower than the critical t-value (-1.685), leading to the failure to accept the null hypothesis. This indicates sufficient evidence to support the claim that the average wait time for customers is less than 5 minutes at a significance level of 
0.05

## Conclusion
Hypothesis testing allows us to evaluate claims or hypotheses about population parameters using sample data. By setting up null and alternative hypotheses and conducting appropriate tests, we can make informed decisions about the validity of these claims. The results of these tests provide valuable insights for decision-making in various fields.



# DATA PREPROCESSING

## Objective:
This project aims to develop a reliable data preprocessing system to enhance the quality and usability of datasets for machine learning applications. By addressing issues like missing values, outliers, and inconsistent formatting, we strive to improve data integrity and analysis outcomes.

 [Dataset](https://drive.google.com/file/d/1RiZO-MuousjNO16uzB3OP3yzyYECC-Kn/view?usp=sharing)


## Key Components:
*Data Exploration: Understand dataset structure, identify unique values, and perform basic statistical analysis

*Data Cleaning: Handle missing values, remove duplicates, and address outliers.

*Data Analysis: Filter and visualize data based on specific criteria.

*Data Encoding: Convert categorical variables into numerical representations.

*Feature Scaling: Standardize or normalize feature values for improved model performance.

## Next Steps:

*Explore the provided dataset and run the preprocessing script to observe its effects.

*Experiment with different preprocessing techniques to optimize data quality.

*Share feedback or suggest improvements to enhance the preprocessing system.


### Car Price Prediction with Linear Regression

[dataset](https://drive.google.com/file/d/17IFuoTr7YH9tK34XAws7Gf1NcZSN9lv4/view?usp=drive_link)

## Introduction:
 In this project, we aim to predict car prices using various machine learning algorithms on the CarPrice dataset. This dataset includes features such as car make, model, engine size, and horsepower.

## We will use and compare the following five regression algorithms:
## 1.Linear Regression: Models the relationship between car price and its features using a straight line.

## 2.Decision Tree Regressor: Splits the data into branches to make predictions based on feature values

## 3.Random Forest Regressor: Uses multiple decision trees to improve prediction accuracy.

## 4.Gradient Boosting Regressor: Builds trees sequentially, where each tree tries to correct errors from the previous one.

## 5.Support Vector Regressor (SVR): Fits the data within a margin, aiming to minimize prediction errors.

## Our goal is to evaluate these models based on their prediction accuracy and identify the best approach for predicting car prices. We will use performance metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score to compare the models.

# Clustering Analysis on the Iris Dataset
This project applies various clustering methods to the Iris dataset to uncover hidden patterns in the data. We use K-means clustering, Agglomerative clustering, and Hierarchical clustering, and evaluate their performance.


## The Iris dataset contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. There are three species: Iris setosa, Iris versicolor, and Iris virginica.

# Clustering Techniques

## 1. K-means Clustering: Partitions data into K clusters by minimizing the variance within each cluster.

## 2. Agglomerative Clustering: Builds clusters hierarchically using the Ward linkage method.

## 3. Hierarchical Clustering: Produces a dendrogram to visualize nested groupings.

# Evaluation Metric
## * Silhouette Coefficient: Measures how similar a point is to its own cluster compared to other clusters. Higher values indicate better-defined clusters.

# Classifiction Analysis on Iris Dataset

## The Iris dataset is one of the most well-known datasets in the field of machine learning. It contains measurements of four features (sepal length, sepal width, petal length, and petal width) for 150 iris flowers, along with the species of each flower (setosa, versicolor, or virginica). This dataset is often used for testing and comparing classification algorithms

## 1.Logistic Regression: A statistical model that predicts the probability of a categorical outcome based on one or more predictor variables.

## 2.Decision Tree Classifier: A model that splits the data into branches based on feature values to make predictions.

## 3.Random Forest Classifier: An ensemble method that uses multiple decision trees to improve classification accuracy.

## 4.K-Nearest Neighbors (KNN): A simple, instance-based learning algorithm that classifies data points based on the labels of their nearest neighbors.

## 5.Naive Bayes: A probabilistic classifier that applies Bayes' theorem with the assumption of feature independence.
