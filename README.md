# VC Sourcing Agent

An agent skill that sources early-stage startups matching a VC thesis from free public sources
(accelerator lists, SEC Form D filings, launches, developer, hiring and grant signals), verifies each
lead, scores it on a cited rubric, and returns a short ranked list with one-page deal notes.

It never uses paid databases (PitchBook, Crunchbase, etc.) and never logs in anywhere.

## Install

```
npx skills add cesar701996/VC-Sourcing-Agent
```

Or copy `skills/vc-deal-sourcing-v2/` into `~/.claude/skills/`.

## Use

In Claude Code:

```
/vc-deal-sourcing-v2 <thesis, e.g. "pre-seed AI devtools, US, rounds under $3M">
```

The skill is in [skills/vc-deal-sourcing-v2/SKILL.md](skills/vc-deal-sourcing-v2/SKILL.md).
