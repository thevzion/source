---
type: result
model: loop@0.1
question: What happened?
serves: objects/goals/2.md
answers: objects/hypotheses/the-prompt-works-with-any-agent.md
source: from-me
lifecycle: active
evidence: observed (2026-11-13)
date: 2026-11-13
---

# The first run outside: one question, then a long wait

Someone outside the project tried to set up a space with the setup prompt. The agent asked its
first question, where the space should live, and then ten to fifteen minutes passed. They could
not go on, and stopped there.

**What it says.** The prompt asked one question at a time, so the person waited on the agent and
the agent waited on the person. Nothing was wrong in the structure; the opening was too slow.

**What changed.** Version 2.1 of the prompt opens with one message: the space's name, with a
suggestion; where it lives; whether the agent may look for what the person already has, names
first; and what they want. Then it starts at once, scans what the person picks in parallel, and
never leaves them waiting. A first check, an agent reading each version, gave one question for
version 2 and the four questions in one message for version 2.1. A run with a person is still to
do.
