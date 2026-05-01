# 🚀 Hybrid AI-Based Career Recommendation System

A hybrid AI system that combines clustering, recommendation, and neural networks to deliver personalized and realistic career guidance.

---

## 📌 Overview

This project presents a hybrid AI-based system designed to provide personalized career recommendations based on individual skill profiles. It addresses the limitations of traditional career guidance systems by combining multiple machine learning techniques to ensure accuracy, interpretability, and real-world relevance.

---

## 🎯 Problem Statement

Students often struggle to choose the right career path due to:

* Generic, one-size-fits-all recommendations
* Lack of personalized insights
* No validation of actual skill readiness

This system solves these issues by delivering data-driven and realistic career suggestions.

---

## 🌍 Why This Matters
Choosing the right career is a critical decision for students. This system bridges the gap between self-assessment and real-world opportunities by providing personalized, data-driven recommendations.

---

## 🧠 System Architecture

The system follows a multi-stage intelligent pipeline:

1. **Input Layer**

   * User enters skill scores (0–10)
   * Selects interest domain

2. **K-Means Clustering**

   * Groups users into archetypes based on skill similarity
   * Identifies student profiles

3. **Collaborative Filtering**

   * Uses cosine similarity
   * Recommends careers based on similar users
   * Domain-restricted for relevance

4. **MLP Neural Network**

   * Domain-specific models
   * Predicts probability of success in careers

5. **Skill-Fit Validation**

   * Checks minimum skill requirements
   * Highlights skill gaps

---

## 📊 Dataset

* Synthetic dataset of 700+ students
* 14 career options
* 7 domains

Synthetic data was carefully designed to simulate real-world skill distributions while avoiding privacy and bias issues.

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

## 💼 Business Impact

Helps students make informed career decisions using data-driven insights, reducing confusion and improving placement readiness.

---

## 🧾 Example Input

* Math: 9
* Creativity: 4
* Communication: 4
* Technical: 9
* Leadership: 3
* Domain: AI

---

## 📤 Example Output

* Recommended Role: AI/ML Engineer
* Confidence: High
* Skill Gap: Communication improvement required

---

## 🧪 Model Performance
The system demonstrates strong prediction consistency across domains due to domain-specific modeling and structured pipeline design.

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

* Designed and implemented the complete ML pipeline
* Integrated clustering, recommendation, and prediction models
* Developed skill gap analysis logic
* Created visualizations and output interpretation

---

## ⚠️ Limitation

This system uses a synthetic dataset for demonstration purposes. Integration with real-world data is part of future work.

---

## 🔮 Future Scope

* Integration with real-world datasets
* Web-based interactive interface
* AI-based feedback and improvement suggestions

---
