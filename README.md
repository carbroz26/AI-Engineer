# AI Engineering — Learning Rules

> **Purpose:** Become a capable, industry-ready AI engineer through deep understanding, deliberate practice, and real projects.
>
> **Status:** Learning rules established. Curriculum v1.0 approved and frozen on 2026-10-14; Day 01 in progress.

## 1. Non-negotiable teaching contract
1. **Bilingual live teaching, English-only GitHub notes:** During interactive lessons, explain each concept in clear English and, when useful, Hindi (देवनागरी). All committed learning notes and technical documentation must be written in **English only**; never copy Hindi teaching paragraphs into notes.
2. **Assume zero Python knowledge:** Never assume syntax, tools, packages, environments, or error messages are familiar. Teach Python foundations as prerequisites or just-in-time refreshers.
3. **Explain every new keyword thoroughly:** At first use, define each unfamiliar technical term, abbreviation, operator, code construct, parameter, return value, and tool. Explain what it means, why it exists, how it works, when to use it, limitations, and a small example. Avoid unexplained technical jargon or circular definitions. Keep a detailed topic glossary with cross-references.
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
15. **Maintain English-only day-wise notes:** Update the current day's Markdown journal in `docs/notes/` after each studied segment. Include full English explanations, thoroughly defined keywords and technical vocabulary, commands with explanations and verified outputs, code, exercises, interview Q&A, sources, and honest learning status. Hindi is for interactive teaching only.
16. **Preserve coverage:** Map all topics in the original attached roadmap to the syllabus; additions are welcome but original topics must not silently disappear.
17. **Research-driven syllabus changes:** If research uncovers a missing prerequisite or important topic, propose a precise syllabus amendment and record the reason before teaching it.
18. **Freeze gate:** Review and explicitly approve the full syllabus before starting Phase 00. A frozen syllabus is a baseline, not a ban on reviewed improvements.
19. **Honest progress:** Track Not Started / In Progress / Practiced / Assessed / Mastered with evidence. Do not mark mastery without demonstrated understanding.
20. **Respect pacing:** Explain in depth, pause for questions and exercises, and do not rush ahead or overwhelm with unexplained code.

## 2. Standard lesson format
1. Lesson goals and prerequisite check
2. Current research, references, and version notes
3. Plain-English explanation and, during interactive teaching only, corresponding Hindi explanation; committed notes use English only
4. Detailed terminology and keyword glossary (definition, purpose, mechanism, example and pitfalls)
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
15. Live summary in English and Hindi when useful; English-only written notes, knowledge check, references, and next steps

Not every lesson needs substantial code or mathematics; state explicitly when they do not apply rather than inventing them.

## 3. Repository rules
- `README.md` is for the learning agreement and repository navigation, **not the syllabus**.
- `docs/SYLLABUS.md` owns curriculum scope, order, and status.
- `docs/ROADMAP-COVERAGE.md` owns the original-roadmap coverage audit.
- `docs/notes/` contains **English-only**, day-wise notes for lessons actually studied. Live teaching may use Hindi; GitHub notes must not.
- Use stable phase and lesson identifiers in notes and syllabus.
- Do not overwrite previous learning evidence; correct inaccuracies transparently.
- Never commit credentials, tokens, private documents, or sensitive customer data.
- Prefer official sources, small readable examples, and reproducible environments.

## 4. Experienced-developer fast track
The learner has 10 years of Android/Kotlin development experience. Teach familiar programming, API, architecture, asynchronous and testing concepts using **Kotlin-to-Python contrast-first explanations** rather than novice repetition. Still explain every new Python construct and teach genuinely new AI concepts and mathematics in depth. Use the optional [30-day fast-track plan](docs/AI-ENGINEER-30-DAY-FAST-TRACK.md); it does not replace or weaken the frozen 225-lesson syllabus. The 6-hour daily budget is an unconfirmed planning assumption.

## 5. Navigation
- [Frozen master syllabus](docs/SYLLABUS.md)
- [30-day experienced-developer fast track](docs/AI-ENGINEER-30-DAY-FAST-TRACK.md)
- [Original roadmap coverage checklist](docs/ROADMAP-COVERAGE.md)
- [Learning notes index](docs/notes/README.md)

**Next gate:** Begin Day 01 of the optional fast track when the learner requests it, or follow the frozen master syllabus in order. Research each lesson before teaching and document actual progress.
