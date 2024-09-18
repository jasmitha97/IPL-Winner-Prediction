# IPL-Winner-Prediction

Project Overview
This project focuses on analyzing historical IPL (Indian Premier League) data and building a machine learning model to predict the winner of the IPL final. By leveraging a wide range of statistical insights, player performance data, and match outcomes, the project aims to create a robust prediction model with high accuracy.

Key Features
Data Source: IPL match data spanning 9 years, including team statistics, player performance, and match outcomes.
Objective: Predict the champion of the IPL using previous seasons’ data while gaining insights into key factors affecting match outcomes.
Tools and Libraries:
Python: Core programming language for data analysis and model building.
NumPy & Pandas: For data manipulation, cleaning, and preprocessing.
Matplotlib & Seaborn: Used for data visualizations and identifying trends.
Scikit-learn: Employed for building and validating machine learning models.
Pyomo: For optimizing key model parameters.
Jupyter Notebook: For executing the project step by step.
Process Overview
Installing Libraries & Reading Data: Loaded the dataset for analysis after installing the required Python libraries.

Data Exploration & Cleaning:

Described the dataset to understand its structure and statistics.
Cleaned and transformed the data by filling null values.
Conducted visualizations to find correlations and patterns within the data.
Key Insights & Analysis:

Identified toss winners and their impact on match outcomes.
Analyzed team performance over the years (Total Matches vs Wins for Teams).
Explored whether the toss winner is also likely to win the match.
Analyzed player performances in terms of sixes and fours across seasons.
Evaluated team performances by runs per over across different seasons.
Identified players who won the most 'Man of the Match' awards.
Conducted team comparisons (e.g., MI vs CSK).
Analyzed the likelihood of teams scoring 200+ runs and chasing such targets.
Player and Performance Analysis:

Compared key batsmen’s performances.
Ranked the top-performing batsmen and broke down their scoring patterns (1s, 2s, 3s, 4s, 6s).
Identified top individual scores and analyzed performances inning by inning.
Analyzed bowlers with the most wickets and maximum overs bowled.
Investigated the most economical bowlers and bowlers with the highest dismissals of specific batsmen.
Team Building:

Created an optimal IPL team lineup based on key metrics, selecting:
1 wicketkeeper
3-5 batsmen
1-3 all-rounders
3-5 bowlers
RandomForestClassifier Implementation:

Split the dataset into training and testing sets.
Implemented a RandomForestClassifier to predict the winner of the IPL final.
Achieved a 79.25% accuracy on the test set and further optimized the model using Pyomo for tuning key parameters.
Compared training and test accuracies to ensure the model wasn't overfitting.
Model Building & Evaluation:

Employed regression models and cross-validation techniques to predict the IPL final's winner.
Achieved an 82% precision rate in predicting the champion.
Results
The model achieved a 79.25% test accuracy and 82% precision rate in predicting the IPL champion.
Key insights uncovered include patterns like the impact of toss wins, top-performing players, and the likelihood of successfully chasing high scores, all contributing to the model's prediction accuracy.
