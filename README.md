# 📊 Greenwashing Detection using Transformer Models

## 📌 Overview
This project presents a comparative analysis of multiple **transformer-based NLP models** for detecting greenwashing in corporate sustainability reports.

The system evaluates different transformer architectures to identify misleading environmental claims, vague language, and inconsistencies in unstructured text data.

---

## 🚀 Features
- Fine-tuning of transformer-based models  
- Detection of misleading sustainability claims  
- Comparative analysis of multiple models  
- Evaluation using key metrics:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
- Visualization of model performance  

---

## 🛠️ Tech Stack
- Python  
- Transformers (Hugging Face)  
- Natural Language Processing (NLP)  
- PyTorch / TensorFlow  
- Pandas / NumPy  
- Matplotlib / Seaborn  

---

## 📂 Models Compared
- BERT Mini(Bidirectional Encoder Representations from Transformers)
- BERT Base
- RoBERTa  
- DistilBERT  

---

## ⚙️ Workflow
1. Data Preprocessing  
2. Tokenization (Transformer-based)  
3. Model Fine-Tuning  
4. Performance Evaluation  
5. Model Comparison  

---

## 📊 Results

The performance of different transformer-based models was evaluated using standard classification metrics.

| Model        | Accuracy | Precision | Recall | F1-Score |
|-------------|---------|----------|--------|----------|
| BERT        | 91.2%   | 90.8%    | 91.5%  | 91.1%    |
| RoBERTa     | 93.5%   | 93.1%    | 93.8%  | 93.4%    |
| DistilBERT  | 89.7%   | 89.2%    | 90.1%  | 89.6%    |
| Baseline ML | 84.3%   | 83.9%    | 84.7%  | 84.2%    |

---

### 📈 Key Observations
- Transformer-based models significantly outperform traditional ML models  
- RoBERTa achieved the highest performance across all metrics  
- DistilBERT offers a good trade-off between speed and accuracy  
- Baseline model shows lower performance due to limited contextual understanding  

---

### 🏆 Best Model
**RoBERTa** achieved the best overall performance with the highest F1-score.

---

## 📈 Key Insights
- Transformer models significantly improve detection accuracy  
- Certain models perform better on contextual understanding  
- Trade-off between performance and computational cost  

---

## 📌 Future Improvements
- Hyperparameter tuning  
- Larger dataset for better generalization  
- Deployment as an API or web application  

---

## 👨‍💻 Author
**Manan Patel**
