# Ritual Context

**IRI:**  
https://iroko-framework.github.io/iroko-ewe-module/terms/ritualContext

**Type:**  
owl:DatatypeProperty

**Preferred label:**  
Ritual context

---

## Definition

High-level narrative description of ritual or symbolic context associated with a plant record.

---

## Scope note

This field captures structured, non-operational contextual description. Procedural instructions, recipes, and step-by-step ritual methods are intentionally excluded. Disclosure of this field is governed by `accessLevel`.

---

## Expected syntax

Values should follow a controlled mini-syntax using key–value pairs separated by pipes (`|`).

---

## Expected keys

- `purpose:` (recommended)
- `timing:` (optional)
- `context:` (optional)
- `parts:` (optional)

Each key should appear at most once per value string.

---

## Example

`purpose: fertility | parts: whole tree, roots`

---

## Version

Introduced in v0.2.0

---

← [Back to vocabulary index](/iroko-ewe-module/)
