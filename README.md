# 🏥 Medical Diagnosis and Prescription Recommendation using Deep Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red?style=for-the-badge&logo=keras)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=for-the-badge&logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 Overview

Medical Diagnosis and Prescription Recommendation is a **Natural Language Processing (NLP)** project built using **TensorFlow and Keras**.

The system accepts a patient's symptom description as input and simultaneously predicts:

- 🩺 Disease
- 💊 Recommended Prescription

The model uses a **shared LSTM encoder** with **multi-task learning**, enabling it to perform disease diagnosis and prescription recommendation within a single deep learning architecture.

---

## 🚀 Key Features

- Predict disease from patient symptoms
- Recommend appropriate prescription
- Multi-output Deep Learning Model
- TensorFlow Functional API
- Embedding + LSTM architecture
- Text preprocessing pipeline
- Tokenization and sequence padding
- End-to-end prediction system

---

# 🧠 Deep Learning Architecture

```
                   Patient Symptoms
                          │
                 Text Preprocessing
                          │
                    Tokenization
                          │
                   Sequence Padding
                          │
                  Embedding Layer
                          │
                        LSTM
                          │
        ┌─────────────────┴─────────────────┐
        │                                   │
 Disease Classification          Prescription Recommendation
        │                                   │
    Softmax Output                  Softmax Output
```

---

# 📂 Project Structure

```
Medical-Diagnosis/
│
├── medical_diagnoser.ipynb
├── medical_data.csv
├── README.md
├── requirements.txt
│
├── models/
│      medical_diagnoser.keras
│
├── images/
│      architecture.png
│      prediction.png
│
└── outputs/
       predictions.csv
```

---

# ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

# 📊 Dataset

The dataset consists of patient symptom descriptions paired with:

- Disease Labels
- Prescription Labels

Example

| Patient Problem | Disease | Prescription |
|-----------------|----------|--------------|
| Fever, cough, sore throat | Flu | Paracetamol |
| Chest pain while walking | Heart Disease | ECG + Aspirin |
| Loss of appetite and sadness | Depression | Antidepressants |

---

# 🔄 Workflow

```
Dataset
   │
   ▼
Text Cleaning
   │
   ▼
Tokenizer
   │
   ▼
Sequence Padding
   │
   ▼
Embedding Layer
   │
   ▼
LSTM Network
   │
   ▼
Disease Prediction
Prescription Prediction
```

---

# 🏗 Model Details

### Input

Patient symptom description

Example

```
I've experienced a loss of appetite and don't enjoy food anymore.
```

### Outputs

```
Predicted Disease

Depression

Suggested Prescription

Antidepressants; eating nutrient-rich foods.
```

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/animesh-jsr/Medical-Diagnosis-and-Prescription-Recommendation.git
```

Move into the project directory

```bash
cd Medical-Diagnosis-and-Prescription-Recommendation
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
tensorflow
numpy
pandas
matplotlib
scikit-learn
jupyter
```

---

# 📈 Future Improvements

- Bidirectional LSTM
- Attention Mechanism
- Transformer-based models (BERT/ClinicalBERT)
- Streamlit Web Application
- Explainable AI
- Medical Knowledge Graph Integration
- Confidence Score Visualization

---

# 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Natural Language Processing
- Deep Learning
- Multi-task Learning
- TensorFlow Functional API
- Text Classification
- Sequence Modeling
- Medical AI Applications

---

# 👨‍💻 Author

**Animesh Kumar**

🎓 Production & Industrial Engineering  
National Institute of Technology Jamshedpur

- GitHub: https://github.com/animesh-jsr
- LinkedIn: https://www.linkedin.com/in/animeshnit

---

