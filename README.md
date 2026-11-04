# Proof of Restraint

> **Ownership and Attribution Notice**
>
> Proof of Restraint (PP-SPEC-090) is authored by **Craig Thomas Ellrod** and is published as part of **Proof Protocol**. Copyright (c) 2026 Craig Thomas Ellrod.
>
> Any use, implementation, derivative, citation, or incorporation of this specification, in whole or in part, MUST attribute **Craig Thomas Ellrod and Proof Protocol**. This requirement applies to standards bodies, working groups, consortia, and commercial implementations.
>
> Licensed under the Proof Protocol License 1.1 (see LICENSE.md); text CC BY 4.0 under Part A, which grants no patent rights. Original inventor: Craig Thomas Ellrod (ORCID 0009-0004-1058-7666).
>
> **Patents.** Patent terms are in [PATENT-SCHEDULE.md](PATENT-SCHEDULE.md). Claims not listed there are reserved by Craig Thomas Ellrod. Licensing: 1proofprotocol@gmail.com.

---

**Did the control avoid stopping legitimate work?**

*A control that blocks everything is not efficacious. It is broken in the other direction.*

Proof of Restraint is the claim that a control let legitimate work through: its False Block Rate over delivered good canaries, or, for a containment control, its False Arrest Rate, is within a limit declared in advance. It is computed from the good canaries of PP-SPEC-077 runs and the false arrests of PP-SPEC-078 runs. Proof of Efficacy is never published without the restraint result beside it.

## How it works

1. **Declare first.** The claim, its subject, scope and limits are registered and anchored before the evidence they are measured against is produced.
2. **Evidence from the family.** The claim is determined only from Conformant, registered Proof Protocol records:
- **PP-SPEC-077 good canary outcomes**
- **PP-SPEC-077 False Block Rate**
- **PP-SPEC-078 False Arrest Rate**
3. **Determine mechanically.** Exactly one of `proven`, `refuted` or `insufficient`, computed the same way by a person and a machine.
4. **Publish everything.** Every Determination is registered, whatever its result.
5. **Expire honestly.** A changed control, a revoked basis record, or the end of the declared period ends the claim.

## Part of the Proof of X family

Only Proof of Efficacy answers whether a control worked. Proof of Restraint answers one other question a reader needs answered. See SPEC.md Section 11 for the whole family, PP-SPEC-082, PP-SPEC-089 to PP-SPEC-099 and PP-SPEC-101.

## Repository

| Path | Contents |
|---|---|
| [SPEC.md](SPEC.md) | The normative specification, PP-SPEC-090 |
| [docs/overview.md](docs/overview.md) | Plain-English walkthrough |
| [docs/glossary.md](docs/glossary.md) | Terms |
| [docs/conformance.md](docs/conformance.md) | Conformance checklist |
| [schemas/restraint-claim.schema.json](schemas/restraint-claim.schema.json) | Claim Declaration and Claim Record schemas |
| [schemas/ai-disclosure.schema.json](schemas/ai-disclosure.schema.json) | Authorship Disclosure schema (077 21.15) |
| [CHANGELOG.md](CHANGELOG.md) | Version history |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to engage |
| [GOVERNANCE.md](GOVERNANCE.md) | How this specification is governed |
| [NOTICE.md](NOTICE.md) | Attribution requirements |
| [AI_DISCLOSURE.md](AI_DISCLOSURE.md) | What was human-authored and what was AI-drafted |
| [FUNDING.md](FUNDING.md) | Funding disclosure |
| [REVIEWERS.md](REVIEWERS.md) | Review disclosure |
| [ACKNOWLEDGEMENTS.md](ACKNOWLEDGEMENTS.md) | Credits |
| [ETHICS.md](ETHICS.md) | Proof Economy Code of Ethics |
| [CITATION.cff](CITATION.cff) | Citation metadata |
| [SECURITY.md](SECURITY.md) | Reporting protocol flaws |
| [PATENT-SCHEDULE.md](PATENT-SCHEDULE.md) | Patent terms |
| [LICENSE.md](LICENSE.md) | License terms |
| [LICENSE-CC-BY-4.0.md](LICENSE-CC-BY-4.0.md) | CC BY 4.0, specification text |
| [LICENSE-APACHE-2.0.md](LICENSE-APACHE-2.0.md) | Apache License 2.0, reference text |

## Status

Draft, version 0.1.0, 2026-11-04. Maintained by Craig Thomas Ellrod as part of Proof Protocol.

Builds on PP-SPEC-077 (Dead Canary), PP-SPEC-078 (Jailed Canary). Records are registered to a [PP-SPEC-004](https://github.com/proofprotocol/registry-api-spec) registry; the public instance is [proofregister.com](https://proofregister.com).

Glossary: [Proof of Restraint](https://proofeconomy.com/glossary/proof-of-restraint/). Specifications: [proofprotocol.io](https://proofprotocol.io/).

Archived on Zenodo: pending.

Related: Proof Economy Prior Art Declaration, DOI [10.5281/zenodo.21379780](https://doi.org/10.5281/zenodo.21379780).

## Cite

```
Ellrod, C. (2026). Proof of Restraint (PP-SPEC-090), v0.1.0.
Craig Thomas Ellrod, Proof Protocol. https://github.com/proofprotocol/PP-SPEC-090-PROOF-OF-RESTRAINT
```
