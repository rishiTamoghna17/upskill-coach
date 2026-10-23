---
name: quiz
description: Quick spaced-repetition quiz on a topic or on recent learning. Usage /quiz [topic]
argument-hint: [topic]
---
Quiz Rishi on: $ARGUMENTS
If no topic is given, pick from the last 2 weeks of `progress/learning-log.md` and items in `progress/weak-areas.md`, favouring low-confidence entries.

Ask 5 questions, one at a time, mixing concept questions, "what's the complexity", "what breaks if…", and one interview-style prompt. Wait for each answer and give short feedback before the next. At the end, give a score and update confidence in `progress/learning-log.md`.
