# ResearchOS Base44 Mirror Manifest

This directory is the verification boundary for the live ResearchOS application implemented in Base44.

- Base44 app: Blendr AI Research Suite / ResearchOS
- Base44 checkpoint: pending post-hardening checkpoint
- Mirror status: PARTIAL — CI boundary established; full source synchronization is not yet certified.
- Production rule: GitHub must not be described as the source mirror for live Base44 code until the mirrored source tree and checkpoint/commit mapping are updated and verified.

## Required verification before release

1. Base44 production build passes.
2. Reference orchestration accepts the exact manuscript version and persists provenance.
3. Journal Compliance Matrix uses deterministic passed / warning / blocked / unable_to_verify states.
4. Sentry runtime instrumentation is configured and a test event is observed.
5. Base44 checkpoint and GitHub mirror revision are recorded together.

This manifest intentionally fails closed in documentation: CI presence alone does not prove that the live Base44 source is mirrored.
