# SOVRINT Digital Systems

**Author:** Katrina Pietroniro  
**Framework:** SOVRINT™  
**Status:** Public architecture index; implementation coverage varies by linked repository.

This repository is the top-level map of SOVRINT digital-system components, their dependencies, evidence paths, and operational boundaries. It is an architecture index, not a claim that every listed subsystem is deployed or connected.

## Runtime reference flow

The current runtime topology defines:

INGRESS → OBSERVE → MEASURE → VERIFY → CLASSIFY → GOVERN → CORRECT → RECORD → EMIT → VALIDATE → VISUALIZE → PRESERVE

The flow is a reference architecture. Each system record must name the implementation, version, owner, dependencies, failure and recovery modes, telemetry, governance boundary, and canonical status.

## Public component repositories

- SOVRINT Core — canonical registries and rights control (private): https://github.com/SOVRINT-OG/sovrint-core
- SOVRINT Publications — publication lineage and release records: https://github.com/SOVRINT-OG/sovrint-publications
- Runtime Visual Atlas — visual artifacts and reproducible synthetic charts: https://github.com/SOVRINT-OG/runtime-visual-atlas
- Research Validation Layer — synthetic fixtures and bounded validation runtime: https://github.com/SOVRINT-OG/sovrint-research-validation-layer
- Ontological Computation — public formalism: https://github.com/SOVRINT-OG/sovrint-ontological-computation
- Emotional Physics — public research formalism: https://github.com/SOVRINT-OG/sovrint-emotional-physics

## Evidence boundary

Separate observed, synthetic, simulated, and empirical evidence. A documented component is not proof of a deployed runtime; a test result is limited to its declared fixtures and conditions. Cite the source repository and version when using these materials.


## Research status and evidence

See [RESEARCH_STATUS.yaml](./RESEARCH_STATUS.yaml) for the version, release, DOI, evidence class, validation state, source-register guidance, and rights metadata. Update that record when those facts change. Cite sources beside claims that depend on them; citation alone does not grant reuse permission.
