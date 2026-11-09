# Shalin Vachheta

### Machine Learning Engineer | MLOps | Applied AI

**M.Sc. Mechatronics · University of Siegen, Germany**

[Portfolio](https://shalinvachheta017.github.io/ShalinV_Portfolio/) · [LinkedIn](https://www.linkedin.com/in/shalin-vachheta/) · [Email](mailto:shalin2010vachheta@gmail.com)

## About me

**I completed my master's in Mechatronics at the University of Siegen. Over time, I became interested in what happens after a machine learning model is trained: how it handles new data, how its results are checked, and how to make it useful in a real application.

My projects range from smartwatch activity recognition and document search to event prediction and ML deployment. Some worked well; others showed me how difficult real-world data can be. I enjoy figuring out what went wrong and building a better version.**
---

## Selected Work

These projects show the areas I have worked on most. Start with the short explanation in each README, then continue to the code, results and limitations.

### 01 · [Wearable Human Activity Recognition — MLOps](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline)

**The challenge:** How can we monitor an ML system when new sensor data arrives without labels?

For my master's thesis, I developed an offline-first MLOps pipeline using wearable accelerometer and gyroscope signals to recognize 11 activities.

One of the most important findings came from evaluation. The model achieved **93.61% accuracy in within-distribution five-fold cross-validation**, but mean accuracy dropped to **44.42% when evaluating unseen users using leave-one-user-out validation**.

That difference changed how I viewed model performance. I built monitoring and review mechanisms around prediction confidence, uncertainty, transitions, sensor-data drift, and unusual prediction patterns.

The project taught me that training a model successfully and operating it reliably are two different problems.

**Technologies:** Python, TensorFlow, 1D-CNN–BiLSTM, MLflow, DVC, FastAPI, Docker, pytest.

**[Explore the project](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline)** · **[Inspect monitoring tests](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline/blob/main/tests/test_stage6_monitoring.py)**

### 02 · [Vehicle Insurance — ML Pipeline & AWS MLOps](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline)

**The challenge:** How do you move an ML application from running locally to a repeatable cloud deployment workflow?

I built a modular machine learning pipeline for insurance response prediction, covering data ingestion, validation, transformation, training, evaluation, and model artifacts.

What interested me most was connecting the application to infrastructure outside my laptop. Using Docker, GitHub Actions, AWS S3, ECR, and EC2 helped me understand how application packaging, artifact management, and deployment fit together.

This project strengthened my interest in ML engineering and cloud infrastructure. It also reinforced the importance of evaluating models correctly before trusting their performance numbers.

**Technologies:** Python, scikit-learn, MongoDB, FastAPI, Docker, GitHub Actions, AWS S3/ECR/EC2.

**[Explore the project](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline)** · **[Inspect the deployment workflow](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline/blob/main/.github/workflows/aws.yaml)**

### 03 · [Multilingual Tender Intelligence — RAG](https://github.com/ShalinVachheta017/multilingual-tender-rag)

**The challenge:** How can an AI assistant answer questions using a specific collection of documents rather than relying only on a language model's general knowledge?

My interest in conversational AI led me to build a local multilingual RAG prototype for German tender documents.

Working with a documented collection of **6,126 documents** introduced practical challenges in PDF processing, OCR, embeddings, vector search, multilingual retrieval, and source-aware answer generation.

I learned that finding the right information can be harder than generating the final answer. Early evaluations showed weaknesses in some retrieval scenarios, especially exact-ID lookups and cross-language searches, and gave me a clearer direction for improving the system.

**Technologies:** Python, Jina Embeddings v3, Qdrant, BM25, Ollama, FastAPI, Streamlit.

**[Explore the project](https://github.com/ShalinVachheta017/multilingual-tender-rag)** · **[Inspect retrieval code](https://github.com/ShalinVachheta017/multilingual-tender-rag/blob/main/src/core/search.py)**

---

## How I Approach Engineering Problems

I'm still learning, but a few principles have become important in my work:

- **Understand the data first.** A good model cannot compensate for incorrect assumptions about the dataset.
- **Evaluate beyond a single score.** Baselines, data splits, generalization, and failure cases matter.
- **Make experiments reproducible.** Configuration, versioning, and documentation make it easier to improve a system.
- **Think beyond the notebook.** APIs, containers, automation, and monitoring are part of making ML useful.
- **Be willing to revisit decisions.** When something doesn't work as expected, understanding why is part of the engineering process.

---

## Other Projects

| Project | What I explored |
|---|---|
| [Seq2Seq Event Prediction](https://github.com/ShalinVachheta017/seq2seq-event-prediction) | Event-sequence modeling, BiLSTM encoder-decoder, cross-validation and tuning |
| [PEGASUS Dialogue Summarization](https://github.com/ShalinVachheta017/pegasus-dialogue-summarization) | Transformer fine-tuning, SAMSum, NLP evaluation, FastAPI |
| [Student Performance Prediction](https://github.com/ShalinVachheta017/Student-Performance-Prediction) | Regression, XGBoost, feature engineering, Flask, Docker |

---

## Tools I Work With

| Area | Technologies |
|---|---|
| **Machine Learning & Data** | Python, pandas, NumPy, scikit-learn, XGBoost |
| **Deep Learning** | PyTorch, TensorFlow, CNNs, LSTMs, Transformers |
| **GenAI & NLP** | Hugging Face, RAG, Qdrant, Jina, Ollama |
| **MLOps & Software** | MLflow, DVC, Docker, FastAPI, Flask, pytest, GitHub Actions |
| **Cloud** | AWS S3, ECR, EC2 |

**Still learning:** more about operating ML systems at scale, especially observability, infrastructure and reliable cloud workflows.

---

## Beyond the Projects

I completed my M.Sc. in Mechatronics at the University of Siegen in 2026 and worked as a Student Research Assistant on deep learning for sequential event prediction.

I enjoy exploring problems where machine learning, software engineering, and real-world constraints meet. I'm particularly interested in opportunities to contribute to ML engineering, MLOps, Data Science, and applied AI systems.

[**View my portfolio**](https://shalinvachheta017.github.io/ShalinV_Portfolio/) · [**Connect on LinkedIn**](https://www.linkedin.com/in/shalin-vachheta/) · [**Get in touch**](mailto:shalin2010vachheta@gmail.com)
