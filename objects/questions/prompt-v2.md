---
type: question
model: loop@0.1
question: What are we still asking?
serves: objects/projects/standard.md
source: inferred
lifecycle: active
evidence: open
date: 2026-11-12
---

# What should the second version of the setup prompt write?

The first prompt and the first trials wrote `org/<type>.md`. A v2 follows the reduced tree: `org/`
becomes `objects/`, `inbox/` becomes proposed changes, `sites.md` becomes `objects/sites/`,
`organization.md` becomes `space.md`, `orgs/` becomes `spaces/`.
[`setup/prompt.md`](../../setup/prompt.md) is a first answer, untested.

Settled by: [trial 00, first run](../../tests/trials/00-first-run.md) and
[trial 03, another agent](../../tests/trials/03-resume-with-another-agent.md).
