# Dev vs Delta — The Two-Pronged Engineering Org

> Source: Palantir's own [Dev versus Delta](https://blog.palantir.com/dev-versus-delta-demystifying-engineering-roles-at-palantir-ad44c2a6e87)
> post, corroborated by [Reflections on Palantir](https://nabeelqu.co/reflections-on-palantir).

The load-bearing sentence from Palantir's post:

> **A Dev builds one capability for many customers. A Delta enables many capabilities for one customer.**

| | **Dev** (Software Engineer) | **Delta** (Forward Deployed Software Engineer) |
|---|---|---|
| Builds | The platforms: Foundry, Gotham, AIP | Customer-specific solutions *on* those platforms |
| Optimizes for | Generality, architecture, long-horizon reliability | Speed to outcome for one customer |
| Sits in | Product Development | **Business Development** |
| Technical debt | Pays it down | Deliberately tolerates it ("hacky workarounds" are a feature) |
| Success metric | Platform capability shipped | Customer outcome achieved |
| Time horizon | Quarters/years | Days/weeks |

## The non-obvious part: Deltas sit in Business Development

This is the detail most imitators miss. Palantir's FDEs are organizationally part of BD, with a
mandate to "achieve technical outcomes for our customers." Deployment *is* the go-to-market.
There is no separate sales-then-implementation handoff; the people who make the product work at
the customer are the same people who expand the account. AIP bootcamps (3–5 day engagements run
by FDE teams) converting into seven-figure contracts is this principle operationalized.

## Why two prongs instead of one

The split resolves the eternal startup tension between "move fast and break things" and "build
sustainable infrastructure" by giving each side to a different org:

- **FDEs** move fast, embed, hack, and capture context that never survives a requirements doc.
- **Devs** watch what FDEs keep rebuilding across customers and abstract it into platform
  primitives (the [productization flywheel](./productization-flywheel.md)).

One prong without the other fails predictably: FDEs alone → a consulting firm
([the consulting trap](../02-mental-models/the-consulting-trap.md)); Devs alone → a beautiful
platform nobody adopts (enterprise shelfware).

## Flat titles

Culturally, nearly everyone at Palantir held the same title — "forward deployed engineer" — with
only a handful of Directors plus the CEO above that (a deliberately Girardian anti-mimetic design
per Thiel). It prevented title politics and let low-status engineers build critical infrastructure
without permission, at the cost of what Qureshi calls the "hero–shithead rollercoaster" and
chronically unclear strategy.

## Further reading

- [Delta–Echo pairing](./delta-echo-pairing.md) — the other half of the field unit
- [Productization flywheel](./productization-flywheel.md) — how Delta hacks become Dev platforms
