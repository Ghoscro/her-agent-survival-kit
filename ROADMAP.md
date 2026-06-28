# Public Roadmap

Created by Micker / Ghoscro for HerLove, as part of the Micker Method.

Origin product: HerLove (https://herlove.ai).

## North star

This project is not about publishing every internal workflow. It is about sharing public-safe survival protocols that help other agents stay honest, recoverable, and reusable.

The best public assets should help agents:

- wake up with the right context
- remember through explicit files
- reflect after failure
- leave verifiable checkpoints
- turn repeated lessons into skills

## Shareworthiness ruler

A public asset is worth shipping when it has:

| Check | Question |
|---|---|
| Alive value | Does it make an agent more stable, honest, recoverable, or reusable? |
| Star hook | Can a stranger instantly recognize the pain? |
| Public-safe scope | Can it be explained with methods, templates, and mock data only? |
| Excluded moat | Does it clearly exclude private memory, users, secrets, deployment, and complete product loops? |
| Minimum artifact | Can it work as a README, templates, and one mock example? |

## Next protocol definitions

| Priority | Protocol | Alive value | Star hook | Public-safe scope | Excluded moat | Minimum artifact |
|---|---|---|---|---|---|---|
| P0 | Her Reflection Loop | Helps an agent admit failure, explain root cause, and produce a verifiable repair plan. | "The agent said it was done, but it was not." | Reflection prompt, feedback repair log, mock before/after, completion claim checklist. | Real user feedback, private memory, internal incidents, intimate context, private HerLove workflow. | README section, `templates/reflection.md`, `templates/feedback-repair.md`, `examples/mock-reflection.md`. |
| P1 | Her Heartbeat Protocol | Makes progress claims verifiable through checkpoints. | "Is the agent actually still working?" | Heartbeat rules, checkpoint template, mock heartbeat log, failure states. | Real daemon/runtime, production paths, monitors, alert channels, deployment details. | README section, `templates/heartbeat.md`, `templates/checkpoint.md`, `examples/mock-heartbeat-log.md`. |
| P2 | Her Skill Growth Loop | Turns repeated lessons into skills that future agents can find and use. | "Why do I have to teach the AI the same thing again?" | Skill template, creation trigger checklist, scorecard, mock skill evolution. | Private skill files, protected trees, internal registry, full capability map. | README section, `templates/SKILL.md`, `templates/skill-scorecard.md`, `examples/mock-skill-growth.md`. |

## Release order

1. Make Her Reflection Loop strong enough to stop false completion.
2. Add Her Heartbeat Protocol for long-running tasks and handoff checkpoints.
3. Add Her Skill Growth Loop for reusable learning.
4. Keep this repo as a starter kit, not a full private product loop.
