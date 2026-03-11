# Docs

`docs/` contains process notes, editorial guidance, and working documents
for developing this repository.

This layer is not part of the core architecture
and not itself a project space.

It exists to document how the repository is shaped,
maintained, revised, and extended.

---

## Status of This Layer

The documentation layer does not define invariants.
It does not introduce new project logic.
It does not carry independent theoretical authority.

Its role is procedural and editorial.

`docs/` records:

- conventions of repository work
- redactional decisions
- structural open questions
- roadmap logic
- process assumptions for revision and extension

What appears here may guide work,
but it does not overrule the core
and does not substitute for project self-positioning.

---

## Relation to Core and Projects

`docs/` stands beside the architecture,
not above it.

This means:

- the **core** defines structural invariants
- **projects** define declared reductions and realizations
- **docs** records how both are being handled in practice

Documentation may summarize, restate, compare, or clarify,
but it should not silently redefine terms from the core
or impose project logic from outside the projects themselves.

If overlap occurs,
it should remain explicitly documentary rather than foundational.

---

## Purpose

This layer exists to:

- preserve editorial continuity
- make revision decisions traceable
- record unresolved structural questions
- support consistency across files and layers
- distinguish stable architecture from active development
- keep process knowledge from leaking into the core

Without such a layer,
temporary decisions tend to harden into implicit doctrine.

`docs/` therefore protects the repository
from confusing work-in-progress with architecture.

---

## Typical Contents

Typical documents in this layer may include:

- roadmap files
- editorial notes
- structural checklists
- naming conventions
- migration notes
- repository maintenance guidance
- comparison notes across projects
- records of unresolved tensions

These documents may be provisional,
time-bound,
or superseded later.

That provisional status is acceptable here.

---

## Allowed and Disallowed Functions

### Allowed

`docs/` may:

- explain how repository layers are currently understood
- record why a redactional change was made
- describe active work sequences
- note incompleteness and pending restructuring
- formulate guidance for maintaining consistency

### Not Allowed

`docs/` should not:

- redefine core terms
- declare architectural invariants
- establish project canon from outside a project
- replace a project README
- turn temporary process language into ontology

The documentation layer supports the work.
It must not become a hidden second core.

---

## On Overlap

This repository allows controlled overlap between layers,
especially where projects must remain readable on their own.

`docs/` may describe or summarize that policy,
but it does not create it.

The rule remains:

**documentation may restate; it may not found.**

Where terminology is repeated here,
its authority remains located elsewhere.

---

## Working Principle

Keep the distinction clear between:

- what the repository **is**
- what a project **does**
- how the repository is currently **being worked on**

`docs/` belongs to the third category.

Its proper tone is therefore neither doctrinal nor projective,
but clarifying, orienting, and procedural.

---

## Current Contents

This folder currently includes:

- `README.md`  
  A brief orientation to the status and function of the documentation layer.

- `ROADMAP.md`  
  A working document for sequencing, extension, revision, and unresolved development needs.

Further documents may be added
as the editorial and structural work of the repository becomes more explicit.

---

## Maintenance Heuristic

A document belongs in `docs/`
if it primarily answers questions such as:

- How are we currently organizing the work?
- Which redactional decisions have been made?
- What remains open?
- In what order should files or layers be revised?
- Which conventions help preserve consistency?

If a document instead answers:

- What is structurally true?
- What are the invariants?
- What is this specific project?

then it belongs elsewhere.

---

## Reminder

`docs/` is a support layer.

It should make the repository easier to understand and maintain,
without competing with the core
and without absorbing the project layer into process language.
