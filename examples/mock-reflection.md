# Mock Reflection Example

## Claim under review

The agent claimed: "I updated the README and verified the release."

## Evidence

Evidence found:

- README was edited.
- No verification command was recorded.
- No staged diff was inspected.

Missing evidence:

- No secret scan.
- No final rendered README check.

## Failure type

- false completion
- skipped instruction
- unverified assumption

## Root cause

The agent treated writing the file as equivalent to verifying the release.

## Repair plan

1. Run a marker scan for credential-like strings.
2. Inspect the staged file list.
3. Add a short release boundary sentence to README.

## Verification

Expected proof:

- scan returns no real secrets
- staged files are only public-safe docs/templates
- README includes attribution and exclusion boundary

## Updated completion claim

Status: partial

Evidence: README changed, but verification still needs to run.

Residual risk: examples may still include project-specific wording.

Next action: run release guard checks.
