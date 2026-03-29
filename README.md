# AI Career Guidance System

The AI Career Guidance System is an intelligent web-based application designed to provide personalized career recommendations based on user inputs such as skills, interests, and academic background.

This system uses machine learning techniques to analyze user data and suggest suitable career paths, helping individuals make informed decisions about their future.

## Key Features:
- Personalized career recommendations
- Interactive user interface
- Machine learning-based predictions
- Real-time input processing

## Data Preprocessing:
- Assisted in collecting and organizing career-related dataset
- Performed basic data cleaning (handling missing values and inconsistencies)
- Applied simple transformations such as encoding categorical data
- Helped in selecting relevant features for model training

## My Contributions:
- Contributed to data preprocessing and dataset preparation
- Assisted in improving model input features
- Supported backend logic for handling user inputs
- Made minor UI improvements
- Participated in testing and debugging
- Collaborated with team member throughout development

## Tech Stack:
- Frontend: HTML, CSS, JavaScript
- Backend: Python
- Machine Learning: Scikit-learn, Pandas, NumPy

# 🚀 AI Career Guidance System

**An Intelligent Machine Learning–Powered Career Recommendation Platform**

---

## 📌 Project Overview

The **AI Career Guidance System** is an end-to-end machine learning–based web application designed to provide **personalized career recommendations** based on an individual's **aptitude assessment and performance evaluation**.

This system leverages **Gradient Boosting Classification**, feature engineering, and probability-based ranking to recommend the **Top-5 most suitable career paths** with confidence scores.

> 🎯 **Goal:** Help students and professionals make informed career decisions using AI.

---

## 🧠 Key Features

* 🔍 **Aptitude-Based Analysis**

  * 8 cognitive & behavioral aptitude dimensions (0–20 scale)
* 📊 **Performance Evaluation**

  * 8 academic/professional performance indicators (POOR / AVG / BEST)
* 🤖 **Machine Learning Prediction**

  * Gradient Boosting Classifier
  * Probability-based Top-5 career recommendations
* 📈 **High Accuracy**

  * Model accuracy ≈ **97%**
* 🌐 **Full-Stack Web Application**

  * Flask REST API (Backend)
  * Modern responsive UI (Frontend)
* 🎨 **Dark Mode UI**

  * User-friendly & professional design
* 🔄 **REST API Integration**

  * JSON-based request/response handling
* 🧪 **Model Health & Validation Endpoints**

---

## 🧩 System Architecture

```
Frontend (HTML + Tailwind + JS)
        ↓ (JSON API)
Backend (Flask REST API)
        ↓
Machine Learning Model (Gradient Boosting)
```

---

## 🧠 Machine Learning Details

### 🔹 Model Used

* **Algorithm:** Gradient Boosting Classifier
* **Reason:**

  * Handles non-linear relationships
  * High accuracy on structured tabular data
  * Robust to overfitting

### 🔹 Feature Engineering

Total **25 engineered features**, including:

* Raw aptitude scores
* Performance metrics
* Aggregate aptitude score
* Aptitude diversity (standard deviation)
* Intelligence, creativity, social & physical indices
* Performance score & binary high-performer flag
* Cluster indicator

### 🔹 Output

* **Top-5 career predictions**
* Confidence score (%) for each career

---

## 📊 Model Performance

| Metric     | Value                       |
| ---------- | --------------------------- |
| Accuracy   | **≈ 97.6%**                 |
| Model Type | Gradient Boosting           |
| Output     | Probabilistic Top-5 Ranking |
| Evaluation | Cross-validated             |

📄 *Detailed metrics available in:*
`backend/model_summary_report.txt`

---

## 🗂 Project Structure

```
career-guidance-project/
│
├── backend/
│   ├── app.py
│   ├── career_prediction_model.joblib
│   ├── feature_order.json
│   ├── feature_scaler.joblib
│   ├── label_encoder.joblib
│   ├── model_summary_report.txt
│   ├── requirements.txt
│
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   │   └── styles.css
│   │   └── js/
│   │       ├── test.js
│   │       └── theme.js
│   │
│   ├── index.html
│   ├── about.html
│   ├── features.html
│   ├── test.html
│   ├── contact.html
│
├── .gitignore
└── README.md
```

---

## ⚙️ Tech Stack

### 🧠 Machine Learning

* Python
* NumPy
* Scikit-learn
* Joblib

### 🖥 Backend

* Flask
* Flask-CORS
* REST API (JSON)

### 🌐 Frontend

* HTML5
* Tailwind CSS
* JavaScript (ES6)

### 🧪 Development Tools

* VS Code
* Git & GitHub
* PowerShell
* Virtual Environment (venv)

---

## ▶️ How to Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ManikantaPerla07/AI-Career-Guidance-System.git
cd AI-Career-Guidance-System
```

### 2️⃣ Setup Backend

```bash
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python app.py
```

Backend runs at:

```
http://127.0.0.1:5000
```

### 3️⃣ Run Frontend

* Open `frontend/index.html` in browser
  OR
* Use Live Server in VS Code

---

## 🔗 API Endpoints

### 🔹 Health Check

```
GET /health
```

### 🔹 Predict Career

```
POST /predict
Content-Type: application/json
```

**Request Payload**

```json
{
  "aptitudes": {
    "linguistic": 12,
    "musical": 10,
    "bodily": 11,
    "logical_mathematical": 15,
    "spatial_visualization": 14,
    "interpersonal": 13,
    "intrapersonal": 12,
    "naturalist": 11
  },
  "performance": {
    "project_performance": "AVG",
    "practical_skills": "AVG",
    "research_interest": "AVG",
    "communication_skills": "AVG",
    "leadership_qualities": "AVG",
    "teamwork": "AVG",
    "time_management": "AVG",
    "self_learning": "AVG"
  }
}
```

**Response**

```json
{
  "status": "success",
  "top_predictions": [
    {
      "rank": 1,
      "career": "Economist",
      "confidence": 31.11
    }
  ]
}
```

---

## 🎓 Academic & Resume Value

This project demonstrates expertise in:

* Machine Learning pipeline design
* Feature engineering
* Model evaluation & optimization
* REST API development
* Full-stack integration
* Production-ready project structuring

### 📌 Resume-Ready Description

> *Developed an AI-based Career Guidance System using Gradient Boosting ML achieving 97% accuracy. Built a full-stack application with Flask REST APIs and a modern responsive frontend to deliver probabilistic career recommendations.*

---

## 🔮 Future Enhancements

* SHAP-based explainability
* User login & history tracking
* Dynamic cluster detection
* Deployment on cloud (Render / AWS)
* Interactive charts & dashboards

---

## 👨‍💻 Author

**Manikanta Perla**
AI & Machine Learning Enthusiast
📧 Email: [careerai.help@gmail.com](mailto:careerai.help@gmail.com)
📍 India

---

## 📜 License

This project is for **educational & academic purposes**.
All rights reserved © 2025.




## Deployment on Render (Free) - LIVE AND ACCESSIBLE TO EVERYONE

Your AI Career Guidance System is deployment-ready! Share a live link with anyone.

### Quick Deployment in 5 Minutes

**Step 1:** Go to https://render.com and sign up with GitHub

**Step 2:** Click "New" → "Web Service" → Select this repository

**Step 3:** Configure:
- Root Directory: backend
- Build: pip install -r requirements.txt  
- Start: gunicorn app:app

**Step 4:** Deploy and share your live URL!

Your app will be accessible at: https://your-app-name.onrender.com
