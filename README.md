# ⚽ FIFA World Cup 2025 Winner Prediction (ML Model)

A machine learning project that uses historical football tournament data to predict which team is most likely to win the FIFA World Cup 2025. The model is trained on team performance stats from past tournaments and can predict winning probabilities based on new input.

---

## 🚀 Technologies Used

### 🐍 Python
Primary programming language used for data processing, model training, and prediction logic.

---

## 📦 Libraries and Frameworks

- **pandas**  
  Used for data loading, cleaning, and manipulation.  
  Example functions: `pd.read_csv()`, `DataFrame.sort_values()`, etc.

- **scikit-learn (sklearn)**  
  For machine learning tasks such as building, training, and evaluating the model.  
  - Algorithms: `RandomForestClassifier`  
  - Utilities: `train_test_split`, `accuracy_score`, `classification_report`

- **numpy** *(optional)*  
  Useful for numerical computations (though not strictly required in the current codebase).

---

## 📊 Machine Learning Model

### 🎯 Random Forest Classifier
An ensemble-based classification model trained on team performance data. It predicts whether a team is likely to win a tournament.

- **Model parameters**:
  - `n_estimators=100` – the number of decision trees used in the forest
  - `random_state=42` – for reproducibility

---

## 📁 Data Files

- `team_tournament_stats.csv`  
  Historical data including match stats, team performance, and results (used for training).

- `shoutout.csv` or `fifa_2025` dataset  
  Hypothetical or current tournament data to predict the winner of the upcoming World Cup.

---

## 🧠 Features Used for Prediction

The following features are used to train the model and predict tournament outcomes:

- `matches_played`
- `goals_for`
- `goals_against`
- `goal_difference`
- `win`
- `draw`
- `loss`

---

## ✅ Model Evaluation Metrics

These metrics are used to evaluate the model's performance:

- **Accuracy** – Overall prediction correctness
- **Precision** – Of the predicted winners, how many actually won
- **Recall** – Of the actual winners, how many were correctly predicted
- **F1 Score** – Harmonic mean of precision and recall
- **Support** – Number of actual occurrences for each class (win/loss)

---

## 📌 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/Hamaddogar/FIFA-CUP-won-ML-Model
   cd FIFA-CUP-won-ML-Model
