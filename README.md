## Project Overview

IPL Score Prediction is a machine learning–based project that predicts the **final score of an IPL (Indian Premier League) match** at any point during the game. The model uses historical match data and current match conditions such as runs, wickets, overs, and recent performance to generate a predicted score range.
---

## Objectives

* Predict the final score of an IPL team during a live match
* Apply machine learning techniques to sports analytics
* Compare multiple regression models for accuracy
* Provide a practical score prediction function

---

## Machine Learning Models Used

* Linear Regression
* Decision Tree Regression
* Random Forest Regression

---

## Features Used

* Batting Team
* Bowling Team
* Current Runs
* Wickets Fallen
* Overs Completed
* Runs in Last 5 Overs
* Wickets in Last 5 Overs

---

## Methodology

1. **Data Collection**
   Historical IPL match datasets were collected containing ball-by-ball and match-level information.

2. **Data Preprocessing**

   * Removal of inconsistent teams
   * Handling missing values
   * One-hot encoding of categorical variables
   * Removal of first 5 overs data
   * Date formatting and cleanup

3. **Exploratory Data Analysis**

   * Correlation analysis
   * Heatmap visualization

4. **Model Training**

   * Train-test split based on match dates
   * Training and evaluation of regression models

5. **Prediction**

   * A function predicts the final score range based on match inputs

---
## Sample Output

```
Predicted Score Range: 185 – 200
```

---

## Technologies Used

* **Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn

---

## Project Structure

```
IPL-Score-Prediction/
│
├── data/                  # IPL datasets
├── notebooks/             # Jupyter notebooks
├── models/                # Trained models
├── src/                   # Source code
│   ├── preprocessing.py
│   ├── training.py
│   └── prediction.py
├── README.md
└── requirements.txt
```

---

## Future Scope

* Include player-level statistics
* Add weather and venue conditions
* Improve accuracy using advanced ML/DL models
* Enable real-time match prediction
* Develop a web or mobile-based user interface
* Extend the model to other sports

## References

* Python Official Documentation
* Scikit-learn Documentation
* Research papers on machine learning and cricket analytics
