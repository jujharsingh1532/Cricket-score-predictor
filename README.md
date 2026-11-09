# Cricket-score-predictor
##PROBLEM STATEMENT:
 Predicting the final score of all cricket match before the completion of match is difficult as the score changes with every over and every wicket
 
# OBJECTIVE :
this is a machine learning project which helps us to predict the final score of cricket innings by learning the relationship with the help of LINEAR REGRESSION 
we need the details such as overs completed, current runs,and wickets lost

## TEAM and ROLLS
|MEMBER|ENTRY NO.|ROLE|
|-|-|-|
|Jujhar Singh|2026MCB1532|Execution lead|
Srinath Dixit|2026EEB1413|PPT lead|
Souvik Das|2026AIB1084|Documentation lead|
Randhi PUJITHA|2026DAB1304|Video lead| 

# OUR APPROACH

We use Linear Regression, a supervised Machine Learning algorithm, to predict the final score.

The model learns the relationship between different match conditions and the final innings score using historical IPL data.

The prediction is based on the following parameters:

Match ID

Innings

Overs completed

Current runs

Wickets lost

Using these inputs, the trained model estimates the final score of the innings.

# DATASET DESCRIPTION

The dataset contains IPL match information used to train and evaluate our Linear Regression model.

Features Used

Feature

Description

Match_ID

Unique identification number of the match

Innings

Innings number (1st or 2nd)

Overs

Number of overs completed

Current_Runs

Total runs scored so far

Wickets

Number of wickets lost

Final_Runs

Actual final score of the innings

Target Variable: Final_Runs

# MACHINE LEARNING ALGORITHM

Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In our project, it analyses the relationship between the current match situation and the final innings score.

The model uses historical data to identify scoring patterns and generates a predicted final score based on the input features.

# MODEL PERFORMANCE

We developed and evaluated two versions of our Linear Regression model.

Evaluation Metric

Original Model

Improved Model

MAE

16.41

16.99

MSE

440.09

465.67

RMSE

20.98

21.58

R² Score

0.5452

0.4764

# EVALUATION METRICS

MAE (Mean Absolute Error): Measures the average absolute difference between actual and predicted scores.

MSE (Mean Squared Error): Measures the average squared prediction error.

RMSE (Root Mean Squared Error): Represents prediction error in the same unit as the final score (runs).

R² Score: Indicates how much variation in the final score is explained by the model.

Note: The results shown above are based on our current dataset and test split.

# TECHNOLOGIES USED

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

# PROJECT STRUCTURE

IPL-Cricket-Score-Prediction/
│
├── data/
│   └── ipl_score_prediction.csv
│
├── model_training.ipynb
│
├── README.md
│
├── requirements.txt
│
├── PPT.pdf
│
└── video_link.txt

# INSTALLATION AND EXECUTION

Step 1: Clone the repository

git clone <https://github.com/jujharsingh1532/Cricket-score-predictor>

Step 2: Navigate to the project directory

cd IPL-Cricket-Score-Prediction

Step 3: Install dependencies

pip install -r requirements.txt

Step 4: Launch Jupyter Notebook

jupyter notebook

Step 5: Run the project

Open model_training.ipynb and execute the cells sequentially to train the Linear Regression model and evaluate its performance.

# EXPECTED OUTCOME

The project demonstrates how Machine Learning can be used in cricket analytics to estimate the final score of an IPL innings before the completion of the match.

It provides an analytical approach to understanding scoring patterns and predicting possible final scores based on the current match situation.

# FUTURE IMPROVEMENTS

Use a larger IPL ball-by-ball dataset.

Include additional features such as current run rate, batting partnerships, and player performance.

Experiment with advanced regression algorithms to improve prediction accuracy.

Develop an interactive web application for real-time score prediction.

Integrate live IPL match data for automatic score predictions.

# PROJECT INFORMATION

Project Title: IPL Cricket Score Prediction Using Linear Regression

Course: AI101 – Introduction to Artificial Intelligence

Institution: Indian Institute of Technology Ropar

Project Type: Machine Learning Mini Project
