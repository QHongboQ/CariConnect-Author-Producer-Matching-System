CariConnect Author–Producer Matching System
Break Through Tech AI Studio Project (2025)
Team 1B — UCSC • UCSD • UCR • CSULB • SJSU
📌 Overview

CariConnect is an initiative focused on empowering Caribbean authors by improving their visibility and helping them connect with publishers, literary agents, producers, and creative partners.

Our team is developing a machine-learning system that predicts author–producer compatibility based on genre, writing themes, narrative style, and historical adaptation trends.

This project integrates book metadata, production adaptation records, author samples, and agent datasets to create a scalable, AI-assisted matching pipeline that enhances discovery and representation across Caribbean creative industries.

🎯 Project Goals

Build an end-to-end ML system for matching authors with publishers, agents, and producers

Clean, merge, and standardize multi-source datasets (authors, producers, adaptation records)

Engineer features from textual & categorical data

Train supervised and unsupervised models to predict match likelihood

Evaluate performance via Accuracy, ROC-AUC, Precision, Recall, F1

Provide interpretable topic clusters to help authors identify their creative “neighborhoods”

📊 Current Progress (as of 2025)
Data Processing

Integrated 831+ book-to-production adaptation records and author metadata

Standardized genre labels, removed duplicates, and created a clean training dataset

Explored dominant themes across adaptation history

Modeling

Prototyped Random Forest classification achieving:

~96% accuracy

ROC-AUC ≈ 0.99 (sample dataset)

Conducted topic modeling exploration using:

TF-IDF + KMeans

LDA Topic Modeling

BERTopic

Built similarity-based pipelines to group authors and producers via thematic alignment

Collaboration

Working across five universities to design, evaluate, and document the ML system

Preparing final model presentation and deliverables for challenge advisors

🧠 Methods & Tools
Languages & Libraries

Python, Pandas, NumPy

Scikit-Learn

TF-IDF Vectorization

KMeans Clustering

LDA Topic Modeling

BERTopic (optional)

ML Techniques

Data cleaning & feature engineering

Text vectorization

Supervised classification (Random Forest)

Unsupervised clustering / topic modeling

Evaluation metrics: Accuracy, ROC-AUC, F1

📁 Repository Structure
caricon-author-matching/
│
├── data/
│   ├── README.md           # Data schema + field descriptions (no raw data uploaded)
│
├── notebooks/
│   ├── EDA.ipynb           # Exploratory data analysis
│   ├── modeling.ipynb      # Random Forest + topic modeling prototypes
│
├── src/
│   ├── clean_data.py       # Dataset cleaning and preprocessing
│   ├── train_model.py      # Training pipeline (WIP)
│
├── results/
│   ├── metrics.txt         # Accuracy, ROC-AUC, etc.
│
└── README.md               # Project documentation (this file)

👥 Team Members — AI Studio 2025
Name	University
Lizbeth Krystal Ramirez	UC Riverside
Xiaomai Wang	UCSD
Sabine Loaiza Chable	UCSD
Mario Zhou	UC Santa Cruz
Justin Pongos	CSU Long Beach
Naina Talasu	San José State University
🧑‍🏫 AI Studio Coach & Challenge Advisors
Name	Role
Audra Zook	AI Studio Coach
Solomon Perkins	Challenge Advisor
Steve Russell	Challenge Advisor
📌 Contributor (This Repository)

Mario Zhou
AI Studio Fellow — Break Through Tech AI 2025
University of California, Santa Cruz

GitHub: https://github.com/QHongboQ

🔮 Future Work

Expand dataset with additional author & producer metadata

Implement cross-validation and hyperparameter tuning

Incorporate transformer-based embeddings (e.g., BERT)

Deploy as a REST API / interactive matching tool

Visualize topic clusters in an author–producer similarity map
