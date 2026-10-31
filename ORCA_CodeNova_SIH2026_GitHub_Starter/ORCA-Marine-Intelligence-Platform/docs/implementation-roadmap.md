# ORCA implementation roadmap

> **Status: Planned.** This roadmap is a proposed sequence, not a report of completed software work.

## Phase 1 — Validate the problem and data

- Select one coastal pilot area and one priority user workflow.
- Confirm authoritative products, access conditions, licensing and update frequency.
- Define location/time inputs and a common evidence schema.

## Phase 2 — Build a vertical slice

- Implement a basic chat or API entry point.
- Implement a planner and two or three real, documented data tools.
- Return source-attributed results with timestamps and missing-data indicators.

## Phase 3 — Add geospatial reasoning

- Normalize coordinate systems and units.
- Add spatial filtering and a map view.
- Test distance calculations, boundaries and time-window alignment.

## Phase 4 — Add explainable assessment

- Agree on authoritative thresholds and advisory precedence with domain experts.
- Implement deterministic, versioned rules.
- Test stale, conflicting, missing and extreme input cases.

## Phase 5 — Demonstrate and expand

- Prepare reproducible demo queries and clearly labelled data snapshots.
- Add more agents and datasets only after the first workflow is reliable.
- Evaluate regional-language responses, geofencing and route planning separately.

## First-demo acceptance criteria

- A user query triggers a visible plan and tool-execution trace.
- At least two real, documented sources contribute to the result.
- Every displayed value has a source and timestamp.
- Missing or stale data is clearly identified.
- The explanation matches the evidence and does not claim official certification.
