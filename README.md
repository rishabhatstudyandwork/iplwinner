# iplwinner
Overview
This project uses a RandomForestClassifier from scikit-learn to predict the winner of an IPL match based on features like:
Team 1
Team 2
Venue
Toss Winner (optional)
Toss Decision (optional)
The model is trained on historical IPL match data and provides an interactive interface using ipywidgets for users to input match details and get predictions.

Features
Interactive Interface: Users can select teams, venue, and other match details from dropdown menus.
Machine Learning Model: Uses a RandomForestClassifier for predictions.
Scalable: Can be extended to include more features like player performance, weather conditions, etc.

Dataset
The dataset used for this project contains historical IPL match data with the following columns:
team1: First team in the match.
team2: Second team in the match.
venue: Venue of the match.
winner: Winning team of the match.
You can find the dataset on Kaggle or Cricsheet.

Model Training
The model is trained using a RandomForestClassifier with the following steps:
Preprocessing:
Encode categorical variables (team1, team2, venue, etc.) using LabelEncoder.
Standardize numerical features using StandardScaler.

Training:
Split the dataset into training and testing sets.
Train the model using the training set.



Acknowledgments
Dataset: Kaggle

Libraries: scikit-learn, pandas, ipywidgets


