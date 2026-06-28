# Mock Skill Growth Example

## Repeated lesson

The agent repeatedly forgot to run a high-voltage scan before public sharing.

## Scorecard

| Question | Score |
|---|---:|
| Did this problem happen more than once? | 2 |
| Would a fresh agent benefit from explicit instructions? | 2 |
| Can the workflow be described without private data? | 2 |
| Is there a clear trigger phrase or situation? | 2 |
| Can success be verified? | 2 |
| Does it reduce future user explanation burden? | 2 |

Total score: 12

Decision: create skill

## Minimum skill artifact

```text
name: public-release-guard
description: Use before publishing public repositories or articles from a private workspace.
when_to_use: User asks to share, open source, publish, push, or create a public repo.
workflow: classify, scan, export clean bundle, stage explicit files, inspect diff, push.
safety_boundaries: no secrets, private memory, user data, deployment details, or full product loops.
verification: high-voltage scan, staged file list, boundary sentence.
example: mock release package with README and templates.
```
