# Iroko Framework: Ewé

This module demonstrates how the Iroko Framework models Afro-Atlantic ethnobotanical knowledge (ewé) using a stewardship-centered, post-custodial linked data approach. It is designed to preserve variation, ritual context, and ethical constraints without flattening sacred or community-bound knowledge into extractive datasets.

- Status: Active development
- Stable release: v0.1.0
- Scope: Ethnobotanical concepts, naming variation, and ritual context
- Audience: Archivists, researchers, and collaborators exploring non-extractive knowledge modeling

This repository is a working module within the broader Iroko Framework and is intended as a foundational demonstration rather than a comprehensive plant archive.

---

**Versioning**

- **Current stable release:** v0.1.0  
- **Development branch:** `main`  
- **Archived snapshot:** `archive/v0.1.0`  
- **Changelog:** [CHANGELOG.md](CHANGELOG.md)

For citation and reproducibility, always reference the tagged release.


## Version History

### Version 0.2.0 (January 27, 2026)

**Major Release - Production Ready**

**Added:**
- 10 new properties for multilingual naming support
- Controlled vocabularies for Access Levels (6), Ritual Uses (7), Medicinal Uses (4)
- `hasNameCollision` and `collisionNote` properties
- `primarySource` and `supplementalSource` properties
- Full `skos:definition` for all terms
- External vocabulary alignments (Darwin Core, SKOS, Dublin Core)

**Improved:**
- Complete documentation with scope notes
- CARE Principles compliance declared
- Examples and use cases added

**Download:** [ewe-v0.2.0.ttl](https://github.com/iroko-framework/iroko-framework-ewe/releases/tag/v0.2.0)

---

### Version 0.1.0 (January 20, 2026)

**Initial Release**

**Included:**
- Basic class: `iroko:Plant`
- Core properties: `accessLevel`, `ritualContext`
- Minimal documentation

**Download:** [ewe-v0.1.0.ttl](https://github.com/iroko-framework/iroko-framework-ewe/releases/tag/v0.1.0)
