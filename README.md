
<h1 align="center">📝 Naive Bayes Blog Topic Classifier</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" />
  <img src="https://img.shields.io/badge/License-GNU.svg" />
  <img src="https://img.shields.io/badge/Model-Naive%20Bayes-orange" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
</p>

---

## 📘 Project Overview

This project applies **Naive Bayes Classification** to predict the **topic/category of blog posts** based on their text content. Using natural language processing (NLP) and machine learning, we analyze text data and classify it into relevant categories.

---

## 🧠 Problem Statement

> Can we classify a blog post into its correct topic using machine learning and natural language processing?

We aim to build a simple and effective text classifier using the **Multinomial Naive Bayes** algorithm.

---

## 📂 Dataset

- **File**: `blogs.csv`
- **Columns**:
  - `Blog` — Raw blog text
  - `Category` — Corresponding topic/label

---

## 🔧 Tech Stack

- 🐍 Python (v3.8+)
- 📚 Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run the Project

1. **Clone the repo**:
```bash
git clone https://github.com/your-username/naive-bayes-blog-classifier.git
cd naive-bayes-blog-classifier
```

2. **Launch the notebook**:
```bash
jupyter notebook Naive_Bayes_and_Text_Mining.ipynb
```

3. **Follow the steps inside the notebook**:
   - Load and clean the data
   - Text vectorization using `CountVectorizer`
   - Train/Test split
   - Model training using `MultinomialNB`
   - Evaluate performance

---

## 📊 Sample Output

- ✅ Accuracy Score
- 📉 Confusion Matrix
- 📋 Classification Report (Precision, Recall, F1-Score)

Example:

| Actual Category | Predicted Category |
|-----------------|--------------------|
| Sports          | Sports             |
| Technology      | Technology         |
| Food            | Food               |

---

## 📈 Model Evaluation

Performance metrics used:

- ✔️ Accuracy Score
- ✔️ Precision, Recall, F1-Score
- ✔️ Confusion Matrix Heatmap

The classifier provides strong baseline results and can be extended to larger datasets.

---

## 🧰 Concepts Used

- Text Preprocessing
- Stopword Removal
- Bag of Words Model (CountVectorizer)
- Multinomial Naive Bayes Classifier
- Evaluation Metrics

---

## 🙌 Acknowledgments

Special thanks to:

- [Scikit-learn](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)
- Custom dataset: `blogs.csv`

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🌟 Show Your Support

If you find this project helpful, please ⭐ star the repo to support the project and share it with others!

---

<p align="center"><b>Made with ❤️ using Naive Bayes</b></p>
