# 🧠 Week-2: LSTM Baseline Model – Disaster Tweet Classification

## 📘 Overview
This week’s milestone focuses on developing a **baseline deep learning model** for disaster tweet classification using **LSTM (Long Short-Term Memory)** architecture.  
The model learns to identify whether a tweet is related to a real-world disaster, forming the foundation for later comparison with transformer-based models (e.g., BERT) in upcoming weeks.

Dataset used: [Kaggle – NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started)

---

## 🚀 Work Completed This Week
- Performed **data cleaning and preprocessing** (removal of URLs, hashtags, and symbols).  
- Conducted **EDA** to visualize tweet lengths and class balance.  
- Implemented **Bidirectional LSTM model** using TensorFlow/Keras.  
- Trained model for 5 epochs and achieved ~82 % validation accuracy.  
- Saved training metrics and model artifacts for reproducibility.

---

## 📂 Files in This Repository

| File | Description |
|------|--------------|
| `week2_lstm_baseline.ipynb`** | Main Jupyter Notebook containing all steps – data loading, preprocessing, EDA, model building, training, and evaluation. |
| **`training_history.json`** | JSON file storing training/validation accuracy and loss per epoch, used to recreate plots without retraining. |
| **`.ipynb_checkpoints/`** | Auto-generated backup folder created by Jupyter; safe to ignore. |
| **`lstm_baseline.h5`** | *(Not uploaded)* Trained model file excluded because GitHub restricts uploads > 100 MB. The file is available via Google Drive or on request. |

---

##  Model Summary
- **Embedding layer:** 20 000 vocab × 128 dims  
- **Bidirectional LSTM:** 64 units (dropout 0.3)  
- **Dense + Dropout:** 64 ReLU + 0.4 dropout  
- **Output:** Sigmoid (1 = disaster, 0 = non-disaster)

---

##  Evaluation (Initial Baseline)
| Metric | Training | Validation |
|--------|-----------|------------|
| Accuracy | ~85 % | ~82 % |
| F1-Score | — | ~0.81 |

---

## 🧩 Notes
> The trained model file `lstm_baseline.h5` exceeded GitHub’s 100 MB limit and was therefore omitted.  
> A compressed version or Google Drive link can be provided if required for verification.

---

## 🗓️ Next Steps
- Fine-tune a **BERT/DistilBERT** model for contextual understanding.  
- Compare results with LSTM baseline using F1-score and recall metrics.  
- Add confusion-matrix visualizations and parameter-tuning analysis.

---

**Author:** Alla Mahitha Sri Varshini
*Deep Learning for Disaster Management – Intermediate Update 1*
