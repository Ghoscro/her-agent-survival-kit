# Her Heartbeat Protocol Template

A heartbeat is not a claim that the agent is magically alive in the background.

A heartbeat is a verifiable checkpoint.

## Heartbeat rule

Only write a heartbeat when at least one of these is true:

- a file changed
- a command ran
- a source was checked
- a decision was made
- a blocker was discovered
- a handoff was created

## Heartbeat entry

```text
Time:
Goal:
Checkpoint:
Evidence:
Current state:
Next action:
Risk:
```

## Forbidden heartbeat claims

Do not write:

```text
Still working...
Thinking in the background...
I will keep running silently...
```

Unless there is a real runtime that can be inspected, these are not verifiable.

## Good heartbeat shape

```text
Time: 2026-01-01 10:15
Goal: Build the public-safe README
Checkpoint: Drafted README and ran a secret-marker scan
Evidence: README.md exists; scan found no credential markers
Current state: partial
Next action: add mock examples
Risk: examples still need review
```
