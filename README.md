# 📰 TruthLens – Fake News Detection System

**TruthLens** is an NLP-powered machine learning system designed to classify news articles as **Real** or **Fake**.
This project focuses on high-quality text preprocessing, TF-IDF–based feature extraction, and a robust ML classifier to effectively identify misleading or fabricated news content.

---

## 🔍 Overview

With the rapid spread of misinformation, automated fake-news detection systems have become essential.
TruthLens uses classical NLP techniques and machine learning to analyze textual patterns and detect whether a news article is legitimate or deceptive.

---

## 🚀 Key Features

* Complete text preprocessing:
  *stopword removal, tokenization, stemming, punctuation cleaning*
* TF-IDF vectorization for converting text into numerical features
* Machine Learning classifier (Logistic Regression) with option to try others
* Evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
* Clean and modular Jupyter Notebook implementation
* Simple, easy-to-run pipeline for beginners as well as ML practitioners

---

## 👨‍💻 Author

This project was originally developed by **Harsh Porwal**.

---

## 📂 Project Structure

```
TruthLens/
│
├── Project_5_Fake_News_Prediction.ipynb   # Core notebook with training, evaluation
├── requirements.txt                       # Dependencies
└── README.md                              # Documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/harshporwal033/TruthLens.git
cd TruthLens
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook Project_5_Fake_News_Prediction.ipynb
```

---

## 📊 Dataset

TruthLens uses the **Fake News Detection Dataset**, often available on platforms like Kaggle.

Make sure to place the dataset (train/test CSV files) in the project folder before running the notebook.

Dataset includes:

* News titles
* News bodies
* Labels: *Real* or *Fake*

---

## 📈 Model Performance

The project evaluates model performance using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**

These metrics provide deeper insight into how well the system distinguishes real vs fake news.

---

## 🛠️ Technologies Used

* **Python**
* **NumPy**, **Pandas**
* **Scikit-learn**
* **NLTK**
* **Jupyter Notebook**

---

## 🤝 Contributors

* **Harsh Porwal** – Author

---

## 📜 License

This project is open for academic and educational use.
Feel free to modify, improve, or extend it.


