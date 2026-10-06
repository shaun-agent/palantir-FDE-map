# FDE vs Adjacent Roles — Don't Confuse the Job Titles

Every company has customer-facing technical people. The FDE is distinct on two axes:
**what they own** (outcomes, not deals or tickets) and **where their output goes**
(product feedback loop, not just the account).

| Role | Primary focus | Job ends when... | Writes production code? | Feeds product? |
|------|--------------|------------------|------------------------|----------------|
| **Sales Engineer** | Close the deal | Contract signed | Demos only | Rarely |
| **Solutions Architect** | Design the fit to the customer's environment | Design handed off | Sometimes | Occasionally |
| **Consultant / SI** | Deliver the statement of work | SOW delivered | Yes, but customer-owned & billable | No |
| **Customer Success** | Retention & satisfaction | Renewal secured | No | Tickets, not patterns |
| **Support Engineer** | Resolve incidents | Ticket closed | Patches | Bug reports |
| **FDE** | **Own the customer's outcome** | Outcome achieved, in daily use | **Yes — product-grade, on the platform** | **Structurally — it's half the point** |

## The two tests that separate an FDE org from the rest

1. **The outcome test.** If the person's success metric can be satisfied while the customer's
   problem remains unsolved (deal closed, SOW delivered, ticket resolved, renewal signed), it's
   not an FDE role.
2. **The flywheel test.** If what the person learns at the customer has no structural path back
   into the product ([productization flywheel](../01-core-concepts/productization-flywheel.md)),
   it's consulting with a better title — the exact critique leveled at the FDE hype
   ([KDnuggets: "AI's hottest new career, or consulting with a better title?"](https://www.kdnuggets.com/forward-deployed-engineer-ais-hottest-new-career-or-consulting-with-a-better-title)).

## Permanent role vs rotation

Two legitimate implementations:

- **Palantir-classic:** FDE is a *permanent career* (Deltas), organizationally in Business
  Development, paired with [Echoes](../01-core-concepts/delta-echo-pairing.md).
- **Rotation model (Project Frontline):** product engineers rotate through field deployments
  (250+ engineers at Palantir) with mentors, then return to product work transformed — users
  before builders. Cheaper to start, and vinoo.io argues it's the only way to *develop* FDEs,
  since you can't really hire them off the street.

Mixing them up causes failure: a rotation treated as a permanent org has no product path home;
a permanent FDE org without product rotation drifts toward consulting.
