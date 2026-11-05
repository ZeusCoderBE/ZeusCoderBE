<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Hi, I'm Quang Huy (Zeus) — AI Engineer. A 3D globe of the tools I work with rotates next to the intro." />
</p>

<p align="center">
  <a href="https://linkedin.com/in/huyhocdata"><b>LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="mailto:hdang1696@gmail.com"><b>hdang1696@gmail.com</b></a> &nbsp;·&nbsp;
  <a href="https://huggingface.co/huyydangg"><b>Hugging Face</b></a> &nbsp;·&nbsp;
  <a href="https://www.tiktok.com/@quanghuyai"><b>TikTok @quanghuyai</b></a>
</p>

## About me

AI Engineer with **2.5+ years** of experience designing, building and optimizing production LLM applications, RAG pipelines and multi-agent systems across **finance, stock market and legal** domains. I work on the whole path from retrieval and agents to LLM serving and the infrastructure that keeps them fast and cheap.

- 💼 AI Engineer at **Mirae Asset Securities Vietnam**
- 🎓 B.Eng. in Data Engineering, **Ho Chi Minh City University of Technology and Engineering**: GPA 3.61/4, 3rd-highest GPA in Data Engineering cohort 21
- 🎯 Working toward **Senior AI Engineer** within the next 3 years
- 🎬 I explain AI topics in Vietnamese on TikTok: [@quanghuyai](https://www.tiktok.com/@quanghuyai)

## Open source

<p align="center">
  <a href="https://huggingface.co/huyydangg/huydang-dek21-embedding">
    <img src="assets/embedding.svg" width="100%" alt="huydang-dek21-embedding: a Vietnamese sentence-embedding model. A 3D embedding space shows a query finding its nearest document clusters." />
  </a>
</p>

[**huydang-dek21-embedding**](https://huggingface.co/huyydangg/huydang-dek21-embedding) is a Vietnamese sentence-embedding model for semantic search and RAG. It was fine-tuned from `bkai-foundation-models/vietnamese-bi-encoder`, works with `sentence-transformers`, and peaked at **400K downloads per month**.

```python
from sentence_transformers import SentenceTransformer

model = SentenceTransformer("huyydangg/huydang-dek21-embedding")
vectors = model.encode(["Thủ tục mở tài khoản chứng khoán", "Điều kiện ký hợp đồng lao động"])
```

## Tech stack

| Area | Tools |
| --- | --- |
| Languages | ![Python](https://img.shields.io/badge/Python-F1F5F9?style=flat-square&logo=python&logoColor=3776AB) ![SQL](https://img.shields.io/badge/SQL-F1F5F9?style=flat-square&logo=postgresql&logoColor=4169E1) |
| LLM & GenAI | ![RAG](https://img.shields.io/badge/RAG-F1F5F9?style=flat-square) ![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Systems-F1F5F9?style=flat-square) ![Tool Calling](https://img.shields.io/badge/Tool_Calling-F1F5F9?style=flat-square) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-F1F5F9?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-F1F5F9?style=flat-square&logo=modelcontextprotocol&logoColor=000000) |
| Models | ![OpenAI GPT](https://img.shields.io/badge/OpenAI_GPT-F1F5F9?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini-F1F5F9?style=flat-square&logo=googlegemini&logoColor=8E75B2) ![Qwen](https://img.shields.io/badge/Qwen-F1F5F9?style=flat-square&logo=alibabacloud&logoColor=FF6A00) |
| Frameworks | ![LangChain](https://img.shields.io/badge/LangChain-F1F5F9?style=flat-square&logo=langchain&logoColor=1C3C3C) ![LangGraph](https://img.shields.io/badge/LangGraph-F1F5F9?style=flat-square&logo=langgraph&logoColor=1C3C3C) ![Langfuse](https://img.shields.io/badge/Langfuse-F1F5F9?style=flat-square) |
| ML / DL | ![PyTorch](https://img.shields.io/badge/PyTorch-F1F5F9?style=flat-square&logo=pytorch&logoColor=EE4C2C) ![Transformers](https://img.shields.io/badge/Transformers-F1F5F9?style=flat-square&logo=huggingface&logoColor=FFB000) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F1F5F9?style=flat-square&logo=scikitlearn&logoColor=F7931E) ![TensorFlow](https://img.shields.io/badge/TensorFlow-F1F5F9?style=flat-square&logo=tensorflow&logoColor=FF6F00) ![MLflow](https://img.shields.io/badge/MLflow-F1F5F9?style=flat-square&logo=mlflow&logoColor=0194E2) |
| Data & storage | ![Qdrant](https://img.shields.io/badge/Qdrant-F1F5F9?style=flat-square&logo=qdrant&logoColor=DC244C) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-F1F5F9?style=flat-square&logo=postgresql&logoColor=4169E1) ![Redis](https://img.shields.io/badge/Redis-F1F5F9?style=flat-square&logo=redis&logoColor=FF4438) ![MinIO](https://img.shields.io/badge/MinIO-F1F5F9?style=flat-square&logo=minio&logoColor=C72E49) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-F1F5F9?style=flat-square&logo=elasticsearch&logoColor=005571) |
| Messaging & APIs | ![Kafka](https://img.shields.io/badge/Kafka-F1F5F9?style=flat-square&logo=apachekafka&logoColor=231F20) ![FastAPI](https://img.shields.io/badge/FastAPI-F1F5F9?style=flat-square&logo=fastapi&logoColor=009688) ![WebSocket](https://img.shields.io/badge/WebSocket-F1F5F9?style=flat-square) ![REST](https://img.shields.io/badge/REST_APIs-F1F5F9?style=flat-square) ![Airflow](https://img.shields.io/badge/Airflow-F1F5F9?style=flat-square&logo=apacheairflow&logoColor=017CEE) |
| Serving & infra | ![vLLM](https://img.shields.io/badge/vLLM-F1F5F9?style=flat-square&logo=vllm&logoColor=30A2FF) ![CUDA](https://img.shields.io/badge/CUDA-F1F5F9?style=flat-square&logo=nvidia&logoColor=76B900) ![Docker](https://img.shields.io/badge/Docker-F1F5F9?style=flat-square&logo=docker&logoColor=2496ED) ![Kubernetes](https://img.shields.io/badge/Kubernetes-F1F5F9?style=flat-square&logo=kubernetes&logoColor=326CE5) ![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI%2FCD-F1F5F9?style=flat-square&logo=gitlab&logoColor=FC6D26) ![Alibaba Cloud](https://img.shields.io/badge/Alibaba_Cloud-F1F5F9?style=flat-square&logo=alibabacloud&logoColor=FF6A00) ![Grafana](https://img.shields.io/badge/Grafana-F1F5F9?style=flat-square&logo=grafana&logoColor=F46800) |

<p align="center"><sub>Thanks for stopping by. Feel free to reach out about LLM apps, RAG or AI infrastructure.</sub></p>
