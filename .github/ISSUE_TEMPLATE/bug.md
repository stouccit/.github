---
name: Bug
about: Something is broken or behaving wrong
title: "fix: <short imperative summary>"
labels: ["tech"]
---

<!--
Examples:
  fix: scraper crashes on posts without caption
  fix: release workflow fails when v0.7.0 tag exists
  fix: OfflineService doesn't materialize sitecustomize.py in --reuse mode
-->

## What broke

One sentence: the observed misbehavior.

## Steps to reproduce

Concrete sequence — ideally something a teammate (or agent) can paste verbatim.

1. …
2. …
3. …

## Expected

What should have happened.

## Actual

What actually happened. Paste the error / log line / wrong output. For long stacks, wrap in `<details>`:

```
<stack trace / error here>
```

## Environment

- Service version (`pyproject.toml`):
- Commit SHA:
- Where it surfaced: local / CI / on-prem / GitHub Actions run URL
- Anything else relevant (Python version, OS, env vars, etc.)

## Suspected scope (optional)

If you have a hunch which module / file / commit introduced it, write it down. Saves the next person five minutes of grep.

## Notes / links (optional)

- Related PRs / issues: #
- Sentry / logs:
- Slack / TG thread:
