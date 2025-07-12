#  Task 2 - Movie Rating Classification

This project is part of my **Data Science Internship at CodSoft**, where I built a machine learning model to **classify IMDb ratings** of Indian movies into **high-rated (≥7)** or **low-rated (<7)** categories based on features like Genre, Director, Cast, Year, Votes, and Duration.

---

## 🎯 Objective

To predict whether a movie is **high-rated or low-rated** using a **Random Forest Classifier** on the IMDb India dataset.  
The goal is to explore how various movie features affect the classification of IMDb scores.

---

##  Dataset

- **Source**: IMDb India Movies Dataset  
- **File Used**: `IMDb Movies India.csv`

### Features in Dataset:
- **Genre**
- **Director**
- **Actor 1**, **Actor 2**, **Actor 3**
- **Votes** (converted from comma-separated string to numeric)
- **Year**
- **Duration** (in minutes, cleaned and converted)
- **Rating** (used to generate a binary target variable)

---

## Technologies Used

- **Python**
- **Pandas** – data cleaning & preparation  
- **Scikit-learn** – model building & evaluation  
- **RandomForestClassifier** – machine learning model used  

---

##  Workflow

1. Load dataset with appropriate encoding (`ISO-8859-1`)
2. Drop rows with missing `Rating`
3. Create binary classification target:  
   - `1` = Rating ≥ 7  
   - `0` = Rating < 7
4. Clean `Votes`, `Duration`, and other string columns
5. Encode categorical columns (Genre, Director, Actors)
6. Perform a train/test split (80/20 with stratification)
7. Train the model using `RandomForestClassifier`
8. Evaluate using:
   - Accuracy
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)

---

##  Machine Learning Model

- **Model Used**: Random Forest Classifier  
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

##  How to Run

1. Clone or download the repo
2. Place `IMDb Movies India.csv` in the same folder as the script
3. Run the Python script:
python Movie_rating_prediction.py

## Demo Video
https://www.linkedin.com/posts/anushka-gulia-478106326_codsoft-machinelearning-python-activity-7349771652072660992-amwq?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAFI91xwBE6ISeZvYC5kxcw2BzyVWL_EQcuI

## ✍️ Author
Anushka Gulia
📧 Email: anushkagulia04@gmail.com
🔗 LinkedIn: linkedin.com/in/anushka-gulia-478106326
🐙 GitHub: github.com/Anushka-gulia

## Hashtags
#CodSoft #DataScience #MachineLearning #Python #IMDbClassification #RandomForest #ClassificationModel #Internship 

## Thanks to CodSoft for this amazing learning opportunity and hands-on experience with real-world data science projects!

