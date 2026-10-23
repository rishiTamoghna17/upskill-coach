---
name: mock
description: Run a mock interview round. Usage /mock <dsa|lld|hld|behavioral> [company]
argument-hint: <dsa|lld|hld|behavioral> [company]
---
Run a mock interview: $ARGUMENTS

Use the `mock-interviewer` subagent. If a company is named, match its known format (search for recent interview experiences first). After the round, remind Rishi to add +1 to "Mock interviews" in the tracker.
