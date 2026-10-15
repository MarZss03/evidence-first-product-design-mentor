# Evidence-First Product Design Mentor

An open-source Codex skill that turns an AI assistant into a product design studio mentor: it teaches through evidence, bounded practice, critique, revision, and transfer instead of silently doing the learner's design work.

## What makes it different

Many design assistants produce polished screens or generic best-practice lists. This skill focuses on the reasoning a designer needs to own:

- distinguishing observations, reported evidence, assumptions, inferences, and unknowns;
- connecting critique to user consequences and a way to verify improvement;
- covering operational constraints, edge states, accessibility, and recovery;
- turning real work into truthful case studies without invented research or impact;
- preserving productive struggle while still providing direct, actionable feedback.

## Modes

- **Learn** — concept, example, counterexample, exercise, and comprehension check.
- **Critique** — prioritized feedback for an interface, flow, prototype, research plan, or case study.
- **Studio** — guided project work from framing through validation and reflection.
- **Case study** — evidence-backed portfolio storytelling and claim hygiene.
- **Interview** — one question at a time, with follow-up probes and structured feedback.

## Install

Clone or download this repository, then place the repository folder in your Codex skills directory:

```text
~/.codex/skills/evidence-first-product-design-mentor
```

Restart or reload your Codex environment if the skill is not discovered immediately.

## Try it

```text
Use $evidence-first-product-design-mentor to teach me how to improve this onboarding flow. Ask me to reason before giving me the answer.
```

```text
Use $evidence-first-product-design-mentor to critique my case study. Flag every claim that is not supported by the evidence I provided.
```

```text
Use $evidence-first-product-design-mentor to simulate a product design portfolio interview. Ask one question at a time.
```

The mentor responds in the learner's language and can retain common product-design terms in English when that improves precision.

## Method

The skill uses a compact teaching loop:

```text
Diagnose → Teach → Demonstrate → Practice → Critique → Revise → Transfer
```

Critique is tied to five elements:

```text
Evidence → Consequence → Principle → Next move → Proof
```

See [`SKILL.md`](SKILL.md) for the behavior contract and [`references/`](references/) for the teaching method, critique rubric, project studio, case-study method, and exercise library.

## Boundaries

- It does not invent research, participant quotes, metrics, or business impact.
- It does not expose confidential employer, customer, or participant information.
- It does not treat visual taste as a usability fact.
- It does not require a heavyweight process when a small exercise or low-risk decision needs less.

## Author

Created by [Martin Zhang](https://github.com/MarZss03), informed by product-design practice across complex operations, AI workflows, interactive products, and portfolio development.

## License

MIT — see [`LICENSE`](LICENSE).
