# AI Engineer — 30-Day Experienced Developer Fast Track

**Version:** 1.0  
**Status:** APPROVED TRACK — created 2026-10-14  
**Audience:** Developer with 10 years of Android/Kotlin experience, new to Python and AI engineering.  
**Authority:** [Frozen 225-lesson syllabus](SYLLABUS.md) remains unchanged. This track is an accelerated **selection and survey**, not a substitute for mastering every lesson.

## Objective and honest scope
Build a credible working AI application with Python, model APIs, embeddings, RAG, tool calling, evaluation, basic security and deployment in 30 days. Aim for practical beginner-to-intermediate AI application skills, **not expert mastery of all 225 lessons**. Full ML/deep-learning mathematics, fine-tuning, advanced multimodal work, production-scale architecture and deep interview mastery remain later work.

## Time budget
**Planning assumption: 6 focused hours/day, 30 calendar days (180 hours).** User has not yet confirmed actual availability; adapt proportionally. At 4 hours/day, reduce project scope or extend duration; at 8 hours/day, allocate extra time to implementation, debugging and deeper assessments. Avoid sacrificing sleep or sustained concentration.

Suggested daily allocation: 60 min concept/research, 90 min bilingual explanations + Kotlin comparison, 150 min hands-on coding, 45 min debugging/testing, 15 min recall/interview review. Adjust to topic complexity.

## Accelerated teaching contract
- Reuse Kotlin/Android knowledge: types, classes, OOP, HTTP, JSON, coroutines, Git, testing, architecture and dependency injection need **contrast-first** instruction, not novice lectures.
- Never assume Python syntax is known: explain indentation, dynamic typing, mutability, exceptions, `asyncio`, packaging and Python-specific semantics.
- Each topic still follows [README learning rules](../README.md): English then Hindi explanation, glossary, what/why/how/when, industry scenario, runnable code, tests, edge cases, interview Q&A and sources.
- New AI mathematics and concepts receive full prerequisite explanations; **do not compress embeddings, transformers, RAG or agent safety into memorized definitions**.
- Each day begins with current-source research and ends with a tangible artifact, self-check and notes under `docs/notes/`.
- Mark a lesson **Practiced** or **Mastered** only with evidence; a daily range below is a coverage target, not automatic completion.
- Legacy APIs (Assistants, DALL-E, Vision naming) are taught historically; verify current supported APIs before writing new code.
- Do not overwrite the frozen master syllabus to accommodate the 30-day schedule. Log proposed amendments separately for approval.

## Kotlin-to-Python bridge
| Existing Android/Kotlin experience | Python/AI counterpart | New pitfalls to emphasize |
| --- | --- | --- |
| `data class`, `val`, `var` | `@dataclass`, variables, type hints | Python annotations generally do not enforce runtime types |
| Collections and higher-order functions | list/dict/set, comprehensions, generators | Mutability, iteration and identity |
| Coroutines, `suspend` | `async def`, `await`, asyncio | Event loop, cancellation and blocking calls |
| Retrofit/Ktor and serialization | HTTPX/requests, JSON, Pydantic | Timeouts, schema validation, API errors |
| Gradle modules/dependencies | `pyproject.toml`, pip/uv, venv | Environment isolation and reproducibility |
| JUnit and mocks | pytest and mocking | Fixtures and parametrization |
| Clean Architecture / SRP | Python packages and boundaries | Avoid Java-style boilerplate and over-abstraction |
| Backend-driven UI / APIs | LLM response/tool schemas | Treat model output as untrusted data |

## Daily plan
| Day | Focus | Master syllabus lesson references | Required deliverable |
| --- | --- | --- | --- |
| 01 | Python environment and syntax | 02-001–02-006 | Hello Python + typed input/output |
| 02 | Python collections and architecture | 02-007–02-014 | JSON parser + domain model |
| 03 | Python async, APIs and tests | 02-015–02-020; 01-005–01-009 | Tested CLI calling an API |
| 04 | AI roles and model basics | 00-001–00-007; 07-001–07-002 | Explain system components |
| 05 | Vectors and embedding mathematics | 03-001–03-006; 10-001–10-002 | Compute similarity in Python |
| 06 | ML, probability and evaluation | 03-009–03-012; 05-001–05-006 | Small scikit-learn evaluation |
| 07 | Neural networks and transformers | 03-007–03-008; 03-013; 06-001–06-010 | Sketch and explain attention pipeline |
| 08 | Pre-trained model ecosystem | 07-003–07-011; 09-001–09-002 | Model selection decision table |
| 09 | API fundamentals | 08-001–08-004 | First model API request |
| 10 | Prompting and structured output | 08-005; 08-008; 08-011 | Typed structured-response workflow |
| 11 | Tokens, costs and streaming | 08-006–08-007; 08-010 | Streaming client with error handling |
| 12 | Tool calling and LLM service | 08-009; 08-012–08-013; 16-001–16-002 | Tested LLM API backend |
| 13 | Embedding models | 10-003–10-008; 09-006 | Generate and compare embeddings |
| 14 | Vector search engines | 10-009–10-014 | Persist and query local index |
| 15 | RAG foundations | 11-001–11-006 | Document ingestion pipeline |
| 16 | Grounded answers | 11-007–11-009 | Cited question-answering endpoint |
| 17 | RAG frameworks and alternatives | 11-010–11-012; 11-015 | Compare two RAG approaches |
| 18 | RAG quality and security | 11-013–11-014; 14-001–14-003 | RAG evaluation suite |
| 19 | Agents and ReAct | 12-001–12-005 | Bounded Python tool loop |
| 20 | Tools, state and memory | 12-006–12-008 | Stateful agent workflow |
| 21 | Agent ecosystems and MCP | 12-009–12-010; 12-014; 09-003–09-005 | Tool integration comparison |
| 22 | Local AI and multimodal survey | 09-007–09-010; 13-001–13-009 | Local model or multimodal demo |
| 23 | Agent reliability and safety | 12-011–12-013; 12-015; 14-004–14-012 | Safe agent with tests |
| 24 | Production API quality | 16-003; 16-006–16-009 | Containerized API |
| 25 | Cloud and CI/CD | 16-004–16-005; 16-012–16-013 | Deploy staging service |
| 26 | Cost, performance and evaluation | 16-010–16-011; 15-001–15-003 | Cost and evaluation report |
| 27 | Advanced topics overview | 15-004–15-009; 13-010–13-012 | Decision memo: when to specialize |
| 28 | Capstone architecture | 17-001–17-007 | Capstone design |
| 29 | Capstone implementation | 17-008–17-009; 17-010 | Working capstone |
| 30 | Review and interview assessment | 18-001–18-012 | Demo, architecture defense and gap report |

## Day-by-day scope and teaching notes

### Day 01 — Python environment and syntax
**Study:** Install Python; compare Kotlin variables/functions/control flow; run scripts and explain indentation.  
**Reference:** 02-001–02-006.  
**Evidence:** Hello Python + typed input/output.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 02 — Python collections and architecture
**Study:** Collections, functions, modules, files, exceptions, dataclasses, type hints; Kotlin comparisons.  
**Reference:** 02-007–02-014.  
**Evidence:** JSON parser + domain model.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 03 — Python async, APIs and tests
**Study:** Generators/decorators overview, asyncio vs Kotlin coroutines, HTTP clients, pytest, packaging.  
**Reference:** 02-015–02-020; 01-005–01-009.  
**Evidence:** Tested CLI calling an API.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 04 — AI roles and model basics
**Study:** AI vs ML, LLM architecture, training/inference, benefits and limitations.  
**Reference:** 00-001–00-007; 07-001–07-002.  
**Evidence:** Explain system components.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 05 — Vectors and embedding mathematics
**Study:** Algebra refresh, vectors, dot product, cosine similarity, matrix intuition.  
**Reference:** 03-001–03-006; 10-001–10-002.  
**Evidence:** Compute similarity in Python.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 06 — ML, probability and evaluation
**Study:** Probability, statistics, supervised learning, metrics and data splits.  
**Reference:** 03-009–03-012; 05-001–05-006.  
**Evidence:** Small scikit-learn evaluation.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 07 — Neural networks and transformers
**Study:** Gradients, neural nets, tokens, attention and transformers at conceptual level.  
**Reference:** 03-007–03-008; 03-013; 06-001–06-010.  
**Evidence:** Sketch and explain attention pipeline.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 08 — Pre-trained model ecosystem
**Study:** Context limits, knowledge cutoff, provider selection, open vs closed, pricing.  
**Reference:** 07-003–07-011; 09-001–09-002.  
**Evidence:** Model selection decision table.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 09 — API fundamentals
**Study:** Credentials, SDK, Responses/Chat Completions concepts, instructions/messages.  
**Reference:** 08-001–08-004.  
**Evidence:** First model API request.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 10 — Prompting and structured output
**Study:** Prompt templates, few-shot, JSON schema and evaluation.  
**Reference:** 08-005; 08-008; 08-011.  
**Evidence:** Typed structured-response workflow.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 11 — Tokens, costs and streaming
**Study:** Token budgets, pricing, timeouts, retries, streaming.  
**Reference:** 08-006–08-007; 08-010.  
**Evidence:** Streaming client with error handling.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 12 — Tool calling and LLM service
**Study:** Function tools, fine-tuning decision overview, FastAPI service.  
**Reference:** 08-009; 08-012–08-013; 16-001–16-002.  
**Evidence:** Tested LLM API backend.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 13 — Embedding models
**Study:** Semantic search, classification, recommendations, open/closed embeddings.  
**Reference:** 10-003–10-008; 09-006.  
**Evidence:** Generate and compare embeddings.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 14 — Vector search engines
**Study:** Indexing, ANN, FAISS/Chroma lab; compare Pinecone, Weaviate, Qdrant, LanceDB, Supabase, MongoDB.  
**Reference:** 10-009–10-014.  
**Evidence:** Persist and query local index.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 15 — RAG foundations
**Study:** Use cases, RAG vs fine-tuning, parsing, chunking, indexing and retrieval.  
**Reference:** 11-001–11-006.  
**Evidence:** Document ingestion pipeline.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 16 — Grounded answers
**Study:** Generation, citations, query rewriting, hybrid retrieval and reranking.  
**Reference:** 11-007–11-009.  
**Evidence:** Cited question-answering endpoint.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 17 — RAG frameworks and alternatives
**Study:** Direct SDK vs LangChain/LlamaIndex; legacy Assistants API context.  
**Reference:** 11-010–11-012; 11-015.  
**Evidence:** Compare two RAG approaches.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 18 — RAG quality and security
**Study:** Retrieval and answer evaluation, prompt injection, private documents.  
**Reference:** 11-013–11-014; 14-001–14-003.  
**Evidence:** RAG evaluation suite.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 19 — Agents and ReAct
**Study:** Agents vs deterministic workflows, ReAct, manual loops.  
**Reference:** 12-001–12-005.  
**Evidence:** Bounded Python tool loop.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 20 — Tools, state and memory
**Study:** Tool schemas, approvals, memory, persistence, execution limits.  
**Reference:** 12-006–12-008.  
**Evidence:** Stateful agent workflow.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 21 — Agent ecosystems and MCP
**Study:** LangChain/LlamaIndex, MCP, Hugging Face Hub and Transformers.js survey.  
**Reference:** 12-009–12-010; 12-014; 09-003–09-005.  
**Evidence:** Tool integration comparison.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 22 — Local AI and multimodal survey
**Study:** Ollama, model serving, vision, image/audio/video tasks, Whisper and legacy DALL-E names.  
**Reference:** 09-007–09-010; 13-001–13-009.  
**Evidence:** Local model or multimodal demo.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 23 — Agent reliability and safety
**Study:** Approvals, traces, adversarial tests, moderation, privacy, constrained outputs.  
**Reference:** 12-011–12-013; 12-015; 14-004–14-012.  
**Evidence:** Safe agent with tests.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 24 — Production API quality
**Study:** Docker, auth, caching, retries, quotas, metrics and logs.  
**Reference:** 16-003; 16-006–16-009.  
**Evidence:** Containerized API.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 25 — Cloud and CI/CD
**Study:** CI pipeline, deployment, monitoring, SLOs and incident response.  
**Reference:** 16-004–16-005; 16-012–16-013.  
**Evidence:** Deploy staging service.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 26 — Cost, performance and evaluation
**Study:** Eval datasets, latency/cost, fine-tuning criteria and SFT basics.  
**Reference:** 16-010–16-011; 15-001–15-003.  
**Evidence:** Cost and evaluation report.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 27 — Advanced topics overview
**Study:** LoRA/QLoRA, optimization, multimodal frameworks; advanced topics are survey only.  
**Reference:** 15-004–15-009; 13-010–13-012.  
**Evidence:** Decision memo: when to specialize.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 28 — Capstone architecture
**Study:** Select use case, requirements, threat model, architecture and ADRs.  
**Reference:** 17-001–17-007.  
**Evidence:** Capstone design.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 29 — Capstone implementation
**Study:** Integrate API, RAG, tool calling, tests, evaluation, deployment.  
**Reference:** 17-008–17-009; 17-010.  
**Evidence:** Working capstone.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

### Day 30 — Review and interview assessment
**Study:** Python/ML/LLM/RAG/agents/system design interviews; research and portfolio.  
**Reference:** 18-001–18-012.  
**Evidence:** Demo, architecture defense and gap report.  
**Checkpoint:** Explain the key concepts in English and Hindi, demonstrate code where relevant, and answer at least one conceptual, one debugging and one industry-scenario question.

## Project quality gates
1. **Day 3:** Python client and tests run locally; no secrets committed.
2. **Day 12:** Model API service validates inputs and outputs, handles errors and logs safely.
3. **Day 18:** RAG returns grounded answers with source citations and includes an evaluation dataset.
4. **Day 23:** Agent has explicit tool permissions, bounded steps, approval points and failure handling.
5. **Day 27:** API can run reproducibly; metrics, costs and security risks are documented.
6. **Day 30:** End-to-end demonstration, README, architecture diagram, tests, limitations and next-stage backlog.

## Research, assessments and note structure
- Before each day's teaching, check current official docs and credible papers; record versions, source URLs and research date.
- Write actual notes only after teaching; prefer `docs/notes/phase-XX-name/XX-YYY-topic.md` and link to original lesson IDs.
- A daily checkpoint must record: learned concepts, code/tests completed, interview Q&A, unresolved questions and confidence.
- Weekly review after days 7, 14, 21 and 30: fix gaps before increasing complexity.
- If a day overruns, carry unfinished work forward. Do not falsely mark it complete to preserve the calendar.

## Coverage limits and next stage
This 30-day plan samples or surveys all major syllabus phases, but **does not deeply complete all 225 lessons**. In particular, advanced ML/DL, full mathematical rigor, deep model training/fine-tuning, all vendor frameworks, multimodal production systems, and advanced operations require dedicated follow-on study. Continue the frozen master syllabus after the fast track, prioritizing assessment gaps.

## Current progress
**Not started.** No exercises, tests, research sessions or lessons have been completed yet. Begin Day 01 only when requested.
