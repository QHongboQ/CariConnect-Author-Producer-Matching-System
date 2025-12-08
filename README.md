# **CariConnect Author–Producer Matching System**
### *Break Through Tech AI Studio Project (2025) – Team 1B*  
UCSC • UCSD • UCR • CSULB • SJSU  

---

## 📌 **Overview**
CariConnect is an initiative focused on empowering Caribbean authors by improving their visibility and helping them connect with publishers, literary agents, producers, and creative partners.

Our team is developing a machine-learning system that predicts **author–producer compatibility** based on genre, writing themes, narrative style, and historical adaptation trends.

This project integrates book metadata, production adaptation records, author samples, and agent datasets to create a scalable, AI-assisted matching pipeline that enhances discovery and representation across Caribbean creative industries.

---

## 🎯 **Project Goals**
- Build an end-to-end ML system for matching authors with publishers, agents, and producers  
- Clean, merge, and standardize multi-source datasets (authors, producers, adaptation records)  
- Engineer features from textual and categorical data  
- Train supervised and unsupervised models to predict match likelihood  
- Evaluate performance using **Accuracy, ROC-AUC, Precision, Recall, F1**  
- Provide interpretable topic clusters to help authors identify their creative "neighborhoods"  

---

## 📊 **Current Progress (as of 2025)**

### **Data Processing**
- Integrated **831+ book-to-production adaptation records** and author metadata  
- Standardized genre labels, removed duplicates, and constructed a clean training dataset  
- Explored dominant themes across adaptation history  

### **Modeling**
- Prototyped **Random Forest** classifier achieving:  
  - **~96% accuracy**  
  - **ROC-AUC ≈ 0.99**  
- Explored topic-modeling pipelines:  
  - TF-IDF + **KMeans**  
  - **LDA Topic Modeling**  
  - **BERTopic** (optional)  
- Built similarity-based clustering pipelines for grouping authors and producers  

### **Collaboration**
- Working across **five universities** to design, evaluate, and document the ML system  
- Preparing final model presentation and deliverables for challenge advisors  

---

## 🧠 **Methods & Tools**

### **Languages & Libraries**
- Python, Pandas, NumPy  
- Scikit-Learn  
- TF-IDF Vectorization  
- KMeans Clustering  
- LDA Topic Modeling  
- BERTopic (optional)

### **ML Techniques**
- Data cleaning & feature engineering  
- Text vectorization  
- Supervised classification (Random Forest)  
- Unsupervised clustering / topic modeling  
- Evaluation (Accuracy, ROC-AUC, F1)

---

## 📁 **Repository Structure**

```
caricon-author-matching/
│
├── data/
│   ├── README.md
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── modeling.ipynb
│
├── src/
│   ├── clean_data.py
│   ├── train_model.py
│
├── results/
│   ├── metrics.txt
│
└── README.md
```

---

## 👥 **Team Members — AI Studio 2025**

| Name | University |
|------|------------|
| **Lizbeth Krystal Ramirez** | UC Riverside |
| **Xiaomai Wang** | UCSD |
| **Sabine Loaiza Chable** | UCSD |
| **Mario Zhou** | UC Santa Cruz |
| **Justin Pongos** | CSU Long Beach |
| **Naina Talasu** | San José State University |

---

## 🧑‍🏫 **AI Studio Coach & Challenge Advisors**

| Name | Role |
|------|------|
| **Audra Zook** | AI Studio Coach |
| **Solomon Perkins** | Challenge Advisor |
| **Steve Russell** | Challenge Advisor |

---

## 👤 **Contributor**
**Mario Zhou**  
AI Studio Fellow — Break Through Tech AI 2025  
University of California, Santa Cruz  
GitHub: https://github.com/QHongboQ

---

## 🔮 **Future Work**
- Add transformer-based embeddings (BERT/RoBERTa)  
- Improve hyperparameter optimization  
- Build interactive matching tool / API  
- Expand dataset with additional metadata  
- Visualize author–producer similarity graph  

---

