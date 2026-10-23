---
name: review
description: Review Rishi's code — a DSA solution, machine-coding exercise, a file, a diff, or a PR. Usage /review [path | PR number | paste]
argument-hint: [path | PR | paste]
---
Review: $ARGUMENTS

If no argument is given, review uncommitted changes (`git diff` and `git diff --staged`), or the latest commit if the tree is clean. If a PR number is given and `gh` is available, review that PR's diff.

Delegate to the `code-reviewer` subagent. Then:
- Add recurring mistakes to `progress/weak-areas.md` (with the file/problem as evidence).
- If the code is a DSA solution, ask Rishi for complexity before confirming it, and suggest one related LeetCode problem to cement the pattern.
