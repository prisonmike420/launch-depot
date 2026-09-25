# Launch Depot

A reusable agent workflow for researching, prioritizing, preparing, and submitting digital products to relevant launch directories, design galleries, company databases, and editorial discovery channels.

Launch Depot is intentionally **not** a “submit everywhere” backlink bot. The workflow treats every platform as a current eligibility decision: relevance, cost, moderation model, reciprocal-link requirement, and backlink behavior must be verified before submission.

## What is in this repository

- `plugins/launch-depot/` — installable skills-only plugin for ChatGPT/Codex.
- `plugins/launch-depot/skills/launch-depot/` — standalone Agent Skill. It can also be installed directly without the plugin wrapper.
- `examples/fondo-moderno/` — a complete worked example for [Fondo Moderno](https://fondomoderno.com/), including researched platforms, product copy, playbooks, safety rules, and submission tracker.
- `.agents/plugins/marketplace.json` — repo marketplace entry for installing the plugin from GitHub.

## Install as a plugin

Add this repository as a marketplace:

```bash
codex plugin marketplace add prisonmike420/launch-depot
```

Then install:

```bash
codex plugin add launch-depot@launch-depot
```

Start a new chat/session after installation.

## Install only the skill

From Codex, use the built-in skill installer with the GitHub folder:

```text
$skill-installer install https://github.com/prisonmike420/launch-depot/tree/main/plugins/launch-depot/skills/launch-depot
```

The installed skill will be available on the next session/turn supported by your client.

## Typical requests

- “Research launch directories for my product and rank only the relevant ones.”
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
