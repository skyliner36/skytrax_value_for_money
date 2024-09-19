# skytrax_value_for_money
Project Objectives
To identify the main factors that influence passengers' perceptions of "value for money" in airline services, aiming to help airlines like Skysafe Airlines improve their offerings based on these insights.

Problem Statement
Airlines receive a wide range of feedback and ratings from passengers, but the "value for money" rating is often undervalued in analysis. This project seeks to identify the most significant factors contributing to a high value-for-money rating, which will help airlines allocate resources effectively to improve this rating.

Project Plan
1.	Data Extraction and Cleaning
o	Tools: Use Python with libraries such as pandas and numpy for data handling and matplotlib or seaborn for visual inspection.
o	Process: Extract the dataset, remove null values, standardize formats, and handle outliers.
2.	Correlation Test
o	Tools: Use scipy or pandas correlation functions to measure the relationship between variables.
o	Process: Run correlation tests (Pearson, Spearman, or Kendall) to determine which factors have the strongest relationship with the "value for money" rating.
3.	Factor Selection
o	Process: From the correlation analysis, select the three most significant factors that contribute to the value for money rating.
4.	Dataset Split
o	Process: Split the dataset into 80% for training and 20% for testing using train_test_split from sklearn.
5.	Machine Learning Model
o	Model Selection: Consider using models such as:
	Linear Regression (to quantify the contribution of each factor),
	Decision Trees (to model the non-linear relationships),
	Random Forest or Gradient Boosting (for robust prediction and feature importance analysis).
o	Process: Train the model using the training dataset and focus on the three selected factors.
6.	Model Testing
o	Tools: Use accuracy metrics such as R-squared, MAE (Mean Absolute Error), or RMSE (Root Mean Squared Error) to evaluate the model's performance.
o	Process: Apply the trained model to the test dataset and analyze the predictive accuracy of the three selected factors.
7.	Conclusion and Presentation
o	Summarize the results, focusing on the three most influential factors affecting passengers' value for money rating.
o	Present these findings to the airlines, providing actionable insights to improve their services.
Post-Implementation Monitoring and Re-Evaluation
8.	Monitoring Real-World Results (6-Month Period)
o	Process: After the model's initial deployment, monitor actual "value for money" ratings and other key performance indicators from passengers for the next 6 months.
o	Data Collection: Set up mechanisms for continuous data collection to ensure up-to-date feedback is incorporated.
9.	Re-Test and Model Update
o	Tools: Use the new 6-month data to:
	Re-run correlation tests to validate the chosen factors.
	Retrain the model using updated datasets if significant changes in factors are observed.
	Tune hyperparameters (e.g., learning rate, tree depth, etc.) of machine learning models to optimize performance.
o	Objective: Improve model accuracy and relevance to current trends, providing Skysafe Airlines with a dynamic, data-driven approach to improving passenger satisfaction.
10.  Data Source
-	Skytrax User Reviews Dataset (August 2nd, 2015)
-	Link: skytrax-reviews-dataset/data at master · quankiquanki/skytrax-reviews-dataset (github.com)

