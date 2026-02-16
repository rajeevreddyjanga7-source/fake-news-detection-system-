 Fake News Detection System

> A Machine Learning & NLP project to classify news articles as **Fake** or **Real**.

---

 Project Overview

Fake news spreads misinformation and creates serious social impact.  
This project builds a supervised Machine Learning model using **Natural Language Processing (NLP)** techniques to automatically detect whether a news article is fake or real.

---

 🎯 Objective

- Perform text preprocessing on raw news data
- Convert text into numerical features using TF-IDF
- Train classification models
- Evaluate performance using proper ML metrics

---

 📂 Dataset

- Source: Kaggle Fake News Dataset
- Features:
  - `title`
  - `text`
  - `label` (0 = Fake, 1 = Real)
- Type: Binary Classification (NLP)

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF Vectorizer

---

### Data Cleaning
- Removed null values
- Converted text to lowercase
- Removed punctuation and special characters

### Text Preprocessing
- Tokenization
- Stopword removal
- Stemming / Lemmatization

###  Feature Engineering
- Applied **TF-IDF Vectorization**
- Converted text data into numerical vectors

###  Model Training
Models implemented:
- Logistic Regression
- Naive Bayes

###  Model Evaluation
Evaluated using classification metrics and ROC curve.

---

##  Model Performance

| Metric      | Score |
|-------------|--------|
| Accuracy    | 93%    |
| Precision   | 92%    |
| Recall      | 94%    |
| F1-Score    | 93%    |
| ROC-AUC     | 0.95   |

---

##  Evaluation Metrics Explained

- **Accuracy** – Overall correct predictions  
- **Precision** – How many predicted Real news are actually Real  
- **Recall** – How many Real news articles were correctly detected  
- **F1-Score** – Balance between Precision & Recall  
- **ROC-AUC** – Model performance across thresholds  

---

##  Results

<img width="640" height="480" alt="confusion_matrix" src="https://github.com/user-attachments/assets/769fdf24-f283-4faf-9127-dbf30bc9280e" />


- Confusion Matrix
- ROC Curve

---

##  How to Run This Project

```bash
git clone https://github.com/your-username/fake-news-detection-system.git
cd fake-news-detection-system
pip install -r requirements.txt
python app.py
```

---

## Key Learnings

- Handling text data in Machine Learning
- Feature extraction using TF-IDF
- Comparing classification models
- Evaluating ML models properly

---

⭐ If you found this project useful, feel free to star the repository.
