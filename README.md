# 🏏 IPL Cricket Analytics Dashboard

An AI-powered interactive dashboard for analyzing IPL matches, teams, and player performances. The project combines Machine Learning with interactive visualizations to provide match insights, player analytics, and IPL match outcome predictions.

## 🚀 Live Demo

https://cricket-project-dashboard.streamlit.app/

---

## 📌 Project Overview

The IPL Cricket Analytics Dashboard is a web application developed using Streamlit and Machine Learning. It provides comprehensive analytics for IPL teams and players using historical IPL data (2008–2025).

The application allows users to:

- Analyze team performance
- Explore player statistics
- Classify player roles
- Predict IPL match winners
- Visualize cricket statistics through interactive charts

---

## ✨ Features

### 📊 Team Analytics
- Team-wise batting statistics
- Team-wise bowling statistics
- Top batsmen
- Top wicket takers
- Team comparison charts

### 🏏 Player Analytics
- Career runs
- Strike rate
- Batting average
- Wickets
- Economy
- Player performance visualizations

### 🎭 Match Role Analysis
Automatically classifies players into different roles.

Batting Roles:
- Aggressive Batter
- Striker
- Anchor
- Defensive Batter

Bowling Roles:
- Wicket Taker
- Economical Bowler
- Expensive Bowler

### 🤖 Match Predictor
Predicts IPL match winners using Machine Learning.

Prediction considers:

- Teams
- Venue
- Toss Winner
- Toss Decision
- Team Recent Form
- Team Strength
- Head-to-Head Record
- Venue Statistics

---

## 📈 Machine Learning

Algorithm Used:

- Random Forest Classifier

Model Features:

- Team Strength
- Recent Form
- Head-to-Head Performance
- Venue Advantage
- Toss Winner
- Toss Decision
- Historical Match Statistics

---

## 📊 Dataset

Historical IPL Dataset (2008–2025)

Files Used:

- matches_yearwise.csv
- deliveries_yearwise.csv
- player_stats.csv
- player_match_stats.csv
- player_fixes.csv
- current_squads.csv

---

## 🛠 Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Scikit-Learn
- Joblib

---

## 📂 Project Structure

```
Cricket-project/
│
├── app.py
├── requirements.txt
├── runtime.txt
├── ipl_model.joblib
├── matches_yearwise.csv
├── deliveries_yearwise.csv
├── player_stats.csv
├── player_match_stats.csv
├── player_fixes.csv
├── current_squads.csv
└── training_data.csv
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/soorya18t/Cricket-project.git
```

Move into the project

```bash
cd Cricket-project
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📷 Dashboard Modules

- 🏠 Overview
- 📈 Team Analytics
- 🏏 Player Analytics
- 🎭 Match Role Analysis
- 🤖 Match Predictor

---

## 🌐 Deployment

The application is deployed using Streamlit Community Cloud.

Live Application:

https://cricket-project-dashboard.streamlit.app/

---

## 🎯 Future Enhancements

- Live IPL Score Integration
- Playing XI Prediction
- Win Probability Graph
- AI-based Player Performance Prediction
- Fantasy Team Recommendation
- Advanced Match Insights

---

## 👨‍💻 Developer

**Soorya T**

GitHub:
https://github.com/soorya18t

---

## 📄 License

This project is developed for educational and academic purposes.
