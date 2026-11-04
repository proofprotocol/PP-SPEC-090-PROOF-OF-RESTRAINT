# Overview

*Informative. [SPEC.md](../SPEC.md) controls.*

## The question

**Did the control avoid stopping legitimate work?**

Proof of Restraint is the claim that a control let legitimate work through: its False Block Rate over delivered good canaries, or, for a containment control, its False Arrest Rate, is within a limit declared in advance. It is computed from the good canaries of PP-SPEC-077 runs and the false arrests of PP-SPEC-078 runs. Proof of Efficacy is never published without the restraint result beside it.

## Why it matters

A control that blocks everything is not efficacious. It is broken in the other direction. A buyer, insurer or regulator relying on a proof of efficacy also needs this question answered, and answered by evidence the measured party did not produce.

## What it is not

- It is not Proof of Efficacy. Restraint says the control did not over-block; Efficacy says it stopped the bad.
- It is not a usability or performance claim. Latency and throughput under load are reported under PP-SPEC-079, not here.

## The three answers

- **proven:** The False Block Rate (or False Arrest Rate) is within the Restraint Limit over at least the declared minimum of delivered good canaries.
- **refuted:** The False Block Rate (or False Arrest Rate) exceeds the Restraint Limit.
- **insufficient:** Fewer delivered good canaries than the declared minimum, or the run was not valid.
