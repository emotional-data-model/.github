# Emotional Data Model

**Open standard for emotional context in AI.**

EDM defines what mattered — not just what happened.
A governance-first schema for representing emotional context
in AI systems. Portable, non-inferential, compliance-ready.

## The Standard

96 fields across 10 domains. Three implementation profiles:

| Profile | Domains | Fields | Use case |
|---|---|---|---|
| Essential | 5 | 24 | Lightweight capture |
| Extended | 8 | 50 | Narrative depth |
| Full | 10 | 96 | Complete governance |

## Repos

| | |
|---|---|
| [edm-spec](https://github.com/emotional-data-model/edm-spec) | Schema, docs, validation — MIT |
| [ddna-tools](https://github.com/emotional-data-model/ddna-tools) | Sealing and verification — MIT |

## Quick Start

```bash
# Validate an artifact
ajv validate -s schema/edm.v0.7.full.schema.json -d artifact.json
```

## Whitepaper

[EDM v0.7.0 on Zenodo](https://doi.org/10.5281/zenodo.19211903)

## Commercial Implementation

[deepadata.com](https://deepadata.com) — extraction API,
significance routing, VitaPass governance.

---

*Maintained by [DeepaData](https://deepadata.com)*
