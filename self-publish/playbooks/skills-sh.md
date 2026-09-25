# skills.sh

Checked: 2026-09-25

Official docs:
- https://skills.sh/docs
- https://skills.sh/docs/cli
- https://vercel.com/changelog/introducing-skills-the-open-agent-skills-ecosystem

## Publishing model
There is no separate author submit form documented for normal public skills. skills.sh is driven by the Vercel `skills` CLI and anonymous install telemetry. Vercel maintainers have also stated in current issue handling that repositories are automatically reindexed when someone runs `npx skills add`.

## Canonical repository layout
- `skills/launch-depot/SKILL.md`
- root `skills.sh.json`
- MIT `LICENSE`

## Install
```bash
npx skills add prisonmike420/launch-depot --skill launch-depot
```

## Verify
- `https://skills.sh/prisonmike420/launch-depot`
- `https://skills.sh/prisonmike420/launch-depot/launch-depot`
- `npx skills find launch-depot`

Do not manufacture repeated installs to influence leaderboard counts.
