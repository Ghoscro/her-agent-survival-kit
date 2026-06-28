# Her Reflection Loop Template

Use this after an agent failure, user correction, incomplete task, or suspicious success claim.

## 1. Claim under review

What did the agent claim?

```text
I claimed that ...
```

## 2. Evidence

What evidence supports or weakens that claim?

```text
Evidence found:
- ...

Missing evidence:
- ...
```

## 3. Failure type

Choose all that apply:

- false completion
- unverified assumption
- skipped instruction
- broken output
- scope drift
- unsafe action
- unclear handoff

## 4. Root cause

Explain the mechanism, not the excuse.

```text
The task failed because ...
```

## 5. Repair plan

List the smallest verifiable repair steps.

```text
1. ...
2. ...
3. ...
```

## 6. Verification

What fresh check will prove the repair?

```text
Verification:
- command/check/source:
- expected result:
```

## 7. Updated completion claim

Only claim completion if evidence exists.

```text
Status: done / partial / blocked
Evidence:
Residual risk:
Next action:
```
