# AI Engineering Master Syllabus

**Version:** 0.1  
**Status:** DRAFT — NOT FROZEN  
**Source:** User-provided roadmap.sh AI Engineer roadmap (one-page PDF), expanded with essential industry prerequisites and production topics.  
**Goal:** Absolute beginner to capable production AI engineer.

## How to read this document
Each phase below is a curriculum unit, **not yet a complete numbered lesson plan**. Before freezing, expand every phase into numbered lessons, identify dependencies, map original roadmap items, and review with the learner. Follow the [learning rules](../README.md).

## Phase 00 — Orientation & AI Engineering
AI engineering roles and responsibilities; product development impact; frontend, backend and full-stack prerequisites; AI vs ML vs deep learning vs AGI; LLMs; training vs inference; AI engineer vs ML engineer; AI systems in industry.

## Phase 01 — Computer Science & Developer Foundations
Computer fundamentals; operating systems; terminal/CLI; Windows/Linux; VS Code; Git and GitHub; networks, HTTP, REST, JSON, authentication, databases, SQL, APIs; debugging; software design and testing.

## Phase 02 — Python from Zero to Professional
Installation and virtual environments; syntax; variables; primitive types; operators; strings; collections; conditions; loops; functions; scope; files; exceptions; modules/packages; OOP; typing; comprehensions; iterators; generators; decorators; async/await; testing; packaging; clean code.

## Phase 03 — Mathematics for AI
Arithmetic and algebra; functions and graphs; logarithms; vectors and matrices; linear algebra; dot product, cosine similarity; derivatives and chain rule; gradients; probability; conditional probability; distributions; descriptive and inferential statistics; optimization; entropy/information theory. Reinforce mathematics just before its dependent lesson.

## Phase 04 — Data Engineering Foundations
NumPy; pandas; data cleaning; SQL; datasets; ETL/ELT; data validation; visualization; feature engineering; data quality; privacy; data pipelines.

## Phase 05 — Machine Learning Fundamentals
Supervised and unsupervised learning; regression; classification; clustering; recommendation; anomaly detection; model evaluation; train/validation/test; cross-validation; overfitting; scikit-learn.

## Phase 06 — Deep Learning & NLP
Tensors; neural networks; activations; losses; backpropagation; PyTorch; optimizers; tokenization; NLP; attention; transformer architecture; encoders/decoders; training.

## Phase 07 — LLMs & Pre-trained Models
Pre-training and inference; benefits, limitations and considerations; tokens, context length and knowledge cutoffs; model capabilities; open vs closed source/weights; model families and selection; provider comparisons (OpenAI, Anthropic Claude, Google Gemini, Mistral, Cohere, Hugging Face, Replicate, Azure AI, AWS SageMaker); benchmarks.

## Phase 08 — AI APIs & Prompt Engineering
OpenAI platform and models; APIs and SDKs; chat completions and current supported response interfaces; authentication; prompts and prompt engineering; roles/messages; zero/few-shot; system instructions; output formats and constraints; token counting, max tokens, managing tokens, pricing; playground; tool/function calling; streaming; caching; fine-tuning introduction. Recheck provider/API status at teaching time.

## Phase 09 — Open-source AI & Model Serving
Open vs closed models; popular open-weight models; Hugging Face Hub, tasks, model discovery and licenses; inference SDKs; Transformers.js; Python Transformers; Sentence Transformers; Ollama, Ollama models and SDK; local model inference; model formats; quantization and serving.

## Phase 10 — Embeddings & Vector Search
What embeddings are; OpenAI embedding models and embeddings API; embedding pricing; open-source embeddings and Sentence Transformers; Hugging Face embedding models; semantic search; classification; recommendations; anomaly detection; vector databases purpose/functionality; indexing embeddings; similarity search; exact/approximate nearest neighbors; Chroma, Pinecone, Weaviate, FAISS, LanceDB, Qdrant, Supabase, MongoDB Atlas; implementing vector search.

## Phase 11 — RAG Engineering
RAG use cases; RAG vs fine-tuning; implementing RAG: chunking, embeddings, vector database, retrieval and generation; retrieval process; query rewriting; metadata filters; hybrid search; reranking; grounding; citations; evaluation; direct SDK implementations; LangChain and LlamaIndex; RAG alternatives; historical OpenAI Assistants API as a legacy topic (verify current status before teaching).

## Phase 12 — AI Agents & Workflows
Agent definition and use cases; prompting; ReAct; tool/function calling; manual agent implementations; historical Assistants API; state and memory; planning; workflow orchestration; LangChain/LlamaIndex; Model Context Protocol; approvals; multi-agent systems; recovery and observability.

## Phase 13 — Multimodal AI
Multimodal tasks and use cases; image understanding; image generation; video understanding; audio processing; speech-to-text; text-to-speech; OpenAI vision/image/audio interfaces (including legacy Vision, DALL-E and Whisper API terminology); Hugging Face models; LangChain and LlamaIndex multimodal applications; implementation.

## Phase 14 — AI Security, Safety & Responsible AI
Prompt injection; security/privacy; bias/fairness; AI safety issues; moderation APIs; user identification in safety workflows (avoid putting unnecessary identifiers into prompts); adversarial testing; robust prompting; understanding customers and use cases; input/output constraints; best practices; secrets; authorization; data protection; threat modeling.

## Phase 15 — Fine-Tuning & Advanced Model Engineering
Fine-tuning concepts and trade-offs; dataset curation; supervised fine-tuning; LoRA/QLoRA and PEFT; training loops; preference optimization; distillation; evaluation; quantization; inference optimization.

## Phase 16 — Production AI Architecture & LLMOps
FastAPI; async services; Docker; CI/CD; cloud and deployment; inference serving; observability, tracing, monitoring, evaluation pipelines; latency; rate limits; retries; resilience; caching; cost control; scaling; reliability; incident response; security.

## Phase 17 — Industry Systems & Capstone Projects
Python developer toolkit; ML prediction service; LLM backend; enterprise document RAG; tool-using agent; multimodal workflow; secure production AI platform; architecture reviews; capstone portfolio.

## Phase 18 — Expert Preparation & Continuous Learning
Python, mathematics, ML, LLM, RAG, agent, system-design and debugging interviews; research papers; open-source contributions; code reviews; communication; career portfolio; related AI/data-scientist and prompt-engineering tracks; continued learning.

## Prerequisite sessions (required, not optional)
| Before | Teach/review |
| --- | --- |
| Python calculations | Arithmetic, algebra and programming operators |
| ML models | Functions, probability and statistics |
| Neural networks | Matrices, calculus, gradients and chain rule |
| Embeddings | Vectors, dot product and cosine similarity |
| Transformers | Matrix multiplication, softmax and probability |
| Model training | Losses, derivatives and optimization |
| Evaluation | Sampling, uncertainty and statistical metrics |
| APIs/RAG/agents | Python, HTTP, JSON, errors and async basics |

## Project milestones
1. Python command-line toolkit with tests.
2. Machine learning prediction service.
3. Production-style LLM API application.
4. Enterprise document RAG with citations and evaluation.
5. Safe tool-using AI agent with approvals.
6. Multimodal workflow.
7. Final deployed AI platform with monitoring, security and portfolio documentation.

## Governance and freeze
- **Current:** proposed high-level syllabus only.
- **Next:** expand into numbered lessons; check original-roadmap item-by-item coverage; resolve omissions and prerequisites.
- **Freeze only after explicit learner approval.**
- At teaching time, research each lesson anew. If important gaps emerge, propose and record an amendment; do not silently alter the frozen baseline.
