# IPL-Win-probability-predictor
🏏 IPL Win Probability Predictor

The IPL Win Probability Predictor is a Machine Learning project that predicts the winning probability of teams in an ongoing IPL match using real-time match conditions like score, overs, wickets, target, and venue.
This system helps cricket fans, analysts, and data enthusiasts understand how match situations affect winning chances.

📌 Project Overview

In a cricket match, the winning chances change every over depending on the match situation.
This project uses IPL historical match data and trains a Machine Learning model to estimate:

✅ Batting team win probability
✅ Bowling team win probability

It takes match inputs such as:

Batting Team

Bowling Team

Host City / Venue

Target Score

Current Score

Overs Completed

Wickets Fallen

and then predicts the probability of winning for both teams.

🚀 Features

✅ Real-time win probability prediction
✅ Predicts chance of winning for both teams
✅ User-friendly interactive interface (Streamlit)
✅ Uses historical IPL match data
✅ Fast and accurate predictions

🧠 Machine Learning Approach

This project is built using a classification model, trained on IPL match datasets.
Key steps involved:

Data Cleaning & Preprocessing

Feature Engineering (runs left, balls left, wickets left, current run rate, required run rate)

Model Training using ML algorithms (Logistic Regression / Random Forest etc.)

Prediction of win probability

📂 Dataset Information

The dataset contains ball-by-ball or match-level information such as:

Teams

City/Venue

Runs scored

Wickets fallen

Overs

Target

Match Result

📌 Example dataset files (commonly used):

matches.csv

deliveries.csv

⚠️ You can download IPL dataset from Kaggle or other cricket analytics sources.

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Matplotlib (optional)

Streamlit (for UI deployment)
