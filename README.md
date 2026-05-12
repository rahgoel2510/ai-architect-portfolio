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

| # | Module | Skills Learned |
|---|--------|---------------|
| 01 | LLM Evaluation | Model benchmarking, evaluation metrics |
| 02 | Model Selection | Performance vs. cost trade-offs |
| 03 | Vector Database | Embedding storage, retrieval optimization |
| 04 | RAG Pipeline | End-to-end RAG architecture |
| 05 | MLOps | CI/CD, drift monitoring, retraining |
| 06 | Cloud Deployment | Serverless AI, scalability |
| 07 | Observability | Latency, throughput, error monitoring |
| 08 | Compliance | GDPR, secure data handling, anonymization |
| 09 | Prompt Engineering | Reliability, bias reduction |
| 10 | Agentic Systems | Multi-step reasoning, tool orchestration |

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
