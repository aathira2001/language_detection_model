# language_detection_model
# 🌐 Language Identification Using Machine Learning

This repository contains a **Language Identification Model** developed as a microproject for academic purposes. It aims to predict the language of a given sentence using machine learning techniques such as TF-IDF vectorization and Logistic Regression.

---

## 🧠 Project Overview

The goal of this project is to classify short text strings into their respective languages. The model is trained using a simple but effective feature extraction technique (character n-grams) and a logistic regression classifier.

---

## 📁 Files in This Project

- `languageidentification_aml_microproject.ipynb` - The main notebook that includes data loading, preprocessing, model training, and evaluation.
- `dataset.csv` - The dataset used for training and testing. It contains text samples in 5 different languages: English, French, Spanish, German, and Portuguese.

---

## 📊 Dataset Description

The dataset contains two columns:
- **Text**: The sentence or phrase.
- **Language**: The actual language label (`'en'`, `'fr'`, `'es'`, `'de'`, `'pt'`).

Example:
| Text               | Language |
|--------------------|----------|
| This is a book     | en       |
| C'est un livre     | fr       |
| Es un libro        | es       |

---

## ⚙️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression Classifier
- Matplotlib & Seaborn (for visualization)

---

## 🚀 How the Model Works

1. **Preprocessing**: The text data is cleaned and tokenized.
2. **Feature Extraction**: Character-level n-grams are used with a TF-IDF vectorizer.
3. **Model Training**: A Logistic Regression model is trained on the extracted features.
4. **Evaluation**: Accuracy score and confusion matrix are used to evaluate the performance.

---

## 🧪 Results

- **Training Accuracy**: ~99%
- **Test Accuracy**: ~98%
- **Languages Supported**: English, French, Spanish, German, Portuguese

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/language-identification-ml.git
   cd language-identification-ml


