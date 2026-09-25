# Self-publish Launch Depot

Use this folder to distribute Launch Depot itself.

## Source of truth
- Project profile: `self-publish/profile.md`
- Copy: `self-publish/copy.md`
- Tracker: `self-publish/submissions.csv`
- Platform notes: `self-publish/playbooks/`
- Canonical skill: `skills/launch-depot/SKILL.md`
- Canonical repo: https://github.com/prisonmike420/launch-depot

## Order

### P0
1. skills.sh
2. SkillsMP
3. Skills Directory
4. AwesomeSkills.dev
5. Skill Store

### P1
6. ClaudSkills
7. Microsoft CAT Agent Skills
8. Codex Marketplace
9. OpenAI universal plugin directory

Do not work P2 until P0/P1 results have been checked.

## Execution rules
1. Recheck each platform's current submission rules before acting.
2. Search for an existing Launch Depot listing before creating another.
3. Use the canonical GitHub repo/skill URL.
4. Do not invent author identity, contact email, install counts, stars, usage, affiliation, endorsements, or security grades.
5. Stop for login, email ownership, CAPTCHA, payment, legal terms, public author identity, or repository forking when the current agent cannot perform it legitimately.
6. Do not manufacture installs, stars, votes, reviews, comments, or repeated telemetry.
7. Mark `submitted` only after a form/PR/request is actually sent.
8. Mark `live` only after opening the public listing logged out.
9. Store the public URL and any useful backlink/indexation observation in `submissions.csv`.

## skills.sh
The normal publication path is a real CLI install:

```bash
npx skills add prisonmike420/launch-depot --skill launch-depot
```

One genuine installation is enough to enqueue discovery/reindexing. Never automate repeated installs to influence the leaderboard.

## GitHub-crawled directories
Where a catalog crawls public GitHub rather than accepting a direct form, verify the required repository topics/metadata and then wait for a real crawl. Do not claim publication before a public listing exists.
