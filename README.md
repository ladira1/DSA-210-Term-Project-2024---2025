Proposal: Correlation Between Daily Entertainment Spending and Class Attendance
1. Motivation
The main purpose of this project is to determine the relationship between my daily entertainment spending and the number of classes I attend on a given day. From this correlation, I can gain insight into how my financial habits affect my academic behavior, such as class attendance. This could help me optimize both financial and academic aspects of my life.

2. Data Source
Spending Data: Daily entertainment expenses will be retrieved from Akbank's banking application. The entertainment category includes discretionary spending such as dining out, movies, or other leisure activities.
Class Attendance Data: The number of classes attended daily will be collected from my academic schedule, personal calendar, or institutional attendance records.
Data Integration: Both datasets will be merged into a time series format where each row represents a day with values for spending and class attendance.

3. Data Analysis Plan
a. Exploratory Data Analysis (EDA):
Visualize daily trends in both entertainment spending and class attendance.
Explore distributions of spending amounts and class counts.
Identify outliers or anomalies in spending or attendance patterns.
b. Correlation Analysis:
Compute Pearson and Spearman correlation coefficients that give a numerical value to the association between spending and class attendance. Identify any temporal effects, such as day-of-the-week effects, which could be influencing the relationship. c. Statistical Testing: Conduct hypothesis testing to assess whether or not the observed correlation is significant. Use time series decomposition to eliminate seasonal or trend effects that may confound the analysis. d. Optional Predictive Modeling:
Develop regression models to predict class attendance based on spending patterns and any other available features.

4. Methods and Tools
Data Preprocessing: Handling missing data, duplicate removal, and cleaning of entries; for example, normalizing spending values in case of potential inflation or misclassification of categories.
Visualization: Time series plots and heatmaps using Python libraries such as Matplotlib and Seaborn.
Correlation Analysis: Computation of correlations using the Pandas and SciPy libraries.
Regression Models: Train machine learning models such as Linear Regression or Decision Trees (optional).

5. Expected Outputs
Determine whether spending on entertainment is positively, negatively, or not related to class attendance every day.
Extract actionable insights that will be useful in enhancing academic performance and better controlling spending habits.
Communicate through visualizations and statistics that shall clearly illustrate these relationships.

6. Challenges and Limitations
Data Accuracy: The manual categorization of spending could result in misclassification.
Confounding Variables: Health, weather, or other exam schedules are a few factors that can affect attendance in class but are not taken into consideration here.
Short Time Period: The data collection period might be too short to generalize the findings.

7. Future Work
Consider extending the analysis to other variables: sleep duration, exercising habits, or academic workload.
Use a longer-term dataset for more robust findings.
Create a dashboard that provides real-time insights into spending and academic trends.

8. Deliverables
Public Github Repository: All project materials will be uploaded to a public repository, including:
A comprehensive README.md file detailing the project, dataset, and analysis plan.
Jupyter notebooks containing data cleaning, EDA, and correlation analysis scripts.
Visualization outputs and reports summarizing the findings.
Final Report: A summary of findings and recommendations based on the analysis.

9. Timeline
Nov 30: Project Proposal with a README.md for the Github repository.
Dec 10: Finish Data Collection, Preprocessing.
Dec 20: Complete EDA and Correlation Analysis.
Jan 10: Final Submission of project, all components uploaded on Github.

10. Relevance and Significance
This project aligns with the principles of personalized data science, leveraging individual data to gain meaningful insights. It also showcases diverse techniques, from EDA to predictive modeling, and demonstrates the practical value of analyzing one's behavior through data.
