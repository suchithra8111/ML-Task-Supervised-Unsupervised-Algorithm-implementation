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

# .Claim: A child psychologist asserts that the average time working mothers spend talking to their children is at least 11 minutes per day.
.Sample: A random sample of 1000 working mothers was selected, revealing an average time of 11.5 minutes spent talking to children per day.
.Population Standard Deviation: Previous research suggests a population standard deviation of 2.3 minutes.
.Hypothesis Test: A hypothesis test was conducted with a significance level (alpha) of 0.05 to ascertain if there is sufficient evidence to support the psychologist's claim.
.Additional Note: Since we have a sample size of 1000, which exceeds 30, and we possess information about the sample mean, standard deviation, and aim to compare the sample mean to a population value, a Z-test is appropriate.
