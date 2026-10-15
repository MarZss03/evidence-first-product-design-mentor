# Product design critique rubric

Use this rubric for interfaces, user flows, prototypes, research plans, and case studies. Evaluate only dimensions supported by the submitted artifact and context.

## Severity

- **Blocking:** prevents task completion, creates serious exclusion or harm, or makes the central claim untrustworthy.
- **Major:** meaningfully increases errors, effort, uncertainty, or implementation risk.
- **Moderate:** weakens comprehension, consistency, confidence, or maintainability.
- **Polish:** improves clarity or craft without materially changing task success.

Do not assign severity from visual taste alone.

## 1. Problem and outcome

Check for a specific user and situation, a task or unmet need rather than a desired feature, constraints and non-goals, and an observable success condition. A problem statement that already dictates the solution is a weak signal.

## 2. Evidence and assumptions

Check whether important decisions trace to research, product data, domain constraints, usability observations, or explicitly labeled assumptions.

Weak signals include unsupported persona details, interview counts without findings, claimed impact without a measurement source, and research performed only to justify a chosen concept.

## 3. Flow and information architecture

Check whether the primary task has a clear start, progression, and completion; labels match the user's language; hierarchy reflects frequency and importance; navigation and back behavior are predictable; and context survives transitions.

## 4. Interaction and system feedback

Check affordances and control states, confirmation and progress, validation and error recovery, reversal of destructive actions, loading and empty states, permissions, conflicts, and completion. When AI is involved, check sources, confidence, human confirmation, and fallback behavior.

## 5. Accessibility and inclusion

Check the applicable surface for keyboard operation, visible focus, readable text, sufficient contrast, meaningful labels, alternatives, zoom, reflow, target size, reduced motion, language, localization, and situational limitations.

Treat confirmed accessibility failures as usability defects, not optional polish.

## 6. Visual hierarchy and system quality

Check whether typography, spacing, color, components, and states form a coherent system that directs attention to the task.

Weak signals include decoration competing with primary actions, one-off components, color carrying meaning alone, and dense layouts without grouping or progressive disclosure.

## 7. Validation and learning

Check whether the evaluation method matches the risk: task testing for comprehension, accessibility review for inclusive operation, technical prototypes for feasibility, analytics or experiments for live behavior, and expert review for domain constraints.

A test should be capable of showing the idea is wrong. Satisfaction alone does not prove task success.

## 8. Communication and ownership

Check whether the creator can explain their role, collaborators, decisions, alternatives, scope, timeline, constraints, evidence-driven changes, remaining limitations, and next steps.

## Critique output

Lead with the highest-severity issue. For each priority use:

```text
Finding:
Evidence state: Observed | Reported | Assumed | Inferred | Unknown
User consequence:
Principle:
Next move:
Proof:
```

Finish with one strength worth preserving and one learner-owned revision task.
