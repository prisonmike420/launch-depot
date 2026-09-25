---
name: launch-depot
description: Research, prioritize, prepare, submit, and verify a website or digital product across relevant launch directories, design galleries, company databases, and editorial discovery channels. Use when the user wants directory submissions, launch distribution, backlink prospecting through legitimate profiles/listings, a submission tracker, or a reusable browser-agent workflow for product promotion.
---

# Launch Depot

Use this skill to build and execute a **relevance-first distribution workflow** for a real product or website.

This is not a bulk backlink workflow. A platform is eligible only when the project genuinely fits its current rules and the resulting presence would make sense to a human visitor.

## Required behavior

1. Establish a factual project profile before preparing submissions.
2. Treat `references/platform-seeds.csv` as a **seed list**, not current truth. Verify current rules, pricing, eligibility, submission path, reciprocal-link requirement, and moderation model before acting.
3. Prefer first-party platform documentation when verifying rules. Record the source URL and checked date.
4. Rank opportunities by relevance and durable discovery value before backlink metrics.
5. Never invent founder identity, legal entity, team size, funding, revenue, customers, traffic, awards, testimonials, partnerships, launch dates, or press.
6. Never misclassify a project as SaaS, AI, a startup, an architecture practice, or another entity type solely to pass a form.
7. Search for an existing listing before creating a duplicate.
8. Never pay, enter payment details, start a paid trial, install a reciprocal badge/backlink/script, or modify the target website without explicit human approval.
9. Stop at CAPTCHA, 2FA, email/identity verification, legal attestations, representative declarations, or any step that requires a person to make a factual/legal representation.
10. Do not automate votes, reviews, comments, follows, fake engagement, or community participation. Community and editorial channels require a human-quality pitch/post.
11. `draft`, `submitted`, `pending`, `scheduled`, and `live` are different states. Mark `live` only when a public URL works logged out.
12. After publication, record the public URL, observed outbound-link attribute if inspectable, indexation status when checked, and referral results when analytics are available.
13. If browsing/computer tools are unavailable, complete research/preparation only and state that no submission was performed.

## Workflow

### 1. Build the source-of-truth profile

Read the project website and any user-provided materials. Create:

- canonical product name;
- canonical URL;
- entity type in plain language;
- one-sentence positioning;
- real product capabilities/features;
- geography when material;
- current public counts/metrics only when they can be verified and are worth using;
- claims that must **not** be made without human confirmation.

Keep a dated note for time-sensitive numbers.

### 2. Create a copy kit

Prepare reusable factual variants:

- tagline / one-liner;
- short description (~150–180 characters when useful);
- medium description;
- long description;
- design-gallery framing if appropriate;
- startup/product framing only if accurate;
- maker/founder copy only after a human approves identity and first-person claims.

Do not force identical copy into every platform. Preserve facts while adapting the framing to the audience.

### 3. Research and classify platforms

Start with `references/platform-seeds.csv`, then expand only when useful.

For every candidate record:

- platform;
- lane (product launch, design gallery, company profile, community, editorial, etc.);
- current submission URL;
- eligibility;
- cost/free path;
- reciprocal badge/backlink requirement;
- moderation model;
- expected listing type;
- backlink behavior only when verified or observed;
- fit score;
- priority: `P0`, `P1`, `P2`, or `SKIP`;
- automation mode;
- source URL;
- checked date;
- reason.

Use these priority meanings:

- **P0** — strong audience/entity fit; worthwhile even without SEO benefit.
- **P1** — credible secondary distribution; some condition or weaker fit.
- **P2** — research/manual/low-priority channel.
- **SKIP** — entity mismatch, closed submissions, unacceptable requirement, or low-value spam risk.

### 4. Prepare assets

Inventory what each P0 platform requires. Prefer real current product screenshots and original assets. Do not fabricate interface screens, user quotes, media logos, ratings, or awards.

### 5. Create the tracker

Use the template in `assets/project-template/submissions.csv` or create an equivalent table with at least:

`platform, priority, status, account, submitted_at, scheduled_for, public_url, link_attribute, indexed, referral_sessions, notes`

Allowed status values:

`not_started, draft, submitted, pending, scheduled, live, rejected, not_fit, needs_human_review`

### 6. Execute submissions

Work P0 first unless the user directs otherwise.

For each platform:

1. Recheck current rules if the research is stale.
2. Search for an existing listing.
3. Open the correct official submission path.
4. Fill only verified factual fields.
5. Use accurate categories/tags rather than the category with the largest audience.
6. Choose the free route by default when both free and paid routes exist.
7. Stop at every approval boundary listed above.
8. Record the exact state immediately.

Do not continue through dozens of sites after finding a systematic issue with the profile, copy, assets, or eligibility. Fix the upstream problem first.

### 7. Verify and learn

For every claimed live placement:

1. Open the public URL logged out.
2. Confirm the project name and target URL are correct.
3. Inspect link treatment when possible (`follow`, `nofollow`, `sponsored`, redirect, JS-only, or unknown).
4. Later check whether the public listing is indexed when indexation matters.
5. Compare referral traffic and meaningful discovery against effort.
6. Update future priorities from observed results.

A low-DR relevant design/editorial page with real audience value can be more useful than dozens of generic directory links.

## Output expectations

When asked to research only, return a prioritized table and explain the important exclusions.

When asked to prepare a project, create a project folder containing:

- `profile.md`
- `copy.md`
- `product.json`
- `platforms.csv`
- `submissions.csv`
- `assets/README.md`
- platform-specific notes/playbooks when needed

When asked to execute, keep the tracker current and distinguish human-action blockers from failures.

## Bundled references

- `references/platform-seeds.csv` — researched seed list from the first Launch Depot pass. It is deliberately dated and must be reverified.
- `assets/project-template/` — generic files for initializing a new project workspace.
