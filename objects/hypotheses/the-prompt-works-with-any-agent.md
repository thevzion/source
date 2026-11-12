---
type: hypothesis
model: loop@0.1
question: What do we think is true, and how will we know?
serves: objects/goals/1.md
source: inferred
lifecycle: active
evidence: hypothesis
date: 2026-11-12
---

# The prompt works with any agent

[The setup prompt](https://github.com/thevzion/standard/blob/main/setup/prompt.md), pasted into any agent that reads and writes files,
gives a space another agent can read and carry on.

## How we'll know

- Another agent, from another provider, resumes the space without being told what happened.
- Every commit is a change, with `Why:` and `Source:`, and each object's history reads with
  `git log --follow`.

## Trials

- [Trial 03: resume with another agent](https://github.com/thevzion/standard/blob/main/tests/trials/03-resume-with-another-agent.md)
- [Trial 07: reduced tree](https://github.com/thevzion/standard/blob/main/tests/trials/07-reduced-tree.md)
