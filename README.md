# 🧪 MLflow & DagsHub Practice Repository

This repository contains code, experiments, and notes from my learning journey with **MLflow** and **DagsHub** — powerful tools used in Machine Learning experiment tracking, model management, and collaborative ML workflow development.

---

## 📖 What is MLflow?

**MLflow** is an open-source platform designed to manage the end-to-end machine learning lifecycle. It helps track experiments, package code into reproducible runs, and manage and deploy models.

### ✨ Features:
- 🔍 **Experiment Tracking**: Record and query experiments (code, data, config, metrics)
- 📦 **Model Packaging**: Save and load models in multiple formats
- 🚀 **Model Deployment**: Serve models via REST API or export to other tools
- 📁 **Project Reproducibility**: Encapsulate code in MLflow Projects

### ✅ Use Cases:
- Comparing different hyperparameters in model training
- Reproducing and auditing past experiments
- Versioning and sharing models with teams

### 🌍 Real-World Scenario:
> A data science team at a retail company uses MLflow to track daily model training jobs for customer churn prediction. By comparing metrics and parameters visually, they rapidly iterate and find the best-performing model.

---

## 📦 What is DagsHub?

**DagsHub** is a web-based platform built on top of Git and DVC that allows teams to **collaborate on data science projects**. It provides a GitHub-like interface for version control of data, code, models, and experiments.

### ✨ Features:
- 📊 MLflow integration for experiment tracking
- 🧬 DVC-based versioning for data and models
- 📘 Jupyter notebook rendering
- 🔗 Git/GitHub-based repo management

### ✅ Use Cases:
- Team collaboration on ML pipelines with versioned data and models
- Hosting ML projects with integrated MLflow dashboards
- Reviewing model performance and training history

### 🌍 Real-World Scenario:
> A healthcare AI startup uses DagsHub to collaborate across teams—engineers push model updates, while analysts review data versions and experiment logs, all in one platform. With MLflow integrated, they track which model version is deployed in production.

---

## 🔬 What You’ll Find in This Repo

- ✅ Code for MLflow tracking (manual and automated logging)
- ✅ Experiments tracked using MLflow UI
- ✅ ML project setup with DVC (for optional DagsHub push)
- ✅ Steps to connect and push code to DagsHub
- ✅ Notes and references for ML lifecycle management

---

## 📎 Getting Started

1. Clone the repo
2. Set up a virtual environment and install dependencies
3. Run MLflow and track experiments locally
4. Push experiments and data to DagsHub (if configured)

---

## 🧠 Useful Resources

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [DagsHub Documentation](https://dagshub.com/docs/)
- [DVC Docs](https://dvc.org/doc)

---

## 💬 Feedback & Contributions

Feel free to raise an issue or contribute if you find something useful or want to improve the setup!

---
