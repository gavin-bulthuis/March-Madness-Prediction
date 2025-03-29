Predicting March Madness Team Win Scores Using XGBoost and KenPom Data
This project leverages the power of XGBoost regression to analyze and predict a team's win score in the NCAA March Madness tournament based on KenPom college basketball (CBB) data. The model aims to identify key features influencing tournament success and provide accurate predictions for each team.

Project Motivation
March Madness captivates basketball fans worldwide, and predicting the outcomes of the tournament has always been an engaging challenge. By harnessing advanced machine learning techniques and utilizing comprehensive KenPom data, this project explores how statistical models can offer insights into game outcomes, player performance, and team dynamics.

Features and Data
The dataset used for this project includes historical KenPom data and other important variables, which provide advanced metrics for college basketball teams. Some key features include:

Offensive Efficiency (AdjO)

Defensive Efficiency (AdjD)

Tempo (AdjT)

Effective Field Goal Percentage (eFG%)

Turnover Rate (TORate)

Rebound Percentage (Reb%)

Free Throw Rate (FTRate)

Strength of Schedule (SOS)

Additional variables, such as coach, conference, and top 12 in the Week 6 AP Poll are included.

The target variable is "Win Score", which measures a team's performance in the March Madness tournament.

Win Score is pretty easily calculated.
- Win National Championship: 32
- Make National Championship: 16
- Make Final Four: 8
- Make Elite 8: 4
- Make Sweet 16: 2
- Make Round of 32: 1
- Lose Round of 64: 0

Model Overview
The project employs XGBoost Regression, a gradient boosting framework known for its efficiency and accuracy in handling structured data. Key steps in the pipeline include:

Data Preprocessing: Cleaning, encoding, and feature scaling of KenPom data.

Exploratory Data Analysis (EDA): Visualizing trends and understanding feature importance.

Hyperparameter Tuning: Using GridSearchCV for parameter optimization.

Model Training: Building and training the XGBoost regression model.

Evaluation: Assessing model performance using metrics such as RMSE and testing on previous tournaments.

Results
The project demonstrates:

Feature importance rankings from the XGBoost model.

Predictive accuracy of win scores during the tournament.

Insights into the key factors contributing to a team's success.

Contributions
Contributions are welcome! If you have ideas for improving the project or extending its scope, please open an issue or submit a pull request.

Disclaimer
This project is for educational purposes only. KenPom data is subject to copyright, so please ensure compliance with their usage terms.
