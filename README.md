# 🔗 Spam Detection from URLs using NLP & SVM

This repository presents a Natural Language Processing (NLP) project aimed at detecting **spam URLs** using machine learning. The project performs text cleaning, feature extraction, and classification using an SVM model with grid search tuning.

---

## 📁 Project Structure

```
📦 URL-Spam-Detection/
├── explore.ipynb         # Jupyter notebook with full analysis
├── README.md                 # Project description and usage
```

---

## 📊 Dataset

- 📂 Source: [4Geeks Academy GitHub - `url_spam.csv`](https://github.com/4GeeksAcademy/NLP-project-tutorial/)
- 💡 Contents:
  - URL text
  - Spam labels (binary classification)
- 🔍 Initial cleanup removed over **600 duplicate entries**

---

## 🧹 NLP Preprocessing

- ✅ Lowercasing, stopwords removal (`nltk`)
- 🔤 Lemmatization with `WordNetLemmatizer`
- 🔧 Regex cleanup
- ☁️ WordCloud for spam vs. non-spam terms

---

## 🧠 Model & Evaluation

- ✨ **Model**: Support Vector Machine (SVM)
- 🔍 **Tuning**: `GridSearchCV` with `RepeatedStratifiedKFold`
- 📈 **Metrics**: Classification report including Precision, Recall, F1-score

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/jilemp/URL-Spam-Detection.git
cd URL-Spam-Detection
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Launch the notebook

```bash
jupyter notebook "explore.ipynb"
```

---

## 📚 Libraries Used

- `pandas`, `numpy`
- `nltk`, `regex`
- `matplotlib`, `wordcloud`
- `sklearn`

---

## 📬 Contact

Project developed as part of 4Geeks Academy — NLP Curriculum.
Feel free to open an issue or fork the repo for improvements!
