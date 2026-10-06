# A Week in the Life — What FDE Work Actually Looks Like

## The canonical story: Airbus, Toulouse

Nabeel Qureshi's deployment, told in [Reflections on Palantir](https://nabeelqu.co/reflections-on-palantir):

- **The setup.** A year in Toulouse, **4 days a week physically inside the A350 factory**, next to
  the people building the planes. Small team (deployments ran 4–5 people).
- **The problem.** Airbus needed to scale A350 production — and the information needed to do it
  (work orders, missing parts, quality issues, schedules) lived in disconnected systems.
- **The build.** One unified interface over integrated data: *"Asana, but for building planes."*
  No attempt at generality; the specific factory's specific problem.
- **The result.** Helped drive the A350 manufacturing surge — **~4x the pace of manufacturing**
  while keeping Airbus's quality standards.
- **The product echo.** PD engineers later abstracted the recurring parts into reusable Foundry
  components — the [flywheel](../01-core-concepts/productization-flywheel.md) in action.

## The texture of the week

Composite from the sources ([vinoo.io](https://vinoo.io/writing/2026-02-05-forward-deployed-engineering/),
getperspective.ai, Qureshi):

| Block | What's happening |
|---|---|
| On-site presence | 30–40 hours embedded (classic Palantir: 3–4 days/week at customer, Fri at HQ) |
| Customer discovery | 5–15 conversations/week — operators, analysts, the people whose workflow you're changing. Treated as engineering work. |
| Shipping | Daily iteration on the live deployment; week-one rule: something working on their data |
| Data wrangling | The silent majority: ingestion, cleanup, [ontology](../01-core-concepts/ontology-first.md) maintenance |
| Politics | Navigating gatekeepers with the [Echo](../01-core-concepts/delta-echo-pairing.md); demos aimed at the people who decide |
| Feedback loop | Written field reports / product requirements flowing back to Dev teams |

## What it feels like (both sides)

**The highs:** outsized ownership years before a big-tech peer would get it; watching a factory,
hospital, or agency visibly change because of your code; the alumni network reads like a founder
factory.

**The lows:** interrupt-driven by design — deep-focus engineers suffer; travel load is structural
(early Palantir's travel spend was "out of control"; United 1K as a lifestyle); customer
frustration lands on you personally unless you can compartmentalize; the
"hero–shithead rollercoaster" of a flat, titleless org where influence swings fast.

## The failure texture

A pilot where the political fight over data access eats 10 of 12 weeks, the demo gets 2, and the
champion who invited you in loses an internal battle — so perfect software dies unadopted. This
is why the model pairs engineers with [deployment strategists](../01-core-concepts/delta-echo-pairing.md)
and why [adoption, not code, is the real deliverable](./adopting-the-model.md).
