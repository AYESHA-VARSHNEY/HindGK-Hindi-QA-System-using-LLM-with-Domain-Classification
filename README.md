# HindGK: A QA System using LLM with Domain Classification 🇮🇳

**A B.Tech Minor Project (Jan–May 2025)**  
_School of Computer Science, UPES Dehradun_

## 📌 Overview

**HindGK** is a Hindi General Knowledge (GK) Question-Answering system built using a fine-tuned Large Language Model (**LLaMA 3.1**) with integrated **domain classification**. This project addresses the lack of QA resources for low-resource languages like Hindi and explores how LLMs can be effectively adapted.

## ✨ Features

- Hindi QA system trained on 5,000 validated question-answer pairs
- Fine-tuned **LLaMA 3.1** on custom Hindi dataset
- Domain classification using:
  - Manual annotation
  - Keyword matching (Hindi + English)
  - TF-IDF vectorization + K-means clustering
- Evaluation with Accuracy, F1-Score, mBERT Score
- Semantic analysis and clustering visualizations

## 🧠 Problem Statement

While Hindi is one of the most widely spoken languages globally, NLP systems and QA tools lag far behind those for high-resource languages like English. HindGK aims to fill this gap with a scalable, fine-tuned QA pipeline for the Hindi language, supporting both open-ended and multiple-choice questions.

## 📊 Performance

| Metric               | Pretrained LLaMA 3.1 | Fine-Tuned HindGK | Improvement |
|----------------------|----------------------|-------------------|-------------|
| Accuracy             | 49.4%                | **57.2%**         | +7.8%       |
| F1 Score             | 0.6789               | **0.7877**        | +10.87%     |
| mBERT Score          | 0.7136               | **0.7598**        | +6.38%      |

Accuracy (Domain Classification | 70%



## ⚙️ System Architecture

The pipeline consists of:
1. **Dataset Preparation** – Translation + Manual Validation of QA pairs
2. **Baseline Testing** – Evaluate pretrained LLaMA 3.1
3. **Fine-Tuning** – On Hindi QA dataset
4. **Domain Classification** – Manual + Automated
5. **Clustering & Visualization** – TF-IDF + PCA + K-means
6. **Evaluation** – Accuracy, F1-score, mBERT

📸 _Insert flow diagram or architecture image here from ppt/report_

## 🛠️ Tech Stack

- Model: LLaMA 3.1 (Meta)
- Language: Python
- Libraries: PyTorch, Hugging Face Transformers, TensorFlow
- Visualization: Matplotlib, Seaborn, Scikit-learn (PCA, KMeans)
- Platform: Google Colab


## 🧪 Evaluation Metrics

- **Accuracy** – Correctly predicted answers
- **Precision** – Relevance of predicted answers
- **Recall** – Coverage of actual correct answers
- **F1-Score** – Balance between precision and recall
- **mBERT Score** – Semantic similarity in multilingual settings

📸![Screenshot 2025-04-29 144844](https://github.com/user-attachments/assets/af5e7214-f68e-40cc-82a7-0ebb1eb64350)
![Screenshot 2025-04-30 120758](https://github.com/user-attachments/assets/31a05b2e-5bee-4dcd-b131-4c8a06d52c78)
![Screenshot 2025-04-30 122105](https://github.com/user-attachments/assets/e68a3cfd-8589-485a-a261-7edc294f3161)

## 🚀 Usage
Since this is a research-focused repository, the primary assets are the datasets and evaluation metrics. 
To replicate the environment for similar fine-tuning:
1. Install dependencies: `pip install -r requirements.txt`
2. Use the datasets in the `data/` folder for fine-tuning any LLM (like LLaMA 3.1) using the Hugging Face library.
   
## 📈 Future Scope

- Extending Native Hindi QA corpus creation (not just translations)
- Extend to other Indian languages (e.g., Bengali, Marathi, Tamil)
 - Deploy mobile/web app with real-time inference









