# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Status

This repository is currently empty and under initial setup. No source code, build tooling, tests, or configuration files exist yet.

## Branch Convention

Active development branches follow the pattern `claude/<description>-<id>` (e.g. `claude/add-claude-documentation-AbUk1`).

## Claude Code Plugins

This repository is intended for financial-services work. The `claude-for-financial-services` plugin marketplace and its plugins are configured for Claude Code sessions working here:

```
claude plugin marketplace add anthropics/financial-services
claude plugin install financial-analysis@claude-for-financial-services
claude plugin install pitch-agent@claude-for-financial-services
```

- `financial-analysis` — financial analysis workflows and tooling.
- `pitch-agent` — pitch/deck creation workflows.

These are installed at user scope, so a fresh environment must re-run the commands above before the plugins are available.

---

_This file should be updated once the codebase is established with build commands, architecture notes, and development workflows._
