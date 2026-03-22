
# 🚀 PySpark & Scalable ML Projects

## 📌 Overview

This repository contains **5 projects** demonstrating **distributed data processing, machine learning, and AI integration**, with a strong focus on **PySpark-based scalable pipelines**.

---

## ⚙️ Tech Stack

PySpark • Spark MLlib • Python • Pandas • Matplotlib • TensorFlow • PyTorch • NLP • LangChain • HuggingFace

---

# 📂 Projects

## 1. K-Means Clustering using PySpark

### Objective

* Perform clustering on automobile dataset using distributed processing

### Key Implementation

* RDD-based data ingestion and transformation
* Feature engineering using broadcast variables
* Vectorization using MLlib
* KMeans clustering (k=3)

```python
kmeans = KMeans(k=3, seed=1)
model = kmeans.fit(autoDF)
```

### Concepts Used

* RDD → DataFrame pipeline
* Distributed scaling
* MLlib clustering

---

## 2. Predictive Maintenance (ML)

### Objective

* Predict machine condition using sensor data

### Key Implementation

* Feature preprocessing + scaling
* Random Forest model training
* Model evaluation using classification metrics

### Concepts Used

* Supervised learning
* Feature importance
* Industrial ML use-case

---

## 3. Image Classification (CNN)

### Objective

* Classify images using deep learning (CIFAR-10)

### Key Implementation

* CNN architecture using TensorFlow/Keras
* Image normalization + training pipeline
* Accuracy evaluation and prediction

### Concepts Used

* Computer Vision
* Deep Learning (CNN)
* Model evaluation

---

## 4. Sentiment Analysis (NLP)

### Objective

* Classify tweet sentiment (Positive/Negative/Neutral)

### Key Implementation

* Text preprocessing (tokenization, stemming)
* Feature extraction using n-grams
* Models: Logistic Regression, SVM

### Concepts Used

* NLP pipeline
* Text vectorization
* Classification

---

## 5. GPT Language Model (From Scratch)

### Objective

* Build transformer-based language model using PyTorch

### Key Implementation

* Character-level tokenization
* Self-attention + transformer blocks
* Text generation pipeline

### Concepts Used

* Transformers
* Sequence modeling
* Generative AI

---

# 🔗 Additional Module: LLM Integration

### Implementation

* HuggingFace + LangChain integration
* Prompt engineering + inference pipelines

```python
llm.invoke("What is machine learning")
```

---

# 🧠 Core Skills Demonstrated

### PySpark & Big Data

* RDD transformations (`map`, `filter`)
* DataFrame operations
* Broadcast variables
* Distributed feature engineering
* MLlib model training

### Machine Learning

* Supervised + Unsupervised models
* Feature engineering + scaling
* Model evaluation

### Deep Learning & AI

* CNN (Computer Vision)
* Transformers (LLMs)
* NLP pipelines

---

# 📊 Outcomes

* Built scalable data pipelines using PySpark
* Implemented distributed + local ML workflows
* Integrated traditional ML with modern AI systems

---

# 📁 Files Reference

* PySpark Clustering → 
* Extended PySpark Pipeline → 
* LLM Integration → 

---

# 🚀 Future Scope

* Spark Streaming (real-time pipelines)
* ML Pipeline API (end-to-end workflows)
* Cloud deployment (Databricks / AWS EMR)
* Model serving APIs

---

# 🧩 Key Takeaways

* PySpark enables scalable and production-grade ML pipelines
* Combining Spark + ML + LLMs creates high-impact systems
* Strong foundation across **Data Engineering + AI + ML stack**

