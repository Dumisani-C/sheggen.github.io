# Open Source Contribution Grading Rubric
### Advanced / Capstone Software Engineering Course

## How to Use This Rubric

This rubric evaluates each student across **six balanced categories**, reflecting the reality that a strong open source contributor is judged not just on code, but on process, collaboration, judgment, and consistency — the same way a junior engineer would be evaluated on a real team.

Each category is scored with a **letter grade (A / B / C / D / F)**, using the descriptors below. Category grades are then combined into a single course grade using the weighting and conversion method in the final section.

Because you control the repository, you have direct access to the evidence needed to score fairly and consistently — see "Evidence Sources" for exactly where to look.

---

## Category 1: Technical Contribution & Code Quality — 20%

| Grade | Description |
|---|---|
| **A** | Contributions are substantial and well-architected, aligned with existing project conventions and idioms. Code handles edge cases, is efficient, and would pass professional review with minimal change requests. Tackled work of real complexity (new features, meaningful refactors, non-trivial bug fixes in core logic). |
| **B** | Contributions are solid and functional, mostly following conventions. Reviewers flag minor, non-blocking issues. Moderate complexity. |
| **C** | Contributions are functional but show gaps — style inconsistencies, mild code smells, thin edge-case handling — or are limited to low-complexity tasks (typo fixes, small config tweaks). |
| **D** | Contributions are minimal, or routinely required significant rework before merge. |
| **F** | No meaningful code contribution, or contributions introduced unresolved bugs/regressions. |

## Category 2: Git/GitHub Workflow & Process — 15%

| Grade | Description |
|---|---|
| **A** | Commit messages are clear and atomic; PRs are appropriately scoped with good descriptions (linked issues, rationale, test notes, screenshots where relevant); clean branch hygiene. |
| **B** | Generally good practices with occasional lapses — a vague commit message, an oversized PR. |
| **C** | Inconsistent practices: large/unclear commits, sparse PR descriptions. |
| **D** | Poor practices throughout — dumped commits ("fix stuff"), missing PR descriptions, history-breaking force pushes. |
| **F** | Did not follow the project's basic contribution workflow. |

## Category 3: Code Review & Collaboration — 20%

| Grade | Description |
|---|---|
| **A** | Actively reviews peers' PRs with substantive, specific feedback. Responds to feedback on own PRs promptly and without defensiveness, iterating well. Engages in issue threads and design discussions. |
| **B** | Reviews some PRs usefully; responds reasonably well to feedback on own work. |
| **C** | Minimal review participation; responds to feedback, but slowly or superficially. |
| **D** | Little to no review participation; defensive or unresponsive to feedback. |
| **F** | No collaborative engagement with the team or project. |

## Category 4: Problem Solving, Scoping & Initiative — 15%

| Grade | Description |
|---|---|
| **A** | Proactively identifies bugs/improvements, scopes own work sensibly, tackles ambiguous or complex problems, and does independent research (source, docs, related issues/PRs) to unblock themselves. |
| **B** | Handles assigned work well and occasionally spots opportunities; needs some guidance under ambiguity. |
| **C** | Relies on being told what to do; struggles with ambiguity without repeated prompting. |
| **D** | Rarely initiates work; needs significant hand-holding to stay productive. |
| **F** | No initiative shown. |

## Category 5: Testing & Documentation — 15%

| Grade | Description |
|---|---|
| **A** | Adds/updates tests for new logic with meaningful edge-case coverage; updates docs (README, docstrings, changelogs) as a normal part of contributions. |
| **B** | Reasonable test coverage and documentation with minor gaps. |
| **C** | Tests/docs are present but sparse. |
| **D** | Rarely writes tests or documentation, even when clearly needed. |
| **F** | No tests or documentation, not even after reviewer requests. |

## Category 6: Professionalism, Communication & Consistency — 15%

| Grade | Description |
|---|---|
| **A** | Consistent contribution cadence across the term (not just before deadlines); proactively communicates blockers or delays; professional tone in PRs, issues, and discussions. |
| **B** | Mostly consistent with occasional gaps; generally professional. |
| **C** | Bursty/last-minute contribution pattern; communication is reactive rather than proactive. |
| **D** | Long silent stretches with little communication. |
| **F** | Disappeared from the project, or conduct was unprofessional. |

---

## Evidence Sources (Where to Look)

| Category | GitHub Evidence |
|---|---|
| Code Quality | Diff view on merged PRs, "Files changed" tab, CI/lint status |
| Workflow/Process | Commit history (`git log`), PR descriptions, branch list |
| Review & Collaboration | "Conversation" tab on others' PRs, review comments left, response time on own PR threads |
| Initiative | Issues opened/self-assigned, discussion posts, linked design docs |
| Testing/Docs | Diffs touching `/tests`, `/docs`, README, inline docstrings |
| Consistency | Contributors graph / Insights → Contributors, commit timestamps across the term |

Tip: GitHub's **Insights → Contributors** view and the repo's **Pulse** page give a fast per-student timeline; combine with manually skimming their PR review comments for qualitative evidence.

---

## Calculating the Final Grade

1. Assign each of the six categories a letter grade using the tables above.
2. Convert each letter to points: **A = 4, B = 3, C = 2, D = 1, F = 0** (use +/- increments of 0.3 if you want finer granularity).
3. Multiply each category's points by its weight, then sum:

```
Weighted Score =
  (Technical Quality × 0.20) +
  (Workflow/Process  × 0.15) +
  (Review & Collab   × 0.20) +
  (Initiative        × 0.15) +
  (Testing & Docs    × 0.15) +
  (Professionalism   × 0.15)
```

4. Convert the weighted score back to a final letter grade:

| Weighted Score | Final Grade |
|---|---|
| 3.7 – 4.0 | A |
| 3.3 – 3.69 | A- |
| 3.0 – 3.29 | B+ |
| 2.7 – 2.99 | B |
| 2.3 – 2.69 | B- |
| 2.0 – 2.29 | C+ |
| 1.7 – 1.99 | C |
| 1.0 – 1.69 | D |
| 0 – 0.99 | F |

*(Adjust bands to match your institution's standard grading scale if it differs.)*

---

## Optional Add-On

Because this is a capstone-level course, you may want to weight **peer feedback** into Category 3 (Review & Collaboration) — a short end-of-term anonymous survey asking teammates to rate responsiveness and review quality can surface things that aren't visible in the commit history alone.
