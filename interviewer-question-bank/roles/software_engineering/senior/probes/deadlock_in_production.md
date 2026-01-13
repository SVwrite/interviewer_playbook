---
id: se.senior.probe.deadlocks
role: software_engineering
level: senior
question_type: probe
topics: [concurrency, databases]
signals:
  - failure_analysis
  - system_debugging
difficulty: medium
expected_time_minutes: 5
vectorize: true
version: 1
---

## Question
Have you ever encountered a deadlock in production or staging?  
How did it manifest, and how was it resolved?

## What this tests
- Exposure to real system failures
- Ability to diagnose non-obvious issues

## Acceptable answers
- Explains symptoms (timeouts, stuck threads, DB waits)
- Mentions tools or signals used to detect it
- Discusses prevention strategies

## Red flags
- Only defines what a deadlock is
- No experience-based explanation
