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
## 📈 Future Scope

- Extending Native Hindi QA corpus creation (not just translations)
- Extend to other Indian languages (e.g., Bengali, Marathi, Tamil)
 - Deploy mobile/web app with real-time inference

<h2 id="contact">Contact</h2>
  <p>For any inquiries or feedback, please contact:</p>
  <ul>
    <li><strong>Name:</strong> Deepanshu Miglani</li>
    <li><strong>Education:</strong> B.tech CSE(AIML) , UPES, Dehradun</li>
    <li><strong>Email:</strong> deepanshumiglani0408@gmail.com / Deepanshu.106264@stu.upes.ac.in</li>
    <li><strong>GitHub:</strong> <a href="https://github.com/deepanshum0408">deepanshum0408</a></li>
  </ul>
  <ul>
    <li><strong>Name:</strong> Divi Saxena </li>
    <li><strong>Education:</strong> B.tech CSE(AIML) , UPES, Dehradun</li>
    <li><strong>Email:</strong> divisaxena04@gmail.com / Divi.107784@stu.upes.ac.in</li>
    <li><strong>GitHub:</strong> <a href="https://github.com/B97784/">Divi Saxena</a></li>
  </ul>
 
  <h2 id="mentor">Mentor</h2>
  <p><strong>Dr. Sahinur Rahman Laskar</strong><br>
  Assistant Professor<br>
  School of Computer Science, UPES, Dehradun, India<br>
  Email: sahinurlaskar.nits@gmail.com / sahinur.laskar@ddn.upes.ac.in<br>
  </p>

<h2>Users of this dataset are kindly requested to cite the corresponding paper.</h2>

<h2> Refrence </h2>
@INPROCEEDINGS{Laskar_HindGK_CICN2025,
  author={Laskar, Sahinur Rahman and Deepanshu and Saxena, Divi and Badhani, Ritika and Viswakarma, Kumar Anish and Ranjan, Rakesh},
  booktitle={IEEE  17th International Conference on Computational Intelligence and Communication Networks (CICN 2025)}, 
  title={HindGK: A LLM-Based Question Answering System for Hindi General Knowledge}, 
  year={2025},
  pages={1-5},
  keywords={; Question Answering, Large Language Model, Hindi, Domain Classification},
  doi={}
  }








