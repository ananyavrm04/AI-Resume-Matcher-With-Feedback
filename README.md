# 🧠 AI Resume + Job Matcher with Feedback Loop

A smart, self-learning system that matches resumes to job descriptions using NLP and machine learning. Built to simulate how companies like Google or LinkedIn screen candidates at scale.

## 🚀 Features
- Cleans and vectorizes resume text using TF-IDF
- Classifies resumes into job categories with 98%+ accuracy using SVM
- Includes a recruiter feedback loop: learns from incorrect predictions
- Logs feedback to CSV for future retraining
- Modular, CLI/Colab-ready, no frontend/backend

## 📁 Files
- `resume_matcher.ipynb` – full working notebook (Colab-ready)
- `feedback_log.csv` – records corrected labels from user feedback
- `sample_data/resumes.csv` – sample resume texts
- `sample_data/job_descriptions.csv` – job listings to match against

## 🛠 Tech Used
- Python, Scikit-learn, NLTK, Pandas
- TF-IDF for vectorization
- Support Vector Machine (SVM) classifier

## 📈 Results
- Accuracy: 98.4% on test data
- F1 Score: 0.98 average
- Handles 10+ job categories

## 💡 Unique Selling Point
Unlike basic resume screeners, this project improves itself via a feedback loop, learning from recruiter corrections — just like smart hiring systems in real companies.

## ✅ How to Run
1. Open `resume_matcher.ipynb` in Google Colab
2. Upload `resumes.csv` and `job_descriptions.csv`
3. Run cells to train, predict, and log feedback
4. Download `feedback_log.csv` for model updates
