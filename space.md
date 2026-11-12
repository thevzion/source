---
space: thevzion
uri: thevzion/source     # the canonical address follows the repository name: objects/decisions/repository-name.md
standard: 0.1
models:
  - organization@0.1     # includes purpose@0.1, goals@0.1, work@0.1, loop@0.1, agreements@0.1
adapters:
  - folder+git
  - github
---

# TheVZion

The organization that writes the standard for executable organizations, and runs on it first.

Standard 0.1 · Organization model 0.1 · candidate, untested.

## Truth

| Where | Role |
|---|---|
| this repository | **Source** for the standard, the models and this space |
| the collective's workspace in Notion, for members | **Source** for day-to-day operations |
| thevzion.com, `llms.txt`, `structure.json`, the public Notion template | **Projections** of this repository |
| `objects/sites/` | **Pointers** to other spaces (none yet) |
| GitHub issues and discussions, Discord | **Inbox** |

Write at the source, read everywhere. A proposal becomes true only by a decision. See
[standard/truth.md](standard/truth.md).

## Access

| Verb | Who |
|---|---|
| read | everyone: this repository is public |
| propose | anyone, by an issue or a pull request |
| decide | the maintainers: a decision lands as a commit on `main` |

Private by default, shared by pointer. A member's home, vision and capital never live here.
See [standard/access.md](standard/access.md).

## Objects

| Folder | Types | Model |
|---|---|---|
| [`objects/`](objects/) | problem, why, mission, vision | Purpose |
| [`objects/goals/`](objects/goals/) | goal | Goals |
| [`objects/projects/`](objects/projects/), [`objects/tasks/`](objects/tasks/), [`objects/deliverables/`](objects/deliverables/) | project, task, deliverable | Work |
| [`objects/decisions/`](objects/decisions/), [`objects/hypotheses/`](objects/hypotheses/), [`objects/questions/`](objects/questions/) | decision, hypothesis, question | Loop |

Trials and checks live in [`tests/`](tests/). No local types and no child spaces yet.

## Provenance

The first objects were split from TheVZion's architecture notes (v0.29, not published), one
object per question. An agent wrote them. `source: from-me` marks only the decisions and
wordings the founder recorded; everything else is `source: inferred`, to review first.

Each change is a commit: `<object>(<operation>): …` with `Why:` and `Source:`
([standard/changes.md](standard/changes.md)).
