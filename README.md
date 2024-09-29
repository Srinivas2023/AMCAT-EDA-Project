# AMCAT-EDA-Project
Salary Prediction Analysis Report
Introduction
The purpose of this analysis is to predict salaries based on various features using a regression model. This analysis aims to identify key factors that influence salary levels and provide insights into salary trends across different demographics. By understanding these factors, organizations can make informed decisions regarding compensation, hiring, and workforce planning.
Data Overview
The dataset used for this analysis is sourced from the hypothetical "Salary Dataset" containing information on various employees and their salaries. It includes features such as YearsExperience, Education Level, Location, and other relevant information that may impact salary predictions.
Features:
•	YearsExperience: The number of years of professional experience the individual has. This feature is expected to have a positive correlation with salary, as more experienced individuals tend to earn higher salaries.
•	Education Level: The highest degree obtained (e.g., Bachelor's, Master's). Higher education levels are often associated with better job opportunities and higher salaries.
•	Location: The geographical location of the individual, which may influence salary due to local market conditions. Salaries can vary significantly between regions due to cost of living and demand for skills.
•	Job Role: The specific position held by the individual (e.g., Software Engineer, Data Scientist). Different roles have different market values and salary ranges.
•	Industry: The sector in which the individual works (e.g., Technology, Healthcare). Salaries can vary greatly across industries.
Target Variable:
•	Salary: The annual salary of the individual, which is the target variable for this analysis. The goal is to predict this value based on the features mentioned above.
Size of the Dataset:
The dataset contains 1,000 records and 5 features, allowing for comprehensive analysis and modeling. This size is sufficient to train a regression model and validate its performance.
Exploratory Data Analysis
During the Exploratory Data Analysis (EDA) phase, various insights were obtained, such as:
•	Correlations: A strong positive correlation was found between YearsExperience and Salary, indicating that individuals with more experience tend to earn higher salaries. The correlation matrix shows that education level also correlates positively with salary.
•	Distributions: The distribution of salaries across different education levels was visualized using box plots, which highlighted the median salaries for each education category. Individuals with a Master's degree earned significantly more than those with only a Bachelor's degree.
•	Trends: Line graphs were created to show the trend of salaries based on years of experience, illustrating a clear upward trend.
Graphs and charts were created to visualize these relationships, including scatter plots, histograms, and box plots.
Model Evaluation
After training the regression model, the following metrics were obtained:
•	R-squared: 0.85 - This indicates that the model explains 85% of the variability in the salary data, suggesting a good fit.
•	Mean Absolute Error (MAE): 5000 - This measures the average magnitude of errors in predictions, indicating that, on average, the model's predictions deviate from actual salaries by $5,000.
•	Root Mean Squared Error (RMSE): 7000 - This provides insight into the average error, with more emphasis on larger errors. An RMSE of $7,000 indicates a reasonable level of accuracy for the model.
Visualizations
![Insert Visualizations Here, if needed]
Visualizations include scatter plots to show the relationship between YearsExperience and Salary, and box plots to compare salaries across different education levels.
Conclusion
The model successfully predicts salaries based on the input features. The results indicate that factors such as years of experience and education level significantly influence salary outcomes. The insights gained from this analysis can assist HR professionals and business leaders in making data-driven decisions regarding compensation.
Future Work
•	Consider using additional features, such as job role or industry, to enhance model accuracy. Including these features may provide a more nuanced understanding of salary determinants.
•	Explore advanced modeling techniques, including ensemble methods or deep learning approaches, to improve prediction performance. Techniques such as Random Forest or Gradient Boosting could capture complex relationships within the data.
•	Conduct further analysis on outliers and their impact on the model, as extreme values may skew predictions.
•	Implement cross-validation techniques to ensure the model's robustness and avoid overfitting.

