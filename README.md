# 🔍 AI-Powered Fake Job Detection System

An end-to-end Machine Learning web application that detects whether a job posting is **Genuine** or **Fraudulent** using **Natural Language Processing (NLP)** and **XGBoost**. The application also provides AI-powered risk analysis, SHAP explainability, resume match score, skill analysis, and a downloadable PDF report.

---

## 🚀 Features

- ✅ Fake Job Detection using XGBoost
- ✅ NLP-based Text Processing (TF-IDF)
- ✅ SHAP Explainable AI
- ✅ AI Risk Analysis
- ✅ Resume Match Score
- ✅ Resume Skill Analysis
- ✅ Downloadable PDF Report
- ✅ Interactive Streamlit Web App

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy
- NLTK
- ReportLab

---

## 📂 Project Structure

```
Fake-Job-Detection-System/
│
├── app.py
├── fake_job_detection_ml_nlp.ipynb
├── fake_job_detector.pkl
├── preprocessor.pkl
├── xgb_model.pkl
├── feature_names.pkl
├── requirements.txt
├── README.md
└── Project Screenshot/
```

---

## 📊 Machine Learning Pipeline

1. Data Cleaning
2. Text Preprocessing (NLP)
3. TF-IDF Vectorization
4. One-Hot Encoding
5. Feature Engineering
6. XGBoost Model Training
7. Model Evaluation
8. SHAP Explainability
9. Streamlit Deployment

---

## 📈 Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | **98.77%** |
| Precision | **88.62%** |
| Recall | **85.55%** |
| F1-Score | **87.06%** |
| ROC-AUC | **99.17%** |

---

## 📄 Key Features

### 🔍 Fake Job Detection
Predicts whether a job posting is Genuine or Fraudulent.

### 🧠 SHAP Explainability
Explains which features contributed most to the prediction.

### 🛡️ AI Risk Analysis
Highlights suspicious keywords and risk factors in the job posting.

### 📄 Resume Match Score
Calculates similarity between the uploaded resume and job description.

### 🎯 Resume Skill Analysis
Displays:
- Skills Found
- Missing Skills

### 📥 PDF Report
Generates a downloadable report containing:
- Prediction
- Confidence Score
- Risk Score
- SHAP Explanation
- AI Recommendation

---

## 📸 Project Screenshots

Project screenshots are available in the **Project Screenshot** folder.

---

---

## ▶️ Installation

```bash
git clone https://github.com/kunal25629/Fake-Job-Detection-System.git

cd Fake-Job-Detection-System

pip install -r requirements.txt

streamlit run app.py
```

---

## 👨‍💻 Author

**Kunal Jain**

- GitHub: https://github.com/kunal25629
- LinkedIn: www.linkedin.com/in/kunal-jain-01a686379

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.
