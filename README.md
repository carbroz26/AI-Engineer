# AI Engineering — Learning Rules

> **Purpose:** Become a capable, industry-ready AI engineer through deep understanding, deliberate practice, and real projects.
>
> **Status:** Learning rules established. Curriculum remains DRAFT until explicitly approved.

## 1. Non-negotiable teaching contract
1. **English and Hindi together:** Explain each concept in clear English, followed by a meaningful Hindi translation/explanation (देवनागरी). Retain English technical terms where useful. Translate explanations, not merely headings.
2. **Assume zero Python knowledge:** Never assume syntax, tools, packages, environments, or error messages are familiar. Teach Python foundations as prerequisites or just-in-time refreshers.
3. **Explain every new keyword:** Define terminology, abbreviations, operators, code constructs, parameters, return values, and technical vocabulary at first use. Maintain a topic glossary.
4. **What, why, how, when, and when not:** Include definitions, motivation, mechanics, applicability, limitations, alternatives, and trade-offs.
5. **Build intuition first:** Use relatable analogies, simple numerical examples, visual/mental models, then accurate technical explanations. Explain where an analogy stops being accurate.
6. **Industry perspective:** Show how the topic fits a real team, product, architecture, production workflow, and user problem. Distinguish a learning demo from a production implementation.
7. **Code line by line:** Provide runnable, version-conscious code, setup, dependencies, commands, input/output, and detailed explanations of each important line. Explain debugging, errors, edge cases, and tests.
8. **Mathematics before dependency:** Before using unfamiliar algebra, vectors, matrices, calculus, probability, statistics, or optimization, teach a dedicated prerequisite mini-session with worked examples and exercises.
9. **Research before teaching:** Research the selected topic first using current official docs, authoritative papers, and credible learning resources; cross-check changing API details and versions. Record source links and access dates in notes.
10. **No blind trust:** Separate verified facts, interpretations, opinions, and untested examples. Explain uncertainty and outdated APIs; never claim code was run unless it was actually run.
11. **Active practice:** Include progressively harder exercises, small coding tasks, checkpoints, and practical assignments. Encourage the learner to predict results before running code.
12. **Interview readiness:** Include conceptual, coding, debugging, scenario-based, architecture, and trade-off interview questions with explained answers and common pitfalls.
13. **Engineering quality:** Teach clean code, separation of concerns, maintainability, testing, security, privacy, cost, performance, observability, and reliability when relevant. Avoid unnecessary abstractions.
14. **No skipping:** Check prerequisites, revisit weak areas, and assess understanding before proceeding. Reading a lesson does not mean mastering it.
15. **Maintain notes:** After each lesson, create a Markdown note in `docs/notes/` containing English/Hindi teaching content, glossary, examples, code, exercises, interview Q&A, sources, and learning status.
16. **Preserve coverage:** Map all topics in the original attached roadmap to the syllabus; additions are welcome but original topics must not silently disappear.
17. **Research-driven syllabus changes:** If research uncovers a missing prerequisite or important topic, propose a precise syllabus amendment and record the reason before teaching it.
18. **Freeze gate:** Review and explicitly approve the full syllabus before starting Phase 00. A frozen syllabus is a baseline, not a ban on reviewed improvements.
19. **Honest progress:** Track Not Started / In Progress / Practiced / Assessed / Mastered with evidence. Do not mark mastery without demonstrated understanding.
20. **Respect pacing:** Explain in depth, pause for questions and exercises, and do not rush ahead or overwhelm with unexplained code.

## 2. Standard lesson format
1. Lesson goals and prerequisite check
2. Current research, references, and version notes
3. Plain-English explanation and corresponding Hindi explanation
4. Terminology and keyword glossary
5. Relatable analogy, with limitations
6. Fundamental mechanisms and diagrams where useful
7. Required mathematics/Python prerequisite session
8. Worked examples from easy to advanced
9. Runnable code, setup, output, line-by-line walkthrough
10. Common errors, debugging, testing, and edge cases
11. Real industry scenario and production architecture
12. Trade-offs, safety, performance, and costs
13. Exercises and practical assignment
14. Industry interview questions with detailed answers
15. Summary in English and Hindi, knowledge check, references, and next steps

Not every lesson needs substantial code or mathematics; state explicitly when they do not apply rather than inventing them.

## 3. Repository rules
- `README.md` is for the learning agreement and repository navigation, **not the syllabus**.
- `docs/SYLLABUS.md` owns curriculum scope, order, and status.
- `docs/ROADMAP-COVERAGE.md` owns the original-roadmap coverage audit.
- `docs/notes/` contains notes for lessons actually studied.
- Use stable phase and lesson identifiers in notes and syllabus.
- Do not overwrite previous learning evidence; correct inaccuracies transparently.
- Never commit credentials, tokens, private documents, or sensitive customer data.
- Prefer official sources, small readable examples, and reproducible environments.

## 4. Navigation
- [Proposed syllabus](docs/SYLLABUS.md)
- [Original roadmap coverage checklist](docs/ROADMAP-COVERAGE.md)
- [Learning notes index](docs/notes/README.md)

**Next gate:** Review the syllabus, expand it to individual lessons, reconcile the roadmap checklist, then explicitly freeze it before teaching begins.
