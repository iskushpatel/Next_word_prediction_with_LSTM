# ✍️ Next Word Prediction using LSTM

## 📌 Overview
This project implements a **Next Word Prediction system** using a **Long Short-Term Memory (LSTM)** neural network.  
Given a sequence of words, the model predicts the **most likely next word**, learning language patterns from text data.
The model is trained on **Shakespeare’s Hamlet** text and deployed using **Streamlit** for interactive predictions.

---
## 🔗 Live Demo
[![Streamlit App](https://img.shields.io/badge/Streamlit-Live%20App-red?logo=streamlit)]([https://moviereview-sentimentanalysis-c7zaqpkvasjmaavhrhqeeb.streamlit.app/](https://nextwordpredictionwithlstm-rv2d7mn66ydhveu7heauvq.streamlit.app/))

---
## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Scikit-learn  
- Streamlit  
---

## ✨ Key Features
- Text cleaning and tokenization  
- Sequence generation for language modeling  
- LSTM-based deep learning model  
- Next-word prediction using probability distribution  
- Interactive Streamlit web application
---

## 🚀 How to Run the Project
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to the project directory
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit application
streamlit run app.py
```
----
## 🧠 Model Architecture
- **Embedding Layer** – converts words into dense vector representations  
- **LSTM Layer** – captures long-term dependencies in text sequences  
- **Dense Output Layer** – softmax activation for next-word prediction  
**Optimizer:** Adam  
**Loss Function:** Categorical Cross-Entropy  
---

## 📈 Model Performance
| Metric                  | Value / Description |
|-------------------------|---------------------|
| Training Dataset        | Shakespeare’s *Hamlet* |
| Model Type              | LSTM (Next Word Prediction) |
| Vocabulary Size         | ~6,000–8,000 words |
| Sequence Length         | 50 tokens |
| Training Loss           | Reduced consistently during training |
| Early Stopping          | Enabled |
| Prediction Output       | Probability distribution over vocabulary |
| Prediction Strategy    | Word with highest probability |
| Performance Behavior   | Context-aware and grammatically consistent predictions |
---
## 🖥️ Application Features
- Enter a sequence of words  
- Instantly predict the next word  
- Simple and clean Streamlit interface  
