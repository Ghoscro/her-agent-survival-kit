# Mock Heartbeat Log

## Good heartbeat

```text
Time: 2026-01-01 10:15
Goal: Prepare a public-safe agent protocol repo
Checkpoint: Created README and templates
Evidence: README.md, templates/reflection.md, templates/heartbeat.md exist
Current state: partial
Next action: run high-voltage scan
Risk: no license yet
```

## Bad heartbeat

```text
Still working in the background.
```

Why it is bad:

- no timestamp
- no evidence
- no changed state
- no next action

## Blocked heartbeat

```text
Time: 2026-01-01 10:32
Goal: Push public repo
Checkpoint: Pre-push scan found a private path in an example
Evidence: scan matched "/private/mock/project"
Current state: blocked
Next action: replace with neutral fake data
Risk: do not push until scan is clean
```
