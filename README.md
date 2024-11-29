# DSA-210-Term-Project-2024---2025
Proposal: Correlation Between Daily Entertainment Spending and Class Attendance
1. Motivation
The primary goal of this project is to explore the potential relationship between my daily entertainment spending and the number of classes I attend each day. By analyzing this correlation, I aim to understand how financial habits influence my academic behavior, particularly class attendance. This insight could help me optimize both financial and academic aspects of my life.

2. Data Source
Spending Data: Daily entertainment expenses will be retrieved from Akbank’s banking application. The entertainment category includes discretionary spending such as dining out, movies, or other leisure activities.
Class Attendance Data: The number of classes attended daily will be collected from my academic schedule, personal calendar, or institutional attendance records.
Data Integration: Both datasets will be combined into a time series format where each row represents a specific day with corresponding spending and class attendance values.
3. Data Analysis Plan
a. Exploratory Data Analysis (EDA):
Visualize daily trends in both entertainment spending and class attendance.
Explore distributions of spending amounts and class counts.
Identify outliers or anomalies in spending or attendance patterns.
b. Correlation Analysis:
Calculate the Pearson and Spearman correlation coefficients to quantify the relationship between spending and class attendance.
Examine any temporal patterns, such as day-of-the-week effects, that might influence the relationship.
c. Statistical Testing:
Conduct hypothesis testing to determine the significance of the observed correlation.
Use time series decomposition to remove seasonal or trend effects that might confound the analysis.
d. Optional Predictive Modeling:
Develop regression models to predict class attendance based on spending patterns and other features, if available.
4. Methods and Tools
Data Preprocessing: Handle missing data, remove duplicates, and clean entries. For example, normalize spending values to account for potential inflation or category misclassification.
Visualization: Create time-series plots and heatmaps using Python libraries such as Matplotlib and Seaborn.
Correlation Analysis: Compute correlations using Pandas and SciPy libraries.
Regression Models: Train machine learning models such as Linear Regression or Decision Trees (optional).
5. Anticipated Outcomes
Identify whether entertainment spending is positively, negatively, or not correlated with daily class attendance.
Derive actionable insights to improve academic performance and manage spending habits more effectively.
Share visualizations and statistics that provide a clear understanding of these relationships.
6. Challenges and Limitations
Data Accuracy: Manual categorization of spending might lead to classification errors.
Confounding Variables: Other factors, such as health, weather, or exam schedules, may influence class attendance but are not included in the analysis.
Short Time Period: A limited data collection period might restrict the generalizability of findings.
7. Future Work
Expand the analysis to include additional variables, such as sleep duration, exercise habits, or academic workload.
Use a longer-term dataset for more robust findings.
Create a dashboard that provides real-time insights into spending and academic trends.
8. Deliverables
Public Github Repository: All project materials will be uploaded to a public repository, including:
A comprehensive README.md file detailing the project, dataset, and analysis plan.
Jupyter notebooks containing data cleaning, EDA, and correlation analysis scripts.
Visualization outputs and reports summarizing the findings.
Final Report: A summary of findings and recommendations based on the analysis.
9. Timeline
November 30th: Submit project proposal with a detailed README.md file on Github.
December 10th: Complete data collection and preprocessing.
December 20th: Finish EDA and correlation analysis.
January 10th: Finalize the project with all deliverables uploaded to Github.
10. Relevance and Significance
This project aligns with the principles of personalized data science by leveraging individual data to gain meaningful insights. It also showcases diverse techniques, from EDA to predictive modeling, and demonstrates the practical value of analyzing one's behavior through data.
