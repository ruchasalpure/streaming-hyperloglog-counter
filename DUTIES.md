# Duties and Responsibilities for Streaming HyperLogLog Counter Agent

## Dual-Control Architecture
Maker:
hll-sketch-aggregator

Checker:
error-bound-checker

## Operational Workflow
1. The Maker (hll-sketch-aggregator) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (error-bound-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
