# Palantir FDE Mental Map

> A mental map of what Palantir's **Forward Deployed Engineer (FDE)** model actually entails —
> the role, the org design around it, the economics, and why every AI company is now copying it.

Unlike the repo-synced maps (openab-map, herdr-map), this map tracks a *practice*, not a codebase.
It is curated from primary and secondary public sources (listed in [05 · Sources](./05-sources/SOURCES.md))
and stamped with a last-reviewed date instead of a sync SHA.

**If you're new → start at [What is an FDE](./00-what-is-an-fde.md)**

---

## Map Layers

| Layer | What it answers |
|-------|----------------|
| [00 · What is an FDE](./00-what-is-an-fde.md) | One-page pitch. The role, where it came from, why it matters now. |
| [01 · Core Concepts](./01-core-concepts/) | The ideas you must internalize: [Dev vs Delta](./01-core-concepts/dev-vs-delta.md), the [Delta–Echo pairing](./01-core-concepts/delta-echo-pairing.md), [ontology-first deployment](./01-core-concepts/ontology-first.md), the [productization flywheel](./01-core-concepts/productization-flywheel.md), and the [talent profile](./01-core-concepts/talent-profile.md). |
| [02 · Mental Models](./02-mental-models/) | How the pieces fit: the [engagement lifecycle](./02-mental-models/engagement-lifecycle.md), [FDE vs adjacent roles](./02-mental-models/fde-vs-adjacent-roles.md), and [the consulting trap](./02-mental-models/the-consulting-trap.md). |
| [03 · Use Cases](./03-use-cases/) | What the work looks like: [a week in the life](./03-use-cases/a-week-in-the-life.md) (incl. the Airbus story) and [adopting the model at your company](./03-use-cases/adopting-the-model.md). |
| [04 · Decision Trees](./04-decision-trees/) | [Should you hire FDEs?](./04-decision-trees/should-you-hire-fdes.md) |
| [05 · Sources](./05-sources/SOURCES.md) | Annotated reading list — primary sources first. |

---

## The One-Paragraph Version

Palantir split engineering into **Devs** (build one capability for many customers — Foundry, Gotham,
AIP) and **Deltas** (FDEs: enable many capabilities for one customer, embedded on-site, sitting
organizationally in *Business Development*, not Engineering). Each Delta pairs with an **Echo** —
a Deployment Strategist with domain background (ex-military, clinicians, forensic accountants) who
handles the customer's politics and adoption. FDEs ship working software in days, tolerate hacks,
and own *outcomes*; Product Development later abstracts the recurring field patterns into platform
primitives. That flywheel is how bespoke deployment work compounded into a platform business with
~80% gross margins instead of a consulting firm's ~32% — and it is the single most-copied org
pattern in AI right now (FDE job postings grew >800% Jan–Sep 2025; OpenAI, Anthropic, and 100+
YC startups run variants of it).

---

## Currency

- **Last reviewed:** 2026-10-06
- **Primary sources:** Palantir's own [Dev versus Delta](https://blog.palantir.com/dev-versus-delta-demystifying-engineering-roles-at-palantir-ad44c2a6e87) post and Nabeel Qureshi's [Reflections on Palantir](https://nabeelqu.co/reflections-on-palantir) (8 years as an FDE)
- Full annotated list: [05 · Sources](./05-sources/SOURCES.md)

## Contributing

Human-correctable like the other maps: open an issue or PR. Claims should trace to a listed source;
unsourced claims get labeled as inference.
