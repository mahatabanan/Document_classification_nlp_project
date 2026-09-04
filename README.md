# Document Classification using NLP, Traditional ML & Transformers

An end-to-end Natural Language Processing (NLP) project that categorizes text documents into predefined classes using both classical Machine Learning algorithms and modern Transformer-based architectures.

---

## 📌 Project Overview
The objective of this project is to analyze, preprocess, and accurately classify document text data. The workflow covers:
* **Text Preprocessing:** Cleaning, tokenization, stopword filtering, and vectorization.
* **Classical ML Models:** Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).
* **Transformer Architectures:** Fine-tuning pre-trained models (e.g., BERT / DistilBERT) via Hugging Face.
* **Evaluation & Reporting:** Analyzing accuracy, precision, recall, and F1-score across models, documented in the final report.

---

## 📂 Project Structure
```text
├── datasets/                # Raw and preprocessed document datasets
├── notebooks/               # Jupyter notebooks for EDA, ML, and Transformers
│   ├── 01_data_exploration.ipynb
│   ├── 02_ml_models.ipynb
│   └── 03_transformer_models.ipynb
├── report/                  # Documentation, final report, and performance plots
│   └── project_report.pdf
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation