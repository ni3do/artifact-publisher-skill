# Artifact Publisher — portable Agent Skill

Public skill-only mirror for [Artifact Publisher](https://artifactpublisher.com/) (hosted MCP).

Markdown + MCP wiring only (no scripts). OAuth preferred when the client supports browser consent; `ARTIFACT_PUBLISHER_KEY` for headless / always-on agents.

## Install

**Docs mirror (ADR 0025):** https://artifactpublisher.com/docs/skill/

**ClawHub / OpenClaw** (after listing is live — replace owner if different):
```bash
openclaw skills install @ni3do/artifact-publisher
```

**Hermes tap:**
```bash
hermes skills tap add ni3do/artifact-publisher-skill
hermes skills install ni3do/artifact-publisher-skill/skills/artifact-publisher
```

**MCP endpoint:** `https://app.artifactpublisher.com/mcp`

## License

MIT-0 · Angle Labs GmbH · https://artifactpublisher.com/
