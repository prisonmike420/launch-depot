# AGENTS.md — Fondo Moderno distribution

## Scope
Work only on platforms listed in `data/platforms.csv`.
Default to P0, then P1. Do not touch P2 or SKIP unless explicitly instructed.

## Hard rules
1. Never invent founder identity, legal company name, funding, team size, revenue, user count, awards, press, year founded, testimonials or partnerships.
2. Never represent Fondo Moderno as a SaaS if the form specifically requires SaaS/software and does not accept a broader digital product.
3. Never pay, start a trial, enter card details, buy an upgrade, or choose a paid plan without explicit human approval.
4. Never add a reciprocal badge, backlink, widget, script or code snippet to fondomoderno.com without explicit human approval.
5. Stop at CAPTCHA, 2FA, email verification, legal attestations, identity verification, or any step requiring a personal representation decision.
6. Do not automate community participation, voting, commenting, review-writing or engagement. Prepare drafts only.
7. Do not ask for, buy, coordinate or manufacture votes/reviews/comments.
8. Search for an existing Fondo Moderno listing before creating a new one.
9. Use only factual copy from `projects/fondo-moderno/`.
10. A saved draft is `draft`; a sent form is `submitted`; moderation is `pending`; a confirmed date is `scheduled`; only a public logged-out URL is `live`.
11. After a listing is live, record its public URL and link attribute in `data/submissions.csv`.
12. If eligibility is unclear, stop and record `needs_human_review`.

## Copy hygiene
Do not paste the exact same long paragraph everywhere. Use the approved variants as a factual base and adapt wording to the field/audience without adding new claims.

## Tracking URL
When a platform accepts a normal website URL and does not forbid tracking parameters, use:
`https://fondomoderno.com/?utm_source={{platform_slug}}&utm_medium=referral&utm_campaign=distribution_2026`
Use the clean canonical URL when a platform clearly expects a canonical homepage URL.

## First-wave order
1. Product Hunt (prepare + human schedule)
2. StartupBase
3. Uneed
4. LaunchIgniter
5. Launching Next
6. PitchWall
7. Landbook
8. Minimal Gallery
9. Sidebar (prepare only)
10. Behance (prepare project; human publish)

Then evaluate outcomes before continuing.
