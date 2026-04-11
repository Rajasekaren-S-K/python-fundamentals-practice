<div align="center">

# 🚀 Hope AI — Master Program Journey
### Applied AI · Generative AI · Data Science

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-EC4E20?style=for-the-badge)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-Agents-1C3C3C?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress-brightgreen?style=for-the-badge)

> **Documenting every week of my Hope AI Master Program** — from Python foundations to AI Agents, RAG pipelines, LangChain, LangGraph, and MCP. Every notebook is hands-on, project-backed learning.

</div>

---

## 🎯 About This Repositoryh

This repository is my **public learning journal** for the [Hope AI](https://www.hopelearning.net) Master Program in Applied AI, Generative AI & Data Science — a structured, mentor-guided program covering the complete AI engineering stack in Tamil + English.

Every week = a dedicated folder with notebooks, assignments, and notes from real hands-on practice.

---

## 📊 Full Curriculum Progress

| Week | Module | Topics | Status | Folder |
|------|--------|---------|--------|--------|
| Week 0 | **Ground Work** | Environment setup, tools, developer mindset | ✅ Done | — |
| Week 1 | **Travel Path** | AI roadmap, career clarity, learning strategy | ✅ Done | — |
| Week 2 | **Python** | Core Python — syntax, data structures, OOP, functions | ✅ Done | Week_2/ |
| Week 3 | **ML — Regression** | EDA, feature engineering, Linear/DT/RF/GBM/AdaBoost/XGBoost, R² | ✅ Done | Week_3/ |
| Week 4.1 | **ML — Classification** | Logistic Regression, SVM, KNN, Decision Trees, evaluation metrics | 🔜 | — |
| Week 4.2 | **ML — Clustering** | K-Means, DBSCAN, Hierarchical clustering, silhouette score | 🔜 | — |
| Week 4.3 | **Practice — Coding & Error Handling** | Real-world ML debugging, pipelines, code quality | 🔜 | — |
| Week 5 | **Data Science — Univariate Analysis** | Distributions, central tendency, spread, outlier detection | 🔜 | — |
| Week 6 | **Data Science — Bivariate Analysis** | Correlation, cross-tabs, pair plots, statistical relationships | 🔜 | — |
| Week 7 | **Data Visualization** | Seaborn, Tableau, Data Studio — storytelling with data | 🔜 | — |
| Week 8.1 | **Advanced ML — Feature Selection** | Filter, wrapper, embedded methods, importance ranking | 🔜 | — |
| Week 8.2 | **Advanced ML — Dimensionality Reduction** | PCA, LDA, t-SNE, UMAP | 🔜 | — |
| Week 9.1 | **ML & DS Capstone Project** | End-to-end ML project — problem to deployment | 🔜 | — |
| Week 9.2 | **Web Development — Shortcut Way** | Streamlit / Gradio for AI apps | 🔜 | — |
| Week 9.3 | **Web Development — Detailed Way** | Flask/FastAPI for model serving | 🔜 | — |
| Week 10 | **Recommendation System** | Collaborative & content-based filtering, matrix factorization | 🔜 | — |
| Week 10.1 | **MySQL** | Databases for AI — queries, joins, data pipelines | 🔜 | — |
| Week 11 | **Deep Learning** | Neural networks, CNNs, backprop, PyTorch fundamentals | 🔜 | — |
| Week 12 | **Time Series Analysis** | ARIMA, LSTM, forecasting, seasonality, trend decomposition | 🔜 | — |
| Week 13 | **Natural Language Processing** | Tokenization, TF-IDF, text classification, sentiment analysis | 🔜 | — |
| Week 13.1 | **NLP + Deep Learning (GenAI)** | Transformers, BERT, sequence models, text generation | 🔜 | — |
| Week 14 | **ChatGPT API — Advanced Techniques** | Prompt engineering, function calling, structured outputs | 🔜 | — |
| Week 15 | **Real-Time Apps with ChatGPT API** | Building production AI apps with OpenAI API | 🔜 | — |
| Week 16 | **RAG — Retrieval Augmented Generation** | Vector DBs, embeddings, FAISS, semantic search, RAG pipelines | 🔜 | — |
| Week 17 | **Deployment — Google Cloud Platform** | GCP, Cloud Run, model serving, CI/CD for ML | 🔜 | — |
| Week 18 | **AI Agents** | Autonomous agents, tool use, planning, memory | 🔜 | — |
| Week 19 | **AWS SageMaker AI** | Cloud ML — training, endpoints, pipelines on AWS | 🔜 | — |
| Week 20 | **LangChain — AI Agent Framework** | Chains, tools, memory, LangChain agents in production | 🔜 | — |
| Week 21 | **LangGraph — AI Agent Framework** | Stateful agents, graph-based workflows, multi-agent systems | 🔜 | — |
| Week 22 | **MCP** | Model Context Protocol — next-gen AI integrations | 🔜 | — |

---

## 🔬 Week 3 Deep Dive — Regression Analysis

> **Assignment:** Insurance Charges Prediction | Supervised ML | 6 Models Benchmarked

```
Dataset   : insurance_pre.csv
Target    : Medical insurance charges (cost prediction)
Features  : age, sex, bmi, children, smoker
Split     : 70% Train / 30% Test
Scaler    : StandardScaler
Metric    : R² Score
```

| Model | Category | Technique |
|-------|----------|-----------|
| Linear Regression | Baseline | Ordinary Least Squares |
| Decision Tree | Tree-based | Recursive partitioning |
| Random Forest | Ensemble | Bagging + feature randomness |
| Gradient Boosting | Boosting | Sequential residual fitting |
| AdaBoost | Boosting | Adaptive sample weighting |
| XGBoost | Boosting | Regularized gradient boosting |

**Pipeline:** EDA → IQR Outlier Removal → Label Encoding → StandardScaler → Train/Test Split → Model Training → R² Comparison → Best Model Selection

---

## 🛠️ Tech Stack

```python
current = {
    "Language"    : "Python 3.8+",
    "Environment" : "Jupyter Notebook (Anaconda)",
    "ML"          : ["Scikit-Learn", "XGBoost"],
    "Data"        : ["Pandas", "NumPy"],
    "Viz"         : ["Matplotlib", "Seaborn"],
}

coming_soon = {
    "Deep Learning" : ["PyTorch", "TensorFlow"],
    "GenAI"         : ["OpenAI API", "LangChain", "LangGraph"],
    "RAG"           : ["FAISS", "ChromaDB", "LlamaIndex"],
    "Deploy"        : ["FastAPI", "Streamlit", "Docker", "GCP", "AWS SageMaker"],
    "Agents"        : ["LangGraph", "MCP", "Tool Use"],
}
```

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Rajasekaren-S-K/12-Week-AI-Engineering-Journey.git
cd 12-Week-AI-Engineering-Journey

# Launch Jupyter
jupyter notebook
```

---

## 💡 Why This Exists

> *"Most people consume AI. I'm here to build it."*

This repository is proof of structured, week-by-week effort through the **Hope AI Master Program** — covering the entire AI engineering stack from Python to autonomous AI agents. Every notebook represents a real skill added, not a tutorial copied.

---

<div align="center">

**⭐ Star this repo to follow the journey — new weeks added regularly!**

*Powered by [Hope AI](https://www.hopelearning.net) · Building in public. One week at a time. 🔥*

</div>
