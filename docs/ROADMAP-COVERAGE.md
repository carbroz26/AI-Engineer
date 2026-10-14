# Original AI Engineer Roadmap — Coverage Audit

**Status:** FROZEN baseline — group-level coverage reconciled against the 225-lesson syllabus; detailed mapping is maintained by phase and topic.  
**Basis:** Attached one-page roadmap.sh AI Engineer PDF. This file tracks original labels, including older API terminology, even when newer equivalents will be taught.

| Original roadmap group | Original items covered | Syllabus phase |
| --- | --- | --- |
| Prerequisites and related | Frontend; Backend; Full-Stack; AI and Data Scientist roadmap; Prompt Engineering roadmap; Data Analyst roadmap | 00, 01, 18 |
| Introduction | Impact on Product Development; Roles and Responsibilities; What is an AI Engineer?; AI Engineer vs ML Engineer; AI vs AGI; LLMs; Inference; Training; Embeddings; Vector Databases; AI Agents; RAG; Prompt Engineering; Common Terminology | 00, 07, 08, 10–12 |
| Pre-trained models | Benefits; Limitations and Considerations; OpenAI Models; Capabilities/Context Length; Cut-off Dates/Knowledge; Popular AI Models; Anthropic Claude; Google Gemini; Azure AI; AWS SageMaker; Hugging Face Models; Mistral AI; Cohere; Replicate | 07 |
| OpenAI API | OpenAI Platform; Chat Completions API; Writing Prompts; Maximum Tokens; Token Counting; Pricing Considerations; Managing Tokens; OpenAI Playground; Fine-tuning; Prompt Engineering Roadmap | 08, 15 |
| AI Safety and Ethics | Prompt Injection Attacks; Security and Privacy Concerns; Bias and Fairness; Understanding AI Safety Issues; OpenAI Moderation API; Adding end-user IDs in prompts; Conducting adversarial testing; Robust prompt engineering; Know your Customers/Usecases; Constraining outputs and inputs; Safety Best Practices | 14 |
| OpenSource AI | Open vs Closed Source Models; Popular Open Source Models; Hugging Face; Finding Open Source Models; Hugging Face Tasks; Hugging Face Hub; Using Open Source Models; Inference SDK; Transformers.js; Ollama; Ollama Models; Ollama SDK | 09 |
| Embeddings | What are Embeddings; Semantic Search; Data Classification; Recommendation Systems; Anomaly Detection; Use Cases for Embeddings; OpenAI Embedding Models; Pricing Considerations; OpenAI Embeddings API; Sentence Transformers; Models on Hugging Face; Open-Source Embeddings | 10 |
| Vector Databases | Purpose and Functionality; Popular Vector DBs (pick one); Chroma; Pinecone; Weaviate; FAISS; LanceDB; Qdrant; Supabase; MongoDB Atlas; Implementing Vector Search; Indexing Embeddings; Performing Similarity Search | 10 |
| RAG & Implementation | RAG Usecases; RAG vs Fine-tuning; Implementing RAG; Chunking; Embedding; Vector Database; Retrieval Process; Generation; Ways of Implementing RAG; Using SDKs Directly; LangChain; LlamaIndex; RAG Alternative; OpenAI Assistant API | 11 |
| AI Agents | Agents Usecases; Prompt Engineering; ReAct Prompting; Building AI Agents; Manual Implementation; OpenAI Functions / Tools; OpenAI Assistant API | 12 |
| Multimodal AI | Multimodal AI Usecases; Image Understanding; Image Generation; Video Understanding; Audio Processing; Text-to-Speech; Speech-to-Text; Multimodal AI Tasks; OpenAI Vision API; DALL-E API; Whisper API; Hugging Face Models; LangChain for Multimodal Apps; LlamaIndex for Multimodal Apps; Implementing Multimodal AI | 13 |
| Development Tools | AI Code Editors; Code Completion Tools; Development Tools | 01, 16 |
| Continue learning | AI & Data Scientist; Prompt Engineering | 18 |

## Audit rules
- Every label from the original PDF must have a lesson-level destination before the syllabus is frozen.
- Preserve legacy terms for historical understanding while teaching current supported APIs.
- This table maps original roadmap groups and subtopics to the frozen syllabus phases. Lesson-level cross-checks should be maintained during research and notes creation.
- Research may add topics, but no original item may be silently dropped.

## Approval and follow-up

The learner approved the syllabus on 2026-10-14. This is a traceability baseline, not proof that each topic has been taught. Some vendor-specific APIs and tools are changing and must be revalidated when their lessons begin.
