# Notes

This directory contains raw study notes taken while going through each module of the Axum course.

The goal of these notes is to capture understanding in progress, not perfection.

These files may include:

explanations of concepts

code snippets from the module

diagrams or flow explanations

questions or confusions

observations about how things work

Think of this folder as a developer lab notebook.

## File Naming Convention

Each module should have a dedicated notes file:

[module-01-intro.md](module-01-intro.md)
[module-02-routing.md](module-02-routing.md)
module-03-extractors.md
module-04-responses.md
module-05-state.md
module-06-middleware.md
module-07-errors.md
module-08-database.md
module-09-auth.md
module-10-advanced.md
module-11-testing.md
module-12-production.md

---

## Suggested Note Structure

- # Module X — Title

## What problem this module solves

Explain the motivation for the feature.

---

```
## Key Concepts

List the main concepts introduced.

Example:

- Router
- Route handlers
- HTTP methods
- Path parameters

---

## Important Code Patterns

Add the important patterns or examples from the module.

Example:

Router::new()
.route("/", get(handler))

---

## Request Flow (if relevant)

Explain how a request moves through the system.

Example:

Client → Router → Handler → Response

---

## Questions / Confusions

Things that are unclear or worth revisiting later.

---

## Observations

Interesting things noticed during the module.

Example:

- Handlers must be async functions
- Axum routing is composable
```

---

## Goal of This Folder

The goal is to understand the module deeply, not to create perfect documentation.

Messy thinking is allowed here.

The refined knowledge should go into the `lessons/` directory.

```

```
