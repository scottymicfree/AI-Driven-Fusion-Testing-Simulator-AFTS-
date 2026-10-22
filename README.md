# AFTS - AI-Driven Fusion Testing Simulator

> 🌐 **Fenton Lab official website:** [fentonlabai.pages.dev](https://fentonlabai.pages.dev/)  
> Planned primary domain: `fentonlabai.com` (custom-domain connection pending).

## Open Architecture Specification

AFTS is an open, implementation-neutral architecture for site-aware, AI-assisted multiphysics simulation of fusion and hybrid acoustic-plasma systems. This repository publishes the concept, architecture, scientific responsibilities, interoperability contracts, validation approach, and implementation guidance. It contains no canonical software implementation and does not require any particular platform, programming language, solver, AI model, interface, vendor, or cloud service.

**Release:** 1.0.0 Public Architecture Edition  
**Status:** Open architecture publication  
**Primary artifact:** `AFTS_Open_Architecture_Specification_v1.0.0.pdf`

## Purpose

Scientific progress depends on the ability to test ideas safely, repeatedly, transparently, and across independent implementations. AFTS provides a common architecture for constructing digital twins and hardware-in-the-loop environments that account for local rotating-frame effects, coupled plasma-acoustic dynamics, uncertainty, provenance, and the disciplined use of AI.

AFTS does not claim that fusion has been achieved, that terrestrial frame effects dominate a particular apparatus, or that AI can replace validated physics. It defines how such questions can be tested rigorously.

## Repository contents

- `specification/` - canonical Markdown specification and focused chapters
- `contracts/` - implementation-neutral interface and data contracts
- `profiles/` - optional capability profiles
- `validation/` - benchmark and conformance guidance
- `examples/` - example manifests and workflows
- `diagrams/` - portable architecture diagrams
- `publications/` - public summary and white-paper materials
- `lucy/` - non-normative note describing Lucy Fusion Testing Studio as one possible implementation

## Foundational principle

> Standalone by design. Platform-neutral by specification. Better through integration.

Any person or organization may implement AFTS inside its own product, interface, laboratory environment, research workflow, or educational system.

## Quick start

1. Read `publications/EXECUTIVE_SUMMARY.md`.
2. Read `specification/AFTS_SPECIFICATION.md`.
3. Select a capability profile from `profiles/`.
4. Use the contracts in `contracts/` to define an implementation.
5. Validate the implementation using `validation/`.

## Licensing

Documentation is released under Creative Commons Attribution 4.0 International. Machine-readable schemas and examples are released under Apache License 2.0. See `LICENSE`.

## Scientific integrity

Every implementation should expose assumptions, coordinate frames, units, solver versions, numerical tolerances, uncertainty, validation status, and provenance. Visualizations and AI recommendations must not fabricate, hide, or overwrite authoritative scientific values.
