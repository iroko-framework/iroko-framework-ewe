# IROKO FRAMEWORK
## iroko: ewe

The **Iroko Framework: Ewé Module** models Afro-Atlantic ethnobotanical knowledge (ewé) using a stewardship-centered, post-custodial linked data approach. It preserves variation, ritual context, and ethical governance without flattening sacred or community-bound knowledge into extractive datasets.

- **Status:** Active development
- **Stable release:** v0.2.0
- **Scope:** Ethnobotanical concepts, naming variation, and governed ritual context
- **Audience:** Archivists, researchers, and collaborators exploring non-extractive knowledge modeling

This repository is a working module within the broader Iroko Framework and serves as a foundational demonstration rather than a comprehensive plant archive.

---

## Versioning

- **Current stable release:** v0.2.0
- **Development branch:** main
- **Changelog:** [CHANGELOG.md](../CHANGELOG.md)

Notes:
- v0.1.0 remains an early attempt and is retained for history.
- For citation and reproducibility, reference the tagged release.

---

## Namespace

This module publishes terms in two parallel forms:

- `vocab/` - machine-readable RDF files
- `terms/` - human-readable term documentation

---

## Machine-readable vocabulary

- [Turtle (RDF)](vocab/iroko-ewe-module.ttl)

---

## Core properties

- [accessLevel](/iroko-ewe-module/terms/accessLevel/)
- [medicinalUse](terms/medicinalUse/)
- [ritualUse](terms/ritualUse/)
- [ritualContext](terms/ritualContext.md)
- [nameCollision](terms/nameCollision.md)
- [collisionNotes](terms/collisionNotes.md)

---

## Access Level Scheme

- [Scheme definition](terms/accessLevel/index.md)

### Controlled values

- [Public - Unrestricted](terms/accessLevel/public-unrestricted.md)
- [Public - No Amplification](terms/accessLevel/public-no-amplification.md)
- [Limited - Community Only](terms/accessLevel/limited-community-only.md)
- [Limited - Initiated Only](terms/accessLevel/limited-initiated-only.md)
- [Private - Practitioner Access](terms/accessLevel/private-practitioner-access.md)
- [Restricted - No Access](terms/accessLevel/restricted-no-access.md)

---

## Medicinal Use Category Scheme

- [Scheme definition](terms/medicinalUse/index.md)

### Controlled values

- [Digestive Support](terms/medicinalUse/digestive-support.md)
- [Respiratory Support](terms/medicinalUse/respiratory-support.md)
- [Skin and Topical Use](terms/medicinalUse/skin-and-topical-use.md)
- [General Tonic / Revitalizing](terms/medicinalUse/general-tonic-revitalizing.md)

---

## Ritual Use Category Scheme

- [Scheme definition](terms/ritualUse/index.md)

### Controlled values

- [Purification and Cleansing](terms/ritualUse/purification-and-cleansing.md)
- [Protection and Boundary Setting](terms/ritualUse/protection-and-boundary-setting.md)
- [Invocation and Communication](terms/ritualUse/invocation-and-communication.md)
- [Healing and Restoration](terms/ritualUse/healing-and-restoration.md)
- [Offering and Devotion](terms/ritualUse/offering-and-devotion.md)
- [Rites of Transition](terms/ritualUse/rites-of-transition.md)
- [Cosmological or Symbolic Association](terms/ritualUse/cosmological-or-symbolic-association.md)

---

## How to Use This Module

- Browse term pages to understand how Ewé concepts are modeled.
- Use the Turtle vocabulary as a reference or template for related datasets.
- Cite the tagged release when referencing this work in publications or projects.

---

## Status

Stable vocabulary (v0.2.0). Active development continues.
