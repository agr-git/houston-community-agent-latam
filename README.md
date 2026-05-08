# Houston Community Agent — Latam
> A Houston agent that ingests WhatsApp community conversations, GitHub issues, and other signals from the Houston Latam ecosystem, then produces structured triage reports for the Houston team.
**Status:** v0.1 — first build of the Houston Latam Builder Series.
**Author:** Alejandro Gil Rivera ([@agr-git](https://github.com/agr-git))
**Built on:** [Houston](https://github.com/gethouston/houston)
---
## What this agent does
Daily ingest of community signals → structured digest for the Houston team:
- **Diagnose:** extracts bugs, repeat questions, sentiment trends from WhatsApp + community channels
- **Identify:** surfaces emerging power users and contributor candidates
- **Prioritize:** ranks issues by frequency, severity, and strategic tier
- **Output:** ready-to-action digest for Felipe, Julián, and the team
## How to use this agent
1. Install Houston: https://github.com/gethouston/houston
2. In Houston: **New Agent → GitHub** → paste this repo URL
3. Houston imports the agent. Done.
## How it works
The agent lives in two files:
- `houston.json` — agent definition (tabs, integrations, metadata)
- `CLAUDE.md` — the instructions Claude follows when this agent runs
See [STRUCTURE.md](./STRUCTURE.md) for the full design rationale.
## Roadmap
| Version | Status | Capability |
|---------|--------|------------|
| v0.1 | 🟡 In progress | Manual ingest of WhatsApp, basic triage digest |
| v0.2 | ⏳ Next | GitHub issues triage, integrated FAQ updates, routines |
| v0.5 | ⏳ Planned | Custom skills, bilingual, board automation |
| v1.0 | ⏳ Planned | Mobile companion, multi-community support |
## License
MIT — see [LICENSE](./LICENSE)
---
*Part of the Houston Latam Builder Series.*
