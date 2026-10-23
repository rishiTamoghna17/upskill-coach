---
name: explain
description: Explain a topic in depth with intuition, examples, interview angle and check questions. Usage /explain <topic>
argument-hint: <topic>
---
Explain: $ARGUMENTS

Use the `tutor` subagent's structure. Tie the explanation to the current week of the plan and to the Credit-Ops Copilot project where it fits. After Rishi answers the check questions, give feedback and append a line to `progress/learning-log.md`:
`YYYY-MM-DD | <topic> | confidence n/5 | revisit: <what>`
