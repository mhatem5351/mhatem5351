## Hi, I'm Mohamed Hatem

**AI Team Lead at [Globant](https://www.globant.com).** I design, ship and run production LLM systems: multi-agent
orchestration, retrieval (RAG), self-hosted model serving, and the evaluation and monitoring that keep them honest.
I'm based in Cairo and work remotely with teams in the Gulf and the US, in English and Arabic.

I came to AI from structural engineering. After my engineering degree I moved into data work (SQL development, then
data science). Over the last four years I have built AI platforms in production, and I now lead an AI engineering
team. I hold the **AWS Certified Machine Learning – Specialty** and an **M.Sc. in Data Science** from Cairo University.

### What I work on

- **Multi-agent LLM systems.** LangGraph orchestration, from a 6-agent bilingual chatbot to a 14-agent assistant for a
  stock-media platform.
- **Retrieval.** Hybrid vector + BM25 search with LLM reranking; semantic and visual search over millions of media
  assets.
- **LLM serving & MLOps.** vLLM on A100 GPUs, model versioning, health monitoring and automated recovery, Dockerized
  FastAPI and gRPC services, CI/CD.
- **Quality.** LLM evaluation, tracing and observability, so we know a model is right before users find out it isn't.
- **Arabic + English.** Most of what I have shipped is bilingual.

### Experience

**AI Team Lead · Globant** · Apr 2026 – present · remote
- Leading AI engineering on the STA project: multi-agent LLM orchestration, LLM serving and scalable RAG pipelines in
  production.

**Senior AI & MLOps Engineer · Wakeb Data** · Sep 2024 – Apr 2026 · Giza, Egypt
- Architected a fully async, production multi-agent chatbot (LangGraph, Qwen served with vLLM on A100 GPUs): six
  specialised agents, modular subgraphs, Arabic and English.
- Owned model serving end to end: vLLM configuration, GPU allocation, model versions, health checks and automated
  restarts across the production GPU servers.
- Built hybrid retrieval (vector + BM25 with LLM reranking), node-level caching and web search over MCP, shipped as
  Dockerized FastAPI services behind Nginx.
- Delivered the second generation of the AIP semantic search (more accurate, faster, with image search), the SALIC
  bilingual enterprise assistant with LLM evaluation and monitoring, and a research-paper agent with conversational
  memory.
- Moved key internal APIs from REST to gRPC to cut latency between services.

**AI Engineer · ArabsStock** · Apr 2023 – Dec 2024 · remote
- Built the Arabsstock Assistant: 14 LangGraph agents covering semantic search, AI image generation, database
  operations and content moderation.
- Engineered the platform's semantic search (OpenAI embeddings + Pinecone) and visual-similarity search across millions
  of stock photos, videos and vectors.
- Extended the platform into audio: sound generation and search for a beta sound library, instrument classification,
  BPM detection and audio watermarking.

**Data Scientist · Empoweromics** · Jan 2022 – Mar 2023 · Cairo · *Best Engineer of the Year*
- Unified data from 3,008+ real-estate developers, each with its own schema, to scale the company's real-time e-map.
- Built lead-lifecycle models for broker prioritisation, WhatsApp message classification (text and images) that routes
  messages to the right department, and a fuzzy "smart search" that finds clients despite misspellings.
- Designed ETL from Cosmos DB to SQL Server with scheduled Azure triggers.

**Earlier**
- AI research assistant and lecturer for M.Sc. students in biomedical informatics, The British University in Dubai
  (2022, part-time, remote).
- AI instructor, Military Technical College, Cairo (2022).
- Freelance data scientist, healthcare analytics for a US software company (2022).
- SQL Developer, MDP (2020 – 2021).

### Selected open-source work

- **[staged-llm-evaluator](https://github.com/mhatem5351/staged-llm-evaluator)**: a replayable LangGraph pipeline that
  grades LLM outputs in separate quality, safety and retry stages, with the final verdict computed in code, not by
  the model.
- **[prompt-reliability-harness](https://github.com/mhatem5351/prompt-reliability-harness)**: measures how consistently
  an LLM answers when the same question is paraphrased, misspelled, reordered or padded with distractors.
- **[rag-answering-service](https://github.com/mhatem5351/rag-answering-service)**: a small FastAPI retrieval service
  with cosine and dot-product indexes, a prompt-injection guardrail and latency / hit-rate metrics.
- **[Arabic sentiment analysis](https://github.com/mhatem5351/Arabic-Sentiment-Analysis-With-Multiple-Models)**:
  BiGRU, CNN and classical models on about 455k Arabic texts with AraVec embeddings.
- **[Text summarization](https://github.com/mhatem5351/Text-Summarization-NLP)**: a Dash app comparing DistilBART, T5
  and TextRank summaries (team project, AI diploma).

My other public repositories are coursework from my AI diploma (2021–22), kept as a record of where I started.

### Toolbox

- **LLMs & agents:** LangGraph · OpenAI API · Azure OpenAI · Qwen · vLLM · MCP · Langfuse
- **Retrieval:** Pinecone · Qdrant · pgvector · hybrid BM25 + dense search · LLM reranking
- **Backend & infra:** Python · FastAPI · gRPC · PostgreSQL · Docker · Kubernetes (AWS EKS) · Nginx · CI/CD
- **ML & data:** PyTorch · TensorFlow · scikit-learn · Spark · SQL Server · Azure · AWS

### Education & certifications

- M.Sc. Data Science, Cairo University (Faculty of Graduate Studies for Statistical Research), 2023 – 2026
- Diploma in Artificial Intelligence, Information Technology Institute (ITI), 9-month program with EPITA Paris, 2021 – 2022
- B.Eng. Structural Engineering, Tanta University, 2015 – 2020
- AWS Certified Machine Learning – Specialty (2022)

### Get in touch

[LinkedIn](https://www.linkedin.com/in/mohamed-hatem-6a5790173) · [mhatem5351@gmail.com](mailto:mhatem5351@gmail.com)
