# Agent Improvement Plans (AIPs)

This repository is the **canonical AIP number registry**. Each GitHub issue is one AIP:

> **Issue #N = AIP `{N:04d}`** (e.g. issue #1 = AIP 0001, issue #42 = AIP 0042)

Issue numbers are permanent and sequential — this is how AIP numbers stay stable across sessions and repos.

## What's here

- `.github/ISSUE_TEMPLATE/aip.md` — template enforced when opening a new AIP issue
- `.github/workflows/` — CI that lints AIP metadata on issue open/edit

## What's NOT here

Plan file content, implementation artifacts, hooks, and source code live in
[agent-improvement](https://github.com/joeblackwaslike/agent-improvement) repo.

## AIP lifecycle

| Status | Meaning |
|--------|---------|
| `draft` | Being written |
| `review` | Ready for review |
| `approved` | Ready to implement |
| `in-progress` | Being implemented |
| `completed` | Implemented and validated |
| `rejected` | Not moving forward |
| `deferred` | Paused, revisit later |

## AIP areas

`search` · `browser` · `memory` · `tools` · `hooks` · `context` · `performance`

## Creating a new AIP

Use the `/new-plan` command in the `agent-improvement` repo. It opens an issue in this repo automatically.
The issue number becomes the AIP number. The plan file is created at
`docs/improvement-plans/{NNNN}-{slug}.md` in `agent-improvement`.
