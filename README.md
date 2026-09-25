# Launch Depot

[![skills.sh](https://skills.sh/b/prisonmike420/launch-depot)](https://skills.sh/prisonmike420/launch-depot)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A reusable agent workflow for researching, prioritizing, preparing, and submitting digital products to relevant launch directories, **agent-skill registries**, design galleries, company databases, and editorial discovery channels.

Launch Depot is intentionally **not** a “submit everywhere” backlink bot. The workflow treats every platform as a current eligibility decision: relevance, cost, moderation model, reciprocal-link requirement, and backlink behavior must be verified before submission.

## Install with skills.sh / Vercel skills CLI

```bash
npx skills add prisonmike420/launch-depot --skill launch-depot
```

The canonical skill lives at:

```text
skills/launch-depot/SKILL.md
```

## Install as an OpenAI plugin

This repository is also a portable skills-only plugin: `plugin.json` and `skills/` live at the repository root.

Add the repo marketplace:

```bash
codex plugin marketplace add prisonmike420/launch-depot
```

Then install:

```bash
codex plugin add launch-depot@launch-depot
```

Start a new chat/session after installation.

## What is in this repository

- `skills/launch-depot/` — canonical Agent Skill, directly installable with the Vercel skills CLI.
- `plugin.json` — portable Agent Plugins manifest for ChatGPT/Codex.
- `.agents/plugins/marketplace.json` — repo marketplace entry for installing the plugin from GitHub.
- `examples/fondo-moderno/` — a complete worked example for [Fondo Moderno](https://fondomoderno.com/), including researched platforms, product copy, playbooks, safety rules, and submission tracker.
- `self-publish/` — Launch Depot’s own distribution campaign and tracker.
- `skills.sh.json` — grouping metadata for skills.sh.
- `LICENSE` — MIT.

## Typical requests

- “Research launch directories and skill registries for my product and rank only the relevant ones.”
- “Prepare this site for submissions and create a tracker.”
- “Submit my project to the free P0 platforms. Stop before payment, CAPTCHA, badge installation, or legal attestations.”
- “Check which previous submissions are live and whether the outbound links are normal, nofollow, or sponsored.”

## Operating principles

1. Relevance before volume.
2. Verify current platform rules before acting.
3. Never invent company, founder, traffic, funding, customer, award, or review data.
4. Never pay, add reciprocal badges, accept legal attestations, or pass identity/2FA steps without explicit human approval.
5. Community channels are not submission forms: do not automate votes, comments, reviews, or fake participation.
6. “Submitted” is not “live.” A placement becomes live only after its public URL works logged out.
7. Measure the result: public URL, link attribute, indexation, referral traffic, and editorial/discovery value.

## Fondo Moderno example

The `examples/fondo-moderno/` folder contains the first real research pass: 42 platforms split into P0/P1/P2/SKIP, 15 platform playbooks, product copy, asset requirements, and a submission tracker. It is an example, not a permanently current directory database; every platform should be rechecked before use.

## Self-publishing

Launch Depot uses itself as a distribution test case. The `self-publish/` folder records where the repository and skill should be listed, what can be automated, what needs human approval, and which placements become genuinely live.

The first target is [skills.sh](https://skills.sh/), where public repositories are discovered through the `skills` CLI install flow.
