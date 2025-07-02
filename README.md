
# Naive Bayes Text Classification - Blog Topic Prediction

This project demonstrates how to use **Naive Bayes** for **text classification** using blog post data. The aim is to predict the **category/topic** of a blog post based on its content.

---

## 📘 Overview

Using a dataset of blog posts (`blogs.csv`), this notebook performs the following:

- Text preprocessing (cleaning, tokenization, stopword removal)
- Vectorization using `CountVectorizer`
- Model training with **Multinomial Naive Bayes**
- Performance evaluation (confusion matrix, classification report)

---

## 🧠 Problem Statement

> Given a blog post, can we automatically predict its topic?

We use the **Naive Bayes classifier**, which is especially effective for text classification tasks due to its simplicity and strong performance on high-dimensional data.

---

## 📁 Dataset

- File: `blogs.csv`
- Columns:
  - `Blog`: The blog content (text)
  - `Category`: The true label/topic of the blog post

---

## 🔧 Dependencies

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/naive-bayes-blog-classifier.git
cd naive-bayes-blog-classifier
```

2. Run the Jupyter notebook:
```bash
jupyter notebook Naive_Bayes_and_Text_Mining.ipynb
```

3. The notebook walks through:
   - Loading the dataset
   - Cleaning and preprocessing the text
   - Splitting data into train/test
   - Vectorizing text using `CountVectorizer`
   - Training a **MultinomialNB** model
   - Evaluating the model using classification metrics

---

## 📊 Output

The model outputs:

- **Accuracy score**
- **Confusion Matrix**
- **Classification Report** (precision, recall, F1-score)

---

## 📌 Example Results

Sample prediction output:

| Actual Category | Predicted Category |
|-----------------|--------------------|
| Sports          | Sports             |
| Technology      | Technology         |
| Food            | Food               |

---

## 📈 Model Evaluation

The model is evaluated on:

- **Accuracy**
- **Precision / Recall / F1-score**
- **Confusion matrix heatmap**

The results demonstrate that Naive Bayes performs well for classifying text with minimal computational cost.

---

## 🧠 Concepts Used

- Text Cleaning
- Stopword Removal
- Bag-of-Words Model
- Multinomial Naive Bayes
- Train/Test Split
- Evaluation Metrics

---

## 🙌 Acknowledgments

- Dataset created manually (blogs.csv)
- Python libraries: Scikit-learn, Pandas, Seaborn, Matplotlib

---

## 📜 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🔗 Connect

Feel free to explore, fork, and contribute!  
⭐ Star the repository if you find it useful.
