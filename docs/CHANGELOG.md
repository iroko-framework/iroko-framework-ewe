# Changelog

All notable changes to the Iroko Framework: Ewé Module vocabulary are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.2.0] - 2026-02-11

### Added

- Formal `skos:ConceptScheme` declaration for:
  - Access Level
  - Medicinal Use
  - Ritual Use
- Six Access Level concepts:
  - Public - Unrestricted
  - Public - No Amplification
  - Limited - Community Only
  - Limited - Initiated Only
  - Private - Practitioner Access
  - Restricted - No Access
- Four Medicinal Use concepts:
  - Digestive support
  - Respiratory support
  - Skin and topical use
  - General tonic / revitalizing
- Seven Ritual Use concepts:
  - Purification and Cleansing
  - Protection and Boundary Setting
  - Invocation and Communication
  - Healing and Restoration
  - Offering and Devotion
  - Rites of Transition
  - Cosmological or Symbolic Association
- Datatype properties:
  - `ritualContext`
  - `nameCollision`
  - `collisionNotes`
- Boolean modeling for `nameCollision`
- Structured mini-syntax specification for `ritualContext`
- Consistent GitHub Pages term documentation under `/docs/terms/`
- Machine-readable vocabulary published under `/docs/vocab/iroko-ewe-module.ttl`
- `owl:DatatypeProperty` and `owl:ObjectProperty` refinements
- Explicit `skos:definition` for all controlled terms

### Changed

- Reorganized repository for GitHub Pages deployment under `/docs`
- Standardized IRIs to match published term pages (removed inconsistent trailing slashes)
- Consolidated medicinal and ritual categories into SKOS concept schemes
- Refined `iroko:accessLevel` as an `owl:ObjectProperty` with `skos:Concept` range
- Clarified separation between:
  - `ritualUse` (controlled classification)
  - `ritualContext` (narrative literal, governed by accessLevel)
- Updated README to reflect v0.2.0 publication state
- Cleaned term documentation to separate structural vocabulary from design commentary

### Documentation

- Published stable vocabulary homepage
- Added term-level human-readable documentation
- Clarified governance model in README
- Added semantic version reference for citation

---

## [0.1.0] - 2026-01-20

### Added

- Initial vocabulary structure
- `iroko:Plant` class
- `iroko:accessLevel` property (minimal form)
- `iroko:ritualContext` property
- Basic ontology metadata
- Early documentation prototype

---

[0.2.0]: https://github.com/iroko-framework/iroko-ewe-module/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/iroko-framework/iroko-ewe-module/releases/tag/v0.1.0
