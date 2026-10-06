# What is a Forward Deployed Engineer?

**An FDE is a software engineer who owns customer *outcomes* — not customer relationships, not
satisfaction scores, but the actual results the customer is trying to achieve with the software.**
(Definition per [vinoo.io's guide](https://vinoo.io/writing/2026-02-05-forward-deployed-engineering/).)

## Where the role came from

Palantir created the role around 2005 because its CIA/NSA-class customers had problems that could
not be solved remotely: classified networks, broken data environments, no helpdesk, and domain
context that never survives a requirements document. Instead of consultants, Palantir embedded
cleared **engineers** on-site for months at a time. They learned the customer's domain, wrote
production code against the customer's real data, and fed what they learned back to headquarters
as product requirements.

The name is military: "forward deployed" means stationed where the fight is, not at base.

## The three commitments

A modern FDE engagement centers on three commitments:

1. **Live on the customer's site** — embedded 30–40 hours a week (Palantir FDEs classically spent
   3–4 days/week at the customer; Qureshi spent a year, 4 days a week, inside the Airbus factory
   in Toulouse).
2. **Ship working code immediately** — a working transform, dashboard, or prototype in week one.
   Time-to-value measured in days, against the industry's 90-day discovery habit.
3. **Own the entire data-to-decision loop** — including continuous customer discovery
   (5–15 customer conversations a week is treated as core engineering work, not sales work).

## What an FDE is NOT

- **Not a sales engineer** — the sales engineer's job ends when the deal closes; the FDE's job
  *starts* there and is measured on usage and outcomes.
- **Not a consultant** — consultants bill time against a statement of work; FDEs ship product-grade
  software and their learnings are an R&D input, not a billable deliverable.
- **Not staff augmentation** — the playbook explicitly *refuses* systems-integration work. The
  customer gets an application they own; the vendor keeps the generalizable patterns.
- **Not a solo act** — at Palantir every Delta (FDE) pairs with an Echo (Deployment Strategist)
  who carries the domain knowledge and the institutional politics. See
  [Delta–Echo pairing](./01-core-concepts/delta-echo-pairing.md).

## Why it matters right now (2025–2026)

FDE job postings grew **>800% between January and September 2025**. OpenAI built an FDE org
(targeting ~50 engineers by end-2025, $220–280K + equity in NY postings); Anthropic grew its
Applied AI group and lists Forward Deployed Engineer roles with a manager track; 100+ YC startups
hire FDEs. The reason: AI systems don't fail at the model layer, they fail at the *deployment*
layer — messy data, undefined workflows, institutional skepticism — which is exactly the layer
the FDE model was invented to attack.

→ Next: [Dev vs Delta](./01-core-concepts/dev-vs-delta.md), the split that makes the model work.
