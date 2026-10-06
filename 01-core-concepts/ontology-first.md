# Ontology-First — Data Integration Is the Hidden Foundation

The FDE model's dirty secret: most of the work is not AI, not analytics, not apps.
It is **getting the customer's data into a usable shape** — and modeling the customer's world
before building anything on top of it.

## What FDEs actually find on site

Enterprise data lives scattered across incompatible formats — PDFs, Excel files, notebooks,
legacy databases — and is gatekept by territorial teams. The first weeks of every deployment are
spent going to *where the data is*, integrating it, and building the **ontology**: a model of the
customer's actual entities (parts, work orders, patients, aircraft, accounts) and the relationships
between them.

The ontology is the contract between the messy world and the software. Once it exists, every
subsequent application — dashboard, scheduler, AI agent — is built against stable, named concepts
instead of against whatever a CSV happened to be called.

## From repeated pain to platform

FDEs rebuilt data-integration plumbing at customer after customer until Product Development
abstracted the pattern into **Foundry**:

| Recurring field pain | Foundry primitive |
|---|---|
| Ingesting scattered, incompatible sources | **Magritte** (data ingestion) |
| Analysts needing to explore integrated data | **Contour** (visualization/analysis) |
| Every customer needing bespoke apps on the same data | **Workshop** (app builder) |
| Every deployment re-modeling the domain | **Ontology** as a first-class platform object |

This is the [productization flywheel](./productization-flywheel.md) applied to the least glamorous
layer — and it's where most of the compounding value lived.

## The AI-era version

The playbook the AI labs copied keeps this step intact: **build customer-specific ontologies
first — domain modeling precedes any LLM deployment.** An agent pointed at unmodeled enterprise
chaos demos well and fails in production; an agent operating over a curated ontology inherits a
decade of deployment lessons. Palantir's AIP is explicitly "LLMs over the ontology."

## The lesson for anyone copying the model

Budget the unglamorous majority. If your FDE engagement plan assumes data is ready, the plan is
fiction. The FDE's first shipped artifact (week one) is usually a *data transform*, not a feature —
because that's the real critical path.

## Further reading

- [Productization flywheel](./productization-flywheel.md)
- [Engagement lifecycle](../02-mental-models/engagement-lifecycle.md)
