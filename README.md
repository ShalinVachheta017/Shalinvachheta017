# Shalin Vachheta

**Machine Learning | MLOps | Applied AI**  
M.Sc. Mechatronics, University of Siegen, Germany

I build machine learning models and the software that makes them usable. My work connects deep learning research with reliable evaluation, APIs, monitoring, and deployment. I care about understanding why a system works, where it struggles, and what it would take to improve it.

**Open to full-time junior roles in Machine Learning Engineering, MLOps, and Applied AI.** Based in Germany and open to relocation.

[Portfolio (English)](https://shalinvachheta017.github.io/ShalinV_Portfolio/) | [Portfolio (Deutsch)](https://shalinvachheta017.github.io/ShalinV_Portfolio/de/) | [LinkedIn](https://www.linkedin.com/in/shalin-vachheta/) | [Email](mailto:shalin2010vachheta@gmail.com)

## Selected engineering work

### 1. Wearable activity recognition: beyond a single accuracy score

**Problem:** Can a model trained on smartwatch sensor data recognize activities from people it has never seen?

For my master's thesis, I built an offline-first MLOps pipeline for **11 activities**, including data checks, inference, risk monitoring, and human-reviewed model updates. The model reached **93.61% accuracy** in within-distribution cross-validation, but only **44.42% mean accuracy** when evaluated with leave-one-user-out testing. The gap showed why generalization and monitoring matter as much as model training. This is a research prototype, not a clinical system.

[Source code](https://github.com/ShalinVachheta017/wearable-har-mlops-pipeline) | [Architecture and evaluation](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/thesis.html)

### 2. Privacy-first RAG: finding evidence in long documents

**Problem:** How can people search technical documents in English or German while retaining control over document processing?

I developed a multilingual RAG prototype working with **6,126 tender documents**, using Jina embeddings, Qdrant, and Ollama. The focus is retrieving relevant passages, supporting answers with sources, and avoiding reliance on external language-model APIs in the current setup. It also taught me how difficult cross-language retrieval and exact document lookups can be.

[Source code](https://github.com/ShalinVachheta017/multilingual-tender-rag) | [Architecture and design choices](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/rag.html)

### 3. Vehicle insurance MLOps: moving beyond the notebook

**Problem:** How do training, model artifacts, an inference service, and deployment fit together?

I developed a modular ML pipeline with **FastAPI, Docker, GitHub Actions, and AWS deployment components**. This project helped me connect data processing and modeling with application and infrastructure decisions. Previous model performance figures are withheld until a leakage-free reevaluation is completed.

[Source code](https://github.com/ShalinVachheta017/vehicle-insurance-mlops-pipeline) | [Pipeline and cloud workflow](https://shalinvachheta017.github.io/ShalinV_Portfolio/cases/insurance.html)

**Technical toolkit:** Python, PyTorch, TensorFlow, scikit-learn, FastAPI, Docker, MLflow, DVC, Qdrant, AWS

For the full project stories, code references, architecture diagrams, and limitations, visit my [portfolio](https://shalinvachheta017.github.io/ShalinV_Portfolio/).
