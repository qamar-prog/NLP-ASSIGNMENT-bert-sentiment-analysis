# Transformer-Based Sentiment Analysis with Explainability

##  Project Overview
This project implements a Transformer-based NLP model using BERT for sentiment classification on the Amazon Polarity dataset. The model is analyzed using attention mechanisms and explainability techniques such as SHAP and LIME.

---

##  Dataset
- Source: Hugging Face (Amazon Polarity)
- Type: Binary classification (Positive / Negative)
- Size:
  - Train: 3.24M
  - Validation: 360K
  - Test: 400K

---

##  Model
- Model: BERT (bert-base-uncased)
- Fine-tuned for sentiment classification
- Framework: PyTorch + Transformers

---

##  Performance
| Metric | Score |
|--------|------|
| Accuracy | 94.86% |
| Precision | 94.93% |
| Recall | 94.89% |
| F1 Score | 94.91% |

---

##  Explainability

### SHAP
- Provides feature importance for each token
- Shows how words affect prediction

### LIME
- Explains individual predictions locally
- Faster but less stable than SHAP

---

##  Visualizations
- Attention heatmaps
- Confusion matrix
- SHAP explanations
- LIME explanations
- Runtime comparison graphs

---

##  Error Analysis
Some misclassifications occurred due to:
- Negation (e.g., "not bad")
- Sarcasm
- Ambiguous sentences

---

##  How to Run

1. Open the notebook in Google Colab
2. Install dependencies:


3. Run all cells step-by-step

---

##  Files Included
- `assignment.ipynb` → Full implementation
- `report.pdf` → Detailed report
- `README.md` → Project documentation

---

##  Features
- Transformer-based NLP model
- Attention visualization
- SHAP & LIME explainability
- Real-time prediction interface

---

##  Conclusion
The BERT model achieved high accuracy and demonstrated strong performance. Explainability techniques provided valuable insights into model decisions and limitations.

---
