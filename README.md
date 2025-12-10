# ADR (Architecture Decision Record) collection for Node CLI

This is ADR (Architecture Decision Record) collection containing Golden Path recommendations for working with Node CLI.

## Agents.md

This ADR collection is compiled into [_agents.md](_agents.md) file that you can copy into your Node CLI project as `AGENTS.md` to help your AI agent to take advantage of our ADR recommendations.

## Building

To create compiled [_agents.md](_agents.md) file execute the following command:

```bash
yax build
```

Yax build is called via [this CI pipeline](.github/workflows/yax.yml), so usually you don't have to run it manually.