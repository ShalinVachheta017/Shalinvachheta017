# Shalin Vachheta

**Machine Learning · MLOps · Applied AI**  
M.Sc. Mechatronics · University of Siegen, Germany

[Portfolio (English)](https://shalinvachheta017.github.io/ShalinV_Portfolio/) · [Portfolio (Deutsch)](https://shalinvachheta017.github.io/ShalinV_Portfolio/de/) · [LinkedIn](https://www.linkedin.com/in/shalin-vachheta/) · [Email](mailto:shalin2010vachheta@gmail.com)

## About me

I build machine learning models and the software around them. During my master's in Mechatronics at the University of Siegen, I became particularly interested in what happens after a model is trained: how it behaves with new data, whether its evaluation is trustworthy, and how it can become part of a working application.

My projects cover wearable-sensor activity recognition, document search, event prediction, text summarization, and ML deployment. Some experiments worked well; others revealed difficult problems. I value understanding those differences and making the next engineering decision based on evidence.

## Selected projects

### 01 · [Wearable Activity Recognition — MLOps](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline)

For my master's thesis, I developed an offline-first pipeline that classifies **11 activities** from smartwatch accelerometer and gyroscope data. It also monitors prediction confidence, uncertainty, unusual activity transitions, and sensor-data drift.

The key finding was the difference between **93.61% accuracy in within-distribution five-fold cross-validation** and **44.42% mean accuracy in leave-one-user-out evaluation**. These are different test settings, and the drop made generalization and human-reviewed monitoring central to the project.

*Python · TensorFlow · 1D-CNN–BiLSTM · FastAPI · Docker · MLflow · DVC*

[Interactive case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/thesis.html) · [Architecture and monitoring code](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline)

### 02 · [Multilingual Tender RAG — Privacy-first Document Search](https://github.com/ShalinVachheta017/multilingual-tender-rag)

I built a privacy-first document assistant for searching German tender documents and answering questions in English or German. The documented collection contains **6,126 documents**. Working with PDFs, metadata, multilingual retrieval, and source-aware answers taught me that finding reliable evidence is often harder than generating fluent text.

The current prototype uses locally operated Qdrant and Ollama components to avoid relying on external language-model APIs for document answers. This is a **design choice for data control**, not a claim of completed cloud scaling or production security certification.

*Python · Qdrant · Jina v3 · Ollama · Streamlit · FastAPI*

[Interactive case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/rag.html) · [Retrieval implementation](https://github.com/ShalinVachheta017/multilingual-tender-rag/blob/main/src/core/search.py)

### 03 · [Vehicle Insurance — ML Pipeline & AWS](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline)

I connected data ingestion, validation, transformation, model training, and inference with a FastAPI application, Docker packaging, GitHub Actions, and AWS deployment components. It helped me understand how model artifacts, application code, and infrastructure fit together.

Earlier model performance numbers are **withheld pending leakage-free reevaluation**. The engineering workflow is documented without presenting it as a proven production insurance service.

*Python · scikit-learn · FastAPI · Docker · GitHub Actions · AWS S3/ECR/EC2*

[Interactive case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/insurance.html) · [AWS workflow](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline/blob/main/.github/workflows/aws.yaml)

### 04 · [Seq2Seq Event Prediction](https://github.com/ShalinVachheta017/seq2seq-event-prediction)

As a student research assistant, I worked on predicting future event sequences from simulation data using a BiLSTM encoder–decoder. The work involved experiments, model tuning, and careful evaluation of sequential data.

*Python · BiLSTM · Seq2Seq · Optuna*

[Research case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/seq2seq.html)

### 05 · [PEGASUS Dialogue Summarization](https://github.com/ShalinVachheta017/pegasus-dialogue-summarization)

I adapted a PEGASUS model for summarizing conversations from the SAMSum dataset, with modular training, evaluation, and a FastAPI prediction route. The challenge is preserving meaning while shortening a dialogue.

*Transformers · Hugging Face · PEGASUS · FastAPI*

[Project case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/pegasus.html)

## Other hands-on work

- [Kubernetes Mini Project](https://github.com/ShalinVachheta017/k8s_pra_proj_mlops-E17) — Tested pod self-healing and Service load balancing with Docker, Flask, and Minikube. [See the case study](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/kubernetes.html).
- [Student Performance Prediction](https://github.com/ShalinVachheta017/Student-Performance-Prediction) — Regression modeling, feature engineering, and a small web application.

## Engineering tools

**ML and data:** Python, pandas, NumPy, scikit-learn, PyTorch, TensorFlow, XGBoost  
**Applications and MLOps:** FastAPI, Flask, Docker, pytest, MLflow, DVC, GitHub Actions  
**Document AI:** Qdrant, Jina, Ollama, Hugging Face  
**Cloud and infrastructure:** AWS S3, ECR, EC2; hands-on Kubernetes/Minikube

---

You can explore the **[English](https://shalinvachheta017.github.io/ShalinV_Portfolio/)** or **[German](https://shalinvachheta017.github.io/ShalinV_Portfolio/de/)** portfolio for project architecture, technical decisions, evaluation evidence, and source-code links.
