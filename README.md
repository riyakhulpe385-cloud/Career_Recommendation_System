# 🚀 Hybrid AI-Based Career Recommendation System

A multi-layered intelligent system that recommends personalized career paths based on student skill profiles using Machine Learning techniques.

---

## 📌 Overview

This project presents a hybrid AI-based system designed to solve the problem of generic and inaccurate career guidance. It uses a combination of clustering, collaborative filtering, and neural networks to generate realistic and data-driven career recommendations.

---

## 🎯 Problem Statement

Students often receive generic career suggestions that do not reflect their individual strengths. Traditional systems fail to provide:

* Personalized recommendations
* Data-driven insights
* Realistic skill-based validation

This system addresses these gaps by combining multiple AI techniques.

---

## 🧠 System Architecture

The system follows a multi-stage pipeline:

1. **Input Layer**

   * User provides skill scores (0–10)
   * Selects interest domain

2. **K-Means Clustering**

   * Groups users into archetypes based on skill similarity
   * Identifies student profiles

3. **Collaborative Filtering**

   * Uses cosine similarity
   * Recommends careers based on similar users

4. **MLP Neural Network**

   * Domain-specific models
   * Predicts career success probabilities

5. **Skill-Fit Validation**

   * Checks if user meets minimum requirements
   * Highlights skill gaps

---

## 📊 Dataset

* Synthetic dataset of 700+ students
* 14 career options
* 7 interest domains

Synthetic data was used to ensure controlled testing and avoid bias.

---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

---

## 📈 Machine Learning Techniques

* K-Means Clustering
* Collaborative Filtering (Cosine Similarity)
* Multi-Layer Perceptron (MLP)

---

## 📊 Output

The system provides:

* 🎯 Student Archetype
* 💼 Top Career Recommendations
* 📉 Probability Scores
* ⚠️ Skill Gap Analysis

---

## 📸 Screenshots

### Output

![Output](screenshots/output.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

---

## 💡 Key Insight

Unlike traditional systems, this model combines multiple ML techniques to balance accuracy, interpretability, and real-world feasibility.

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the program:

   ```
   python code/career_recommendation_system.py
   ```

---

## 👩‍💻 My Contribution

* Designed system architecture
* Implemented ML pipeline
* Developed recommendation logic
* Performed data preprocessing and model training

---

## 🔮 Future Scope

* Real-world dataset integration
* Web-based interface
* AI-driven feedback system

---
