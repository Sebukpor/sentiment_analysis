# 🏨 Sentiment Analysis for Hotel Reviews

A simple and effective machine learning project for classifying hotel reviews as **Positive**, **Negative**, or **Neutral**.

This repository contains the full workflow — from data preprocessing and model training to deployment — making it easy to understand, reproduce, and extend.

---

## 📌 Project Overview

Customer reviews play a critical role in shaping a hotel's reputation. This project applies Natural Language Processing (NLP) techniques to automatically analyze hotel comments and categorize them into:

* ✅ **Positive**
* ❌ **Negative**
* ➖ **Neutral**

The implementation is provided in a Jupyter Notebook for clarity and step-by-step understanding.

---

## 📂 Repository Structure

```
sentiment_analysis/
│
├── code/
│   └── sentiment_analysis.ipynb   # Main Jupyter Notebook
|
│── customer_reviews.xlsx   #dataset
|
└── README.md
```

The core implementation can be found in the `code/` directory.

---

## 🚀 Live Demo

You can test the deployed model using the Hugging Face Space:

👉 **Try it here:**
[https://huggingface.co/spaces/Sebukpor/sentiment_app](https://huggingface.co/spaces/Sebukpor/sentiment_app)

---

## 🧠 Model Workflow

The notebook covers:

1. Data loading and exploration
2. Text preprocessing (cleaning, tokenization, etc.)
3. Feature extraction
4. Model training
5. Model evaluation
6. Deployment preparation

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Scikit-learn
* Pandas
* NumPy
* Hugging Face Spaces (for deployment)

---

## ▶️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/sebukpor/sentiment_analysis.git
cd sentiment_analysis
```

2. Install required dependencies:

3. Open the notebook:

```bash
jupyter notebook
```

4. Navigate to the `code/` folder and run `sentiment_analysis.ipynb`.

---

## 📊 Example Use Case

Input:

```
"The room was clean and the staff were extremely helpful!"
```

Output:

```
Positive
```

---


## 📄 License

This project is open-source and available under the MIT License.
