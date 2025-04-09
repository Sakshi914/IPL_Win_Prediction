🏏 IPL Win Predictor
A Machine Learning-powered Streamlit web application that predicts the winning probability of an IPL match based on real-time inputs like teams, city, target score, current score, overs, and wickets.

🚀 Features
Predicts winning probability for batting and bowling teams.
Interactive UI built with Streamlit.
Uses Logistic Regression model trained with historical IPL match data (2008 - 2024).
Handles categorical data using OneHotEncoding.

📊 Inputs
Batting Team
Bowling Team
City
Target Score
Current Score
Overs Completed
Wickets 

⚙️ Tech Stack
Python
Pandas
Scikit-learn
Streamlit
Pickle

📁 Project Structure
bash
Copy
Edit
├── app.py               # Streamlit app
├── pipe.pkl             # Trained ML pipeline
├── test.py              # Test script for local model testing
├── requirements.txt     # Dependencies
├── README.md            # Project documentation

🧠 Model Info
Algorithm: Logistic Regression
Preprocessing: OneHotEncoding (Teams and City), numeric transformation (overs, score, etc.)
Target Variable: Match winner

✨ Output
The app shows the predicted winning percentage for both batting and bowling teams in real-time.

🧪 Example
Batting Team: Mumbai Indians
Bowling Team: CSK
City: Mumbai
Target: 180
Score: 100
Overs: 12
Wickets: 3

🔹 Mumbai Indians: 68%
🔸 Chennai Super Kings: 32%

📌 To Do
Improve model performance with more features
Add visualization support (matplotlib/seaborn/plotly)
Integrate live match data APIs
