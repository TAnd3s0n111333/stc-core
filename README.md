# STC Core

**Standard Template Construct — Core Definitions and Standards**

## Overview

`stc-core` defines the **foundational architecture, interfaces, and standards** of the Standard Template Construct (STC).  
It formalises how engineering knowledge, modules, environments, and planning concepts are represented across the STC ecosystem.

This repository acts as the **reference standard** for all other STC components.

## Scope

This repository contains:
- Core architectural definitions
- Module interface standards
- Knowledge representation schemas
- Planning and constraint abstractions
- Versioning and development rules

This repository deliberately avoids implementation-heavy code.

## What This Repository Is Not

- A simulation engine  
- A robotics control stack  
- A machine learning training repository  
- A finished product  

Implementations live in downstream repositories.

## Repository Structure

- stc-core/
  - docs/ # Architectural and conceptual documentation
  - schemas/ # Formal schemas (JSON/YAML) for STC entities
  - standards/ # Naming, versioning, and interface rules
- README.md

## Relationship to the STC

`stc-core` defines the **contract** that all STC subsystems adhere to.  
Simulation, planning, robotics, and analysis tools must conform to these definitions to be considered STC-compatible.

## Status

**Phase 1 — Foundations**  
Active development. Interfaces are evolving and subject to change.

## Versioning

Semantic versioning is used:
- `v0.x` — evolving standards
- `v1.0` — stable STC core specification

## License

Apache License 2.0

## Author

Toby Anderson  
Robotics & Mechatronics Engineering (AI) — Monash University
