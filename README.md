# 🏸 AI-Based Badminton Shot Prediction System

## 📌 Overview

The **AI-Based Badminton Shot Prediction System** is a machine learning project that predicts the most suitable badminton shot — **Smash, Drop, or Clear** — based on real-time gameplay conditions.

This project demonstrates how Artificial Intelligence can assist players in making better tactical decisions by analyzing multiple factors such as player position, opponent position, score pressure, and shuttle difficulty.

---

## 🎯 Problem Statement

In badminton, players must make quick decisions during rallies. Choosing the right shot depends on several dynamic factors:

* Player’s position on the court
* Opponent’s position
* Current score situation (pressure level)
* Difficulty of the incoming shuttle

Beginner players often struggle to process all these factors simultaneously, leading to poor shot selection and loss of points.

This project aims to solve this problem using Machine Learning by predicting the most effective shot under given conditions.

---

## 🤖 Features

* Predicts optimal badminton shot (Smash / Drop / Clear)
* Uses real-game parameters for decision-making
* Machine Learning-based classification model
* Simple and interactive prediction system
* Optional Streamlit UI for real-time input

---

## 📊 Dataset

Since no public dataset exists for this problem, a **synthetic dataset** was created.

### Features used:

* `Player_X` – Player's position (X coordinate)
* `Player_Y` – Player's position (Y coordinate)
* `Opponent_X` – Opponent's position (X coordinate)
* `Opponent_Y` – Opponent's position (Y coordinate)
* `Score_Situation` – Early / Mid / Pressure
* `Shuttle_Difficulty` – Easy / Medium / Hard

### Target:

* `Recommended_Shot` – Smash / Drop / Clear

---

## ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib (for visualization)
* Streamlit (for UI - optional)

---

## 🧠 Machine Learning Model

A **Decision Tree Classifier** is used for prediction.

### Why Decision Tree?

* Easy to understand and explain
* Works well with categorical data
* Suitable for small to medium datasets
* Provides clear decision logic

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/badminton-shot-predictor.git
cd badminton-shot-predictor
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Model (Jupyter Notebook)

```bash
jupyter notebook
```

Open:

```
notebook/model.ipynb
```

---

## 🖥️ Run Streamlit App (Optional)

```bash
streamlit run app/app.py
```

---

## 📈 Example Prediction

**Input:**

```
Player Position: (2, 8)
Opponent Position: (5, 2)
Score Situation: Pressure
Shuttle Difficulty: Easy
```

**Output:**

```
Recommended Shot: Smash
```

---

## 📁 Project Structure

```
badminton-shot-predictor/
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── model.ipynb
│
├── app/
│   └── app.py
│
├── README.md
└── report.pdf
```

---

## ⚠️ Challenges Faced

* No existing dataset available
* Converting gameplay intuition into structured data
* Representing shot difficulty numerically
* Balancing simplicity and realism

---

## 🌍 Applications

* Training tool for beginner players
* Sports analytics systems
* Coaching assistance platforms
* Future integration with real-time tracking systems

---

## 🔮 Future Scope

* Integration with computer vision for real-time tracking
* Use of deep learning models for better accuracy
* Mobile app development
* Personalized recommendations based on player style

---

## 👨‍💻 Author

**Daksh Nagar**
AI/ML Student

---

## 📜 License

This project is for academic purposes only.
