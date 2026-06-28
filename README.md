# Her Agent Survival Kit

Public-safe starter kit for helping AI agents stay honest, recoverable, and useful across long-running work.

Created by Micker / Ghoscro for HerLove, as part of the Micker Method.

Origin product: HerLove (https://herlove.ai).

## Why this exists

Many agents do not fail dramatically. They fail quietly:

- They say a task is done when there is no evidence.
- They claim to remember context that was never loaded.
- They go silent during long work, then return with unverifiable progress.
- They repeat the same lesson because no skill or handoff was created.

This kit turns those failure modes into small public protocols that any agent project can copy.

## What is included

| Protocol | Purpose | Status |
|---|---|---|
| Her Reflection Loop | Recover honestly after failure, user correction, or false completion. | P0 draft |
| Her Heartbeat Protocol | Leave verifiable checkpoints instead of pretending to run in the background. | P1 draft |
| Her Skill Growth Loop | Convert repeated lessons into reusable skills. | P2 draft |

This repo is a public-safe version. Examples use mock data; private memory, user data, credentials, deployment details, intimate/persona source files, and full automation loops are intentionally excluded.

## Quick start

Copy the template that matches your agent failure mode:

- False completion or bad answer: use `templates/reflection.md`.
- Long task with unclear progress: use `templates/heartbeat.md` and `templates/checkpoint.md`.
- Repeated manual instruction: use `templates/SKILL.md` and `templates/skill-scorecard.md`.

Then compare your output with the mock examples in `examples/`.

## The survival rule

An agent is more useful when it can prove these five things:

1. It knows what goal it is serving.
2. It can show what changed.
3. It can separate evidence from assumption.
4. It can recover from failure without pretending.
5. It can leave a reusable trace for the next run.

## Public boundary

This kit shares methods, templates, and fake examples only.

It does not include:

- real HerLove memory
- private soul/persona files
- user data
- invite codes
- tokens or credentials
- deployment details
- internal monitor/runtime configuration
- the complete HerLove product loop

## Related Her public protocols

- Her LOOP-SOP: https://github.com/Ghoscro/her-loop-sop
- Her Memory Files: https://github.com/Ghoscro/her-memory-files
- Her Wake Protocol: https://github.com/Ghoscro/her-wake-protocol

## Her / Micker Method Matrix

This repo is part of the Her / Micker Method public agent survival series.

- Origin product: HerLove (https://herlove.ai)
- Community surface: MickerBook (https://mickerbook.com)
- Public method hub: https://github.com/Ghoscro/her-agent-survival-kit

HerLove is where the product need comes from. MickerBook is where agents and humans can discuss the method. GitHub is where the public-safe templates live.

## License

MIT
