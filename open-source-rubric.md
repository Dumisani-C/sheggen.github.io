# CSC 426 - Open Source Software Engineering 
## Contribution Grading Rubric

Strong open source contributor is judged not just on code, but on process, collaboration, judgment, and consistency; the same way a junior engineer would be evaluated in the software engineering industry.
Thus, this rubric evaluates you across **six categories**:

1. Technical Contribution & Code Quality
2. Git/GitHub Workflow & Process
3. Code Review & Collaboration
4. Problem Solving, Scoping & Initiative
5. Testing & Documentation
6. Professionalism, Communication & Consistency

Each category is scored with a **letter grade (A / B / C / D / F)**, using the descriptors below. 
Category grades are then combined into a single course grade using their weights.

---

## Category 1: Technical Contribution & Code Quality — 20%

**A note on story points.** Every issue in the repo carries a story point estimate (or you will assign them). 
Use story points as a signal of *complexity and risk*, not just throughput:

- **Volume of trivial work does not equal a strong grade.** A student who only ever picks up 1-point tasks — and does a lot of them — has avoided the harder judgment calls this work requires (design trade-offs, ambiguity, integration risk). High volume at low complexity caps out around a C/B-, regardless of how many issues were completed.
- **Ambition has a flip side.** Taking on a large task (5+ points) is worth encouraging, but a big task that's started and never finished (i.e., abandoned issues, never merged solutions, or requiring a teammate to bail it out later) has effectively zero impact on the project and carries real risk. That risk will show up in the grade.
- **What earns an A** is a track record of work scoped appropriately to your current skill level at a given point in the term. Consistently landing tasks in the 3–5 point range (or successfully breaking a larger task into shippable increments), with most of what was taken on actually merged, is an excellent way to ensure you are meeting the mark for this category.

**A note on early feedback and iteration.** This category grades what gets *merged*, not the quality of the initial Pull Request/early commits. 
Opening a PR early, even a draft, before every edge case is handled, to surface design questions and get reviewer eyes 
on if the approach is correct. What matters is whether feedback gets resolved thoughtfully before being merged, not whether a 
first draft drew comments. A review thread with zero comments isn't automatically a sign of quality.

| Grade | Description                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **A** | Final merged code is well-architected, aligned with project conventions, and handles edge cases well. Reviewer feedback, including feedback drawn out by an early or draft PR, is addressed thoughtfully and fully before merge. Overall, consistently took on real complexity (3+ point tasks, or larger work broken into shippable stages) and successfully merged the majority of it.                                                       |
| **B** | Final merged code is solid and functional, mostly following conventions. Most reviewer feedback is resolved before merge, with only minor points carried forward as follow-ups. Overall, taking on moderate complexity (roughly 2–3 point tasks).                                                                                                                                                                                              |
| **C** | Final code is functional but shows gaps (e.g., style inconsistencies, mild code smells, thin edge-case handling) **or** reviewer feedback is repeatedly left unresolved or only partially addressed, requiring the same issue to be re-flagged. Overall, complexity is consistently low (mostly 1-point tasks) even if volume is high, **or** the student occasionally reached for higher-complexity work but left it unfinished or abandoned. |
| **D** | Contributions are minimal, or reviewer feedback is routinely ignored, requiring the reviewer or a teammate to fix the issue directly rather than the student iterating on it. Includes taking on a high-point task and abandoning it without a fallback, leaving a gap in the project.                                                                                                                                                         |
| **F** | No meaningful code contribution, or contributions ship with known, flagged bugs/regressions that were never addressed. Includes over-committing to a large task, failing to deliver it, and not communicating or re-scoping in time.                                                                                                                                                                                                           |


## Category 2: Git/GitHub Workflow & Process — 15%

| Grade | Description                                                                                                                                                                                                   |
|---|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **A** | Commit messages are clear and atomic. PRs are appropriately scoped with good descriptions (linked issues, rationale, test notes, screenshots where relevant). Clean branch hygiene. Created issues are clear. |
| **B** | Generally good practices with occasional lapses: a vague commit message, an oversized PR.                                                                                                                     |
| **C** | Inconsistent practices: poor git branch management, large/unclear commits, sparse PR descriptions, vague or unclear new issues.                                                                               |
| **D** | Poor practices throughout: dumped commits (e.g., "fix stuff"), missing PR descriptions, history-breaking force pushes.                                                                                        |
| **F** | Did not follow basic contribution workflow. Created more work for the repository owner                                                                                                                        |

## Category 3: Code Review & Collaboration — 20%

| Grade | Description                                                                                                                                                                                                          |
|---|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **A** | Actively reviews peers' PRs with substantive, specific, non-judgmental feedback. Responds to feedback on own PRs promptly and without defensiveness, iterating well. Engages in issue threads and design discussions. |
| **B** | Reviews some PRs usefully; responds reasonably well to feedback on own work. Nominally engages in issue threads and design discussions.                                                                              |
| **C** | Minimal review participation; responds to feedback, but slowly or superficially. Drops conversations in issue threads and design discussions.                                                                        |
| **D** | Little to no review participation; judgmental reviews or discussion; defensive or unresponsive to reasonable feedback.                                                                                               |
| **F** | No collaborative engagement with the team or project.                                                                                                                                                                |

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

| Grade | Description                                                                                                                                                                  |
|---|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **A** | Consistent contribution cadence across the term (not just before deadlines); proactively communicates blockers or delays; professional tone in PRs, issues, and discussions. |
| **B** | Mostly consistent with minimal gaps; generally professional.                                                                                                                 |
| **C** | Bursty/last-minute contribution pattern; communication is reactive rather than proactive.                                                                                    |
| **D** | Long stretches of silence with little communication, moments of unprofessional communication.                                                                                |
| **F** | No communication; disappeared from the project; conduct was unprofessional.                                                                                                  |

---

## Evidence Sources

| Category | GitHub Evidence                                                                          |
|---|------------------------------------------------------------------------------------------|
| **Code Quality** | Diff view on merged PRs, "Files changed" tab, test outputs                               |
| **Workflow/Process** | Commit history (`git log`), PR descriptions, branch list, issues created                 |
| **Review & Collaboration** | "Conversation" tab on others' PRs, review comments left, response time on own PR threads |
| **Initiative** | Issues opened, issues self-assigned, discussion posts, linked design docs                |
| **Testing/Docs** | Diffs touching test suites, README, inline docstrings, source code comments              |
| **Consistency** | Contributors graph / Insights → Contributors, commit timestamps across the term          |

Most often, a lack of evidence occurs because a student does not drive enough in the pair-programming/driver-navigator 
process. It is your responsibility as a student to ensure you are contributing 
equally in both roles, driver and navigator, and providing ample opportunity to your partner to also contribute in each 
role.  

---

## Calculating the Final Grade

Each letter grade maps to points: **A = 4, B = 3, C = 2, D = 1, F = 0**.

```
Weighted Score =
  (Technical Quality × 0.20) +
  (Workflow/Process  × 0.15) +
  (Review & Collab   × 0.20) +
  (Initiative        × 0.15) +
  (Testing & Docs    × 0.15) +
  (Professionalism   × 0.15)
```

Converted back to a final letter grade:

| Weighted Score |          | Final Grade |
|----------|----------|----|
| **Min**  | **Max**  |    |   
| 3.67     | 4.0      | A+ |        
| 3.34     | 3.66     | A  |    
| 3.0      | 3.33     | A- |    
| 2.67     | 2.99     | B+ |    
| 2.34     | 2.66     | B  |    
| 2.0      | 2.33     | B- |    
| 1.67     | 1.99     | C+ |    
| 1.34     | 1.66     | C  |    
| 1.0      | 1.33     | D  |    
| 0.0      | 0.99     | F  |    

---

### Final Note

**Peer feedback** in the form of a short end-of-term anonymous survey, will ask you and your teammates to rate responsiveness and review quality to catch items things that aren't visible in the commit history alone. 

Peer feedback can move an individual as much as one full letter grade (e.g., B- to C-) in either direction (e.g., C+ to B+), depending on the level of detail and egregiousness (either positive or negative). 
