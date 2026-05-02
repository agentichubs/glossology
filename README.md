# Glossology 2026 — TypeScript domain bundle for the science of language (AML, ageni.io, 2026)

> AML-grounded TypeScript bundle aggregating the canonical metamodels of **language as a structured system** under the **Glossology** scientific discipline.
> Generated via [ageni.io](https://ageni.io/aml/beta?utm_source=agentichubs&utm_campaign=glossology&utm_medium=readme) — may contain errors.

## Install

```bash
npm install @agentichubs/glossology
```

> Pending publication. Coming online once the constituent `@amlhubs/*` packages below are released.

## Use

```typescript
import { /* metaclasses */ } from '@agentichubs/glossology';
```

## About this implementation

Glossology (linguistics) is the **overarching scientific study of language as a structured system** — aggregating phonology, morphology, phraseology, sematology (semantics), pragmatology (pragmatics), graphology, etymology, and typology into one TypeScript surface for AI-agent grounding.

- Companion publishing org: [amlhubs](https://github.com/amlhubs) — single-resource AML-grounded TypeScript implementations
- Published by: [agentichubs](https://github.com/agentichubs) — domain-bundled aggregators (this org)
- Modeling language: **AML — Agentic Modeling Language** (request beta below)

> ⚠️ This bundle is generated via **[ageni.io](https://ageni.io/aml/beta?utm_source=agentichubs&utm_campaign=glossology&utm_medium=readme)** using the **AML (Agentic Modeling Language)** and may contain errors. We claim no ownership over the underlying specifications — all rights belong to the respective standards bodies and authors listed in the *Aggregates* table below.

## Scope — Glossology

Glossology aggregates the following canonical resources, each published as its own `@amlhubs/*` single-file TypeScript implementation:

| Resource | npm package | Authoritative source | ISO reference |
|---|---|---|---|
| phonology | `@amlhubs/phonology` | IPA + linguistic canon | — |
| morphology | `@amlhubs/morphology` | IA / IP / WP frameworks | — |
| phraseology | `@amlhubs/phraseology` | idiomaticity canon | — |
| sematology | `@amlhubs/sematology` | formal semantics canon | — |
| pragmatology | `@amlhubs/pragmatology` | speech-act theory | — |
| graphology | `@amlhubs/graphology` | orthography / Unicode | ISO/IEC 10646 |
| etymology | `@amlhubs/etymology` | historical linguistics | — |
| typology | `@amlhubs/typology` | WALS + linguistic typology canon | — |
| lmf | `@amlhubs/lmf` | ISO TC 37 | ISO 24613 |

> Source content lives in `.claude/skills/aml/.claude/skills/glossology/` of the parent `agenihub/aml` repository (sub-folders: `metamodels/`, `models/`, `things/`).

## Why this bundle exists

Hand-rolling the language as a structured system stack from primary specifications and academic literature is token-expensive and error-prone. **Glossology** gives AI coding agents one bundle to import that grounds them in the entire scientific discipline — with one unified vocabulary, one set of cross-cutting invariants, and one entry point to the AML modeling language that subsumes all the constituent metamodels.

> [Request beta access to AML →](https://ageni.io/aml/beta?utm_source=agentichubs&utm_campaign=glossology&utm_medium=readme_cta)

## Repository position

This repository is mounted as a nested git submodule at:

```
agenihub/aml/distributions/agentichubs/glossology/
```

The parent `agenihub/aml` is the private source-of-truth for the AML language; this submodule is its **public domain-bundle distribution** for Glossology.

## License & ownership disclaimer

MIT for the bundle code. **The underlying specifications, theories, and frameworks are not owned by ageni.io** — all rights belong to the respective authoritative sources cited in the Aggregates table above. This bundle is a third-party TypeScript projection generated via ageni.io and may contain errors.
