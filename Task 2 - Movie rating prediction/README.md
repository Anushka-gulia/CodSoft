#  Task 2 - Movie Rating Prediction

This project is part of my **Data Science Internship at CodSoft**, where I built a machine learning model to predict IMDb ratings of Indian movies based on features like Genre, Director, Cast, Year, Votes, and Duration.

---

##  Objective

To predict movie ratings using a **Random Forest Regressor** model on the IMDb India dataset. The goal is to understand how various factors like genre, director, actors, votes, and duration affect the movie's IMDb score.

---

##  Dataset

- **Source**: IMDb India Movies Dataset
- **File Used**: `IMDb Movies India.csv`

###  Features in Dataset:
- **Genre**
- **Director**
- **Actor 1**, **Actor 2**, **Actor 3**
- **Votes** (converted from comma-separated strings to numeric)
- **Year**
- **Duration** (in minutes, cleaned and converted)
- **Rating** (Target variable)

---

##  Technologies Used

- **Python**
- **Pandas** – data cleaning & preparation
- **Scikit-learn** – model training & evaluation
- **RandomForestRegressor** – ML model used for prediction

---

##  Workflow

1. Load dataset with encoding (`latin1`)
2. Clean column names and drop rows with missing ratings
3. Convert `Votes` and `Duration` from string to float
4. Encode categorical columns (Genre, Director, Actors)
5. Select features and target
6. Train/test split (80/20)
7. Model training using `RandomForestRegressor`
8. Evaluate with MSE and R² Score

---

## Machine Learning Model

- **Model Used**: Random Forest Regressor
- **Evaluation Metrics**:
  - `Mean Squared Error (MSE)`
  - `R² Score`

---

## How to Run

1. Clone/download the repo
2. Place `IMDb Movies India.csv` in the same folder as the script
3. Run the Python script:
python Movie_rating_prediction.py

## Demo Video
https://www.linkedin.com/posts/anushka-gulia-478106326_codsoft-machinelearning-python-activity-7349771652072660992-amwq?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFI91xwBE6ISeZvYC5kxcw2BzyVWL_EQcuI 

## ✍️ Author
Anushka Gulia
📧 Email: anushkagulia04@gmail.com
🔗 LinkedIn: www.linkedin.com/in/anushka-gulia-478106326
🐙 GitHub: https://github.com/Anushka-gulia 

## 📌 Hashtags
#CodSoft #DataScience #MachineLearning #Python #IMDbPrediction #RandomForest #RegressionModel #Internship

## Thank you CodSoft for the learning experience and real-world project exposure!
