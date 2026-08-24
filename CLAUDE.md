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

# All named agents
claude plugin install pitch-agent@claude-for-financial-services
claude plugin install earnings-reviewer@claude-for-financial-services
claude plugin install gl-reconciler@claude-for-financial-services
claude plugin install kyc-screener@claude-for-financial-services
claude plugin install market-researcher@claude-for-financial-services
claude plugin install meeting-prep-agent@claude-for-financial-services
claude plugin install model-builder@claude-for-financial-services
claude plugin install month-end-closer@claude-for-financial-services
claude plugin install statement-auditor@claude-for-financial-services
claude plugin install valuation-reviewer@claude-for-financial-services
```

- `financial-analysis` — core skills + connectors (comps, DCF, LBO, 3-statement, xlsx/pptx authoring).

Named agents (each self-contained, bundles its own skills):

| Function | Agent | What it does |
|---|---|---|
| Coverage & advisory | `pitch-agent` | Comps, precedents, LBO → branded pitch deck |
| | `meeting-prep-agent` | Briefing pack before client meetings |
| Research & modeling | `market-researcher` | Sector/theme → overview, landscape, comps, ideas |
| | `earnings-reviewer` | Earnings call + filings → model update → note draft |
| | `model-builder` | DCF, LBO, 3-statement, comps — live in Excel |
| Fund admin & finance ops | `valuation-reviewer` | GP packages → valuation template → LP reporting |
| | `gl-reconciler` | Finds breaks, traces root cause, routes for sign-off |
| | `month-end-closer` | Accruals, roll-forwards, variance commentary |
| | `statement-auditor` | Audits LP statements before distribution |
| Operations & onboarding | `kyc-screener` | Parses onboarding docs, runs rules engine, flags gaps |

All plugins are installed at user scope, so a fresh environment must re-run the commands above before they're available.

---

_This file should be updated once the codebase is established with build commands, architecture notes, and development workflows._
