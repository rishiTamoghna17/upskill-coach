# Upskill Coach

A Claude Code setup that acts as Rishi's personal interview-prep coach for the 2027 job switch.

## Set up (10 minutes)
1. Create a **private** GitHub repo called `upskill-coach` and push this folder to it.
2. Clone it next to your project repo, `cd upskill-coach`, and run `claude`.
3. Try `/today`, `/explain sliding window`, `/resources consistent hashing`.

Claude Code reads `CLAUDE.md` automatically, so every session knows your goal, plan, tracker and coaching rules.

## Daily use
| Command | What it does |
|---|---|
| `/today` | Today's tasks, catch-up, pace, a 5-minute primer, resources, one question |
| `/explain <topic>` | Deep explanation with interview angle and check questions |
| `/review [file / PR / paste]` | Senior-level review of a DSA solution, LLD exercise or project change |
| `/quiz [topic]` | 5-question quiz, biased toward weak and recent topics |
| `/mock <dsa / lld / hld / behavioral> [company]` | Realistic mock round with a scorecard |
| `/resources <topic>` | The best 1–3 verified blogs, videos or docs |
| `/weekly` | Weekly scorecard, code review of the week's commits, next-week plan |

Subagents in `.claude/agents/`: `tutor`, `code-reviewer`, `resource-curator`, `mock-interviewer`.

## Reviewing your project code
- Run `/review` inside the Credit-Ops Copilot repo (copy `.claude/agents/code-reviewer.md` into that repo's `.claude/agents/`), or
- Install the Claude GitHub App on the project repo and add a routine at claude.ai/code/routines with a GitHub trigger on `pull_request.opened`, prompt: "Review this PR using the code-reviewer checklist in upskill-coach".

## Progress memory
Everything the coach learns about you goes in `progress/`. Commit it so routines and other machines see the same history.

## Rules baked in
Synthetic data only, hints before answers on DSA, honest reviews, verified links only.
