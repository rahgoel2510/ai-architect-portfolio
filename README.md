# 🏗️ Enterprise-Scale AI System with RAG + MLOps

A comprehensive project demonstrating Senior AI Architect skills: building a Retrieval-Augmented Generation (RAG) system deployed on the cloud with monitoring, compliance, and optimization.

## 📂 Project Structure

```
ai-architect-project/
├── notebooks/
│   ├── 01_llm_evaluation.ipynb      # Model benchmarking & evaluation
│   ├── 02_model_selection.ipynb     # Performance vs. cost trade-offs
│   ├── 03_vector_db.ipynb           # Embedding storage & retrieval
│   ├── 04_rag_pipeline.ipynb        # End-to-end Q&A with LangChain
│   ├── 05_mlops.ipynb               # CI/CD, versioning, drift monitoring
│   ├── 06_cloud_deployment.ipynb    # Serverless AI on AWS
│   ├── 07_observability.ipynb       # Metrics & monitoring
│   ├── 08_compliance.ipynb          # GDPR & privacy by design
│   ├── 09_prompt_engineering.ipynb  # Reliable prompt crafting
│   └── 10_agentic_systems.ipynb     # Autonomous multi-step agents
├── requirements.txt
└── README.md
```

## 🚀 Quick Start

### 1. Create Environment

```bash
conda create -n ai_architect python=3.11 -y
conda activate ai_architect
pip install -r requirements.txt
```

### 2. Set API Keys

Get a free API key from [OpenRouter](https://openrouter.ai/keys):

```bash
export OPENROUTER_API_KEY="your-key"
export PINECONE_API_KEY="your-key"  # only needed for notebook 03
```

### 3. Launch Notebooks

```bash
jupyter notebook notebooks/
```

## 📋 Module Overview

| # | Module | Run in Colab |
|---|--------|-------------|
| 01 | LLM Evaluation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/01_llm_evaluation.ipynb) |
| 02 | Model Selection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/02_model_selection.ipynb) |
| 03 | Vector Database | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/03_vector_db.ipynb) |
| 04 | RAG Pipeline | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/04_rag_pipeline.ipynb) |
| 05 | MLOps | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/05_mlops.ipynb) |
| 06 | Cloud Deployment | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/06_cloud_deployment.ipynb) |
| 07 | Observability | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/07_observability.ipynb) |
| 08 | Compliance | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/08_compliance.ipynb) |
| 09 | Prompt Engineering | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/09_prompt_engineering.ipynb) |
| 10 | Agentic Systems | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rahgoel2510/ai-architect-portfolio/blob/main/notebooks/10_agentic_systems.ipynb) |

## 🛠️ Tech Stack

- **LLMs**: Meta LLaMA 3.1, Google Gemma 2 (free via OpenRouter)
- **Orchestration**: LangChain
- **Vector DBs**: Pinecone, FAISS, Weaviate
- **MLOps**: MLflow, DVC, Evidently
- **Cloud**: AWS Lambda, API Gateway
- **Observability**: Prometheus, Datadog, OpenTelemetry
- **Compliance**: Presidio, cryptography

## 🎯 Outcomes

- 10 hands-on Jupyter notebooks covering all Senior AI Architect competencies
- Live demo deployable via AWS Lambda or Vercel
- GitHub Pages documentation with Binder/Colab links

## 📄 License

MIT
