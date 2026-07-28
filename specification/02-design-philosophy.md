# Design Philosophy

AFTS is founded on engineering and scientific principles that guide architectural decisions without prescribing a specific implementation.

## Physics before AI
AI assists computation, control, search, anomaly detection, and explanation. It does not replace authoritative physical models or silently override solver outputs.

## Scientific integrity
Results remain traceable to assumptions, equations, numerical methods, inputs, and validation evidence. Presentation layers must not fabricate or obscure scientific values.

## Reproducibility by default
A run should be replayable from its experiment definition, site definition, model and solver identities, tolerances, seeds, environment, and provenance record.

## Site awareness
When the modeled sensitivity warrants it, geographic coordinates, local reference frames, effective gravity, Earth rotation, timing, magnetic context, and site uncertainty are explicit inputs rather than hidden constants.

## Open architecture
AFTS defines responsibilities and contracts, not a required programming language, user interface, operating system, vendor, cloud platform, AI model, or numerical package.

## Modular composition
Physics engines, controllers, AI models, data stores, visualization systems, and hardware adapters communicate through explicit contracts and may be independently replaced.

## Explainable intelligence
AI output should include its basis, applicability domain, uncertainty, and limitations whenever those can materially affect interpretation or control.

## Verification before optimization
Speed, visual quality, and automation do not take precedence over numerical correctness, calibration, uncertainty, and benchmark performance.

## Human authority
Qualified humans retain responsibility for scientific conclusions, publication, safety decisions, and operation of connected physical equipment.

## Long-term preservation
Published experiments and architecture releases should remain readable, versioned, exportable, and understandable after current tools become obsolete.

## Universal accessibility
The architecture is intended to be implementable by universities, laboratories, industry, educators, students, public-interest organizations, and independent developers.

## Continuous evolution
AFTS evolves through evidence, review, implementation experience, and documented change while preserving clarity and compatibility wherever practical.
