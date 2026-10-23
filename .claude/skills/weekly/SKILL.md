---
name: weekly
description: Weekly progress review — pace vs plan, code review of the week's commits, weak areas, and adjustments for next week.
---
Run the weekly review.

1. Read the tracker (page source + `prep/state`) if available; otherwise ask Rishi for his numbers.
2. Compute: tasks done vs due this week and overall; DSA vs cumulative target; applications, mocks, interviews.
3. If the Credit-Ops Copilot repo is available, look at the last 7 days of commits (`git log --since="7 days ago" --stat`) and review the most important change with the `code-reviewer` subagent.
4. Read `progress/learning-log.md`, `progress/weak-areas.md` and `progress/interview-log.md`.
5. Write `progress/weekly/<YYYY>-W<week>.md` with:
   - **Scorecard**: on pace / slightly behind / behind, with numbers
   - **Wins** (max 3)
   - **Gaps** and why (be honest)
   - **Next week**: the 3 most important things, plus a catch-up plan if behind
   - **Read/watch next**: 1–2 resources for the weakest area
6. Show Rishi the summary in under 300 words.
