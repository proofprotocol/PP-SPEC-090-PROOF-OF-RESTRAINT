# Conformance Checklist

*Informative summary of the MUST requirements in [SPEC.md](../SPEC.md). A declaration, determination or record that fails any item is non-conforming.*

## Question (SPEC 3)
- [ ] Presented only as the answer to: Did the control avoid stopping legitimate work?
- [ ] Never described as verification, validation, attestation, assurance or testing

## Claim Declaration (SPEC 4)
- [ ] Registered and anchored before any evidence measured against its limits is produced; referenced records registered before it
- [ ] Subject, Declarant and interest, funding tier, Sponsor, validity period
- [ ] Declares: The Restraint Limit
- [ ] Declares: The minimum number of delivered good canaries
- [ ] Declares: The good canary colors and work types in scope
- [ ] Limits unchanged after registration
- [ ] Publication commitment

## Evidence (SPEC 5)
- [ ] Basis: PP-SPEC-077 good canary outcomes
- [ ] Basis: PP-SPEC-077 False Block Rate
- [ ] Basis: PP-SPEC-078 False Arrest Rate
- [ ] Every basis record Conformant and Registered
- [ ] No measured-party logs, consoles, alerts, receipts or reports used

## Determination (SPEC 6)
- [ ] Exactly one of `proven`, `refuted`, `insufficient`
- [ ] `refuted` takes precedence over `insufficient`
- [ ] Computed from the declaration and basis records alone
- [ ] `insufficient` never presented as a result

## Scope and expiry (SPEC 7)
- [ ] Scope stated exactly as declared
- [ ] Expired on period end, DUT Fingerprint change, or basis Revocation

## Independence (SPEC 8, 10)
- [ ] Resolver is not the Provider and not in any basis Party Set

## Records (SPEC 9)
- [ ] Record IDs use the `PORS-1:record` tag
- [ ] Every Determination registered, including `refuted` and `insufficient`
- [ ] Public whenever basis results are public
