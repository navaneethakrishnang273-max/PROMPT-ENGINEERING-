# PROMPT-ENGINEERING - BASICS TO INTERMIDEATE

Welcome to my central repository documenting an intensive, 10 week journey for prompt engineering from scratch  to intermideate level and how to use ai tools efficiently.

This 10-week, zero-to-intermediate prompt engineering curriculum and repository design is ready to commit directly to your GitHub `README.md`.

---

### Roadmap & Curriculum Overview

| Week | Phase | Focus Module | Core Prompting Concepts | Practical Hand-on Output |
| --- | --- | --- | --- | --- |
| **W1** | **Foundations** | LLM Architecture & Mechanics | Tokens, Context Windows, Temperature, Top-P, System vs. User Prompts | Tokenizer sandbox scripts & hyperparameter baseline tests |
| **W2** | **Foundations** | Base Prompting Patterns | Zero-shot, Few-shot (In-context learning), Role/Persona Assignment | Structured domain-expert prompt library (Markdown) |
| **W3** | **Intermediate** | Output Control & Structuring | JSON schemas, Markdown formatting, Delimiters, Negative Constraints | Validated JSON generator for complex structured data |
| **W4** | **Intermediate** | Reasoning Paradigms | Chain-of-Thought (CoT), Few-shot CoT, Self-Consistency, Step-Back | Multi-step mathematical & logical reasoning test suite |
| **W5** | **Intermediate** | Advanced Reasoning | Tree-of-Thought (ToT), Directional Stimulus, Skeleton-of-Thought | Problem-solving prompt pipelines for complex analysis |
| **W6** | **Advanced Systems** | Prompt Chaining & Flow | Sequential prompting, Output-to-Input mapping, Sub-task decomposition | Automated 3-stage blog post/code generation pipeline |
| **W7** | **Advanced Systems** | Tool Use & Function Calling | Function schemas, API integration, ReAct framework (Reason + Act) | ReAct agent prompting setup executing external APIs |
| **W8** | **Production** | RAG & Context Injection | Context augmentation, Chunking strategies, Grounding, System Instructions | Knowledge-base QA prompt pipeline with hallucination guards |
| **W9** | **Production** | Security & Robustness | Prompt Injection, Jailbreak defense, Data leakage, System prompt hardening | Red-teaming report & production-grade system prompt shield |
| **W10** | **Optimization** | Evaluation & Fine-Tuning | Metric-based testing (BLEU/ROUGE), LLM-as-a-Judge, Systematic Prompt Tuning | End-to-End Capstone Project: Production Prompt Suite |

---

### Repository Structure

```
prompt-engineering-roadmap/
├── 01-foundations/
│   ├── week-01-llm-mechanics/
│   │   ├── notes.md
│   │   └── token_calculator.py
│   └── week-02-base-patterns/
│       ├── zero_shot_examples.md
│       └── few_shot_templates.json
├── 02-intermediate-techniques/
│   ├── week-03-output-structuring/
│   ├── week-04-reasoning-cot/
│   └── week-05-advanced-reasoning/
├── 03-advanced-systems/
│   ├── week-06-prompt-chaining/
│   └── week-07-react-and-tool-use/
├── 04-production-and-security/
│   ├── week-08-rag-context/
│   └── week-09-security-red-teaming/
├── 05-evaluation-and-capstone/
│   ├── week-10-llm-as-a-judge/
│   └── capstone-project/
├── templates/
│   ├── system_prompts.md
│   └── output_schemas/
├── tests/
│   └── prompt_eval_suite.py
├── .gitignore
├── LICENSE
└── README.md

```

---

### Daily Progress Tracker

Copy and paste this checklist into your `README.md` to track daily progress.

#### Phase 1: Foundations (Weeks 1–2)

* [*] **Day 01:** Learn tokens, context windows, and model architectures.
* [ ] **Day 02:** Master parameters: `Temperature`, `Top-P`, `Frequency Penalty`, `Presence Penalty`.
* [ ] **Day 03:** Understand the functional difference between System, User, and Assistant roles.
* [ ] **Day 04:** Construct effective Zero-Shot prompts with precise instructions.
* [ ] **Day 05:** Implement Few-Shot prompting (1 to 5 examples) to control style and output.
* [ ] **Day 06:** Build domain-specific Personas using role assignment patterns.
* [ ] **Day 07:** Project: Build a modular Base Prompt Library in Markdown.

#### Phase 2: Structured Output & Reasoning (Weeks 3–5)

* [ ] **Day 08:** Enforce strict JSON output using system instructions and schemas.
* [ ] **Day 09:** Use explicit delimiters (`xml`, `markdown`, `---`) to isolate context from instructions.
* [ ] **Day 10:** Implement negative constraints (what *not* to do) without triggering unwanted outputs.
* [ ] **Day 11:** Master standard Chain-of-Thought (CoT) prompting ("Think step by step").
* [ ] **Day 12:** Build Few-Shot CoT templates containing fully worked-through reasoning samples.
* [ ] **Day 13:** Practice Self-Consistency prompting (sampling multiple reasoning paths).
* [ ] **Day 14:** Implement Step-Back prompting to extract core principles before task execution.
* [ ] **Day 15:** Design Tree-of-Thought (ToT) prompts for multi-path exploration.
* [ ] **Day 16:** Implement Directional Stimulus Prompting to guide output trajectory.
* [ ] **Day 17:** Test Skeleton-of-Thought for rapid structured generation.
* [ ] **Day 18:** Project: Multi-step technical reasoning prompt suite with JSON validation.

#### Phase 3: Advanced Systems & Integration (Weeks 6–7)

* [ ] **Day 19:** Learn Prompt Chaining: Passing output of Prompt A into Prompt B.
* [ ] **Day 20:** Implement Sub-task Decomposition for complex workflows.
* [ ] **Day 21:** Build an automated multi-stage document generation pipeline.
* [ ] **Day 22:** Understand Function Calling concepts and JSON Schema parameter declarations.
* [ ] **Day 23:** Implement the ReAct (Reason + Act) loop pattern manually in prompts.
* [ ] **Day 24:** Connect prompts to external tool calls (Search, Calculator, Database).
* [ ] **Day 25:** Project: ReAct Agent system prompt capable of structured tool selection.

#### Phase 4: Production, RAG & Security (Weeks 8–9)

* [ ] **Day 26:** Learn RAG context injection patterns: System Instructions vs. Injected Context.
* [ ] **Day 27:** Write groundness prompts to prevent hallucinations.
* [ ] **Day 28:** Handle context window overflow with prompt chunking & summarization chains.
* [ ] **Day 29:** Study Direct & Indirect Prompt Injections (Jailbreaking techniques).
* [ ] **Day 30:** Implement defensive prompt design: XML tags, instruction boundaries, defensive system prompts.
* [ ] **Day 31:** Perform red-teaming tests against your system prompts.
* [ ] **Day 32:** Project: Production-grade system prompt shield with context grounding.

#### Phase 5: Optimization & Capstone (Week 10)

* [ ] **Day 33:** Set up LLM-as-a-Judge evaluation prompts to grade model responses.
* [ ] **Day 34:** Build automated evaluation scripts comparing prompt variants (A/B testing).
* [ ] **Day 35:** Optimize prompt length (token reduction) without sacrificing accuracy.
* [ ] **Day 36:** Assemble final Capstone Project: End-to-End LLM Prompt System.
* [ ] **Day 37:** Refine project documentation and push to GitHub repository.

---

### Core Tech Stack

* **Playgrounds & IDEs:** OpenAI Playground, Google AI Studio, Anthropic Console, VS Code
* **Frameworks & Orchestration:** LangChain, LlamaIndex, Instructor (for structured outputs), Guidance / Outlines
* **Model Access (APIs/Providers):** OpenAI API (GPT-4o/o3), Anthropic API (Claude 3.5 Sonnet), Google Gemini API, Ollama (Local open-weight models: Llama 3, DeepSeek R1)
* **Testing & Evaluation:** Promptfoo (CLI prompt testing), Ragas (RAG evaluation), Python `pydantic` (Schema validation)
* **Version Control:** Git, GitHub, Markdown
