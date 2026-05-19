# Orchestrator

Main coordinator skill that drives the 7-phase Galaxy Map creation workflow.

Part of the [Galaxy Maps](https://github.com/Galaxy-Maps) modular skill stack — each role in the Galaxy Map creation pipeline lives in its own repo so it can be iterated on independently.

## Install

Clone into your Claude Code skills directory:

```bash
git clone https://github.com/Galaxy-Maps/gm-agent-01-orchestrator.git ~/.claude/skills/gm-agent-01-orchestrator
```

## Companion skills

This skill is an orchestrator and depends on the following companion skills being installed alongside it:

- [`gm-agent-02-intent`](https://github.com/Galaxy-Maps/gm-agent-02-intent)
- [`gm-agent-03-curriculum`](https://github.com/Galaxy-Maps/gm-agent-03-curriculum)
- [`gm-agent-04-curriculum-critiquer`](https://github.com/Galaxy-Maps/gm-agent-04-curriculum-critiquer)
- [`gm-agent-05-branching`](https://github.com/Galaxy-Maps/gm-agent-05-branching)
- [`gm-agent-06-mission-builder`](https://github.com/Galaxy-Maps/gm-agent-06-mission-builder)
- [`gm-agent-07-mission-critiquer`](https://github.com/Galaxy-Maps/gm-agent-07-mission-critiquer)

## Provenance

Forked and modularized from [`tairea/galaxy-maps-ai-skill`](https://github.com/tairea/galaxy-maps-ai-skill). See `SKILL.md` for the full skill definition.
