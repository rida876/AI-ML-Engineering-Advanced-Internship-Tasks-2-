# README.md

# Machine Learning Assignment – BERT, Scikit-learn Pipeline, LLM Auto Tagging

 Overview

This repository/document contains three machine learning tasks covering Deep Learning, Classical Machine Learning, and NLP using LLMs.

---

 Student Information

* **Name:** Mahi Jutt
* **Program:** BSCS (Bachelor of Science in Computer Science)
* **Course:** Machine Learning / Data Science
* **Date:** 16 May 2026

---

 Project Structure

1. News Topic Classifier Using BERT
2. End-to-End ML Pipeline using Scikit-learn Pipeline API
3. Auto Tagging Support Tickets using LLM


 Task 1: News Topic Classifier Using BERT

 Objective

Fine-tune a BERT model to classify news headlines into categories like World, Sports, Business, and Science/Technology.

 Dataset

* AG News Dataset (Hugging Face)
* 4 labeled classes

 Workflow

* Tokenization using `BertTokenizer`
* Model: `bert-base-uncased`
* Training using Hugging Face Trainer API
* Loss: Cross-Entropy
* Optimizer: AdamW

 Evaluation

* Accuracy
* F1 Score

 Optional Deployment

* Streamlit / Gradio app
* Input: News headline
* Output: Predicted category

---

 Task 2: ML Pipeline using Scikit-learn

 Objective

Build an automated ML pipeline for preprocessing + training using Scikit-learn Pipeline API.

 Dataset

Any structured dataset (e.g., Titanic, Churn, Housing)

 Workflow

* Missing value handling
* Encoding categorical features
* Feature scaling
* ColumnTransformer + Pipeline

 Model

* Logistic Regression OR Random Forest

 Evaluation

* Accuracy
* Confusion Matrix
* Classification Report

 Optional

* GridSearchCV for hyperparameter tuning


 Task 5: Auto Tagging Support Tickets using LLM
 Objective

Automatically classify support tickets using Large Language Models.

 Workflow

* Input: Customer support ticket text
* Prompt Engineering for classification
* Categories: Billing, Technical Issue, Account Issue, General Inquiry

 Output Format

```json
{
  "ticket": "Internet not working",
  "tags": ["Technical Issue"]
}
```

 Improvements

* Few-shot prompting
* Multi-label classification
* Fine-tuning (optional)

---

 Conclusion

This project demonstrates:

* Deep Learning (BERT)
* Machine Learning Pipelines (Scikit-learn)
* NLP with LLMs (Prompt Engineering)

E
