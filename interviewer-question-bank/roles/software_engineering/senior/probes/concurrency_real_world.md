---
id: se.senior.probe.concurrency
role: software_engineering
level: senior
question_type: probe
topics: [concurrency, multithreading]
signals:
  - real_world_experience
  - risk_awareness
  - debugging_maturity
difficulty: medium
expected_time_minutes: 5
vectorize: true
version: 1
---

## Question
What kinds of concurrency issues have you actually seen in real systems, and how did you deal with them?

## What this tests
- Practical experience with concurrency
- Ability to reason about race conditions beyond theory

## Acceptable answers
- Mentions race conditions, data corruption, inconsistent state
- Talks about detection (logs, metrics, reproducing under load)
- Mentions prevention (locks, immutability, idempotency, design changes)

## Red flags
- Pure textbook definitions
- No real examples
- Overconfidence (“we never had issues”)
