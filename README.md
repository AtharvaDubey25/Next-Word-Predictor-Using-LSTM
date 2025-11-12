# 🧠 Next Word Predictor

A simple **Next Word Prediction** model built using **LSTM** in **Keras**.  
It predicts the next most probable word in a sequence, demonstrating the basics of **NLP** and **text generation**.

---

## 🚀 Overview
The model learns from text data (e.g., *Sherlock Holmes excerpts*) and predicts the next word based on prior context using an **Embedding → LSTM → Dense** architecture.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Framework:** TensorFlow / Keras  
- **Libraries:** NumPy, Scikit-learn  
- **Environment:** Jupyter Notebook / Google Colab

---

## ⚙️ Model Architecture
Embedding → LSTM(150) → Dense(Softmax)

---

## 📚 Workflow
1. **Data Preparation:** Tokenize and clean text, create word sequences.  
2. **Model Training:** Train LSTM with categorical crossentropy + Adam optimizer.  
3. **Prediction:** Generate the next word from user input.

---

## 💻 Example
```python
Input: "He never spoke of the softer"
Output: "passions"
