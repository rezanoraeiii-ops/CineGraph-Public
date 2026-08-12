# CineGraph — Human-AI Collaboration Protocol v0.1

## Purpose

Define the minimum operating protocol for humans and AI collaborators working on CineGraph without duplicated work, loss of context, or undocumented decisions.

## 1. Enter through shared context

A new AI collaborator should first read the public onboarding material and the available foundational documentation before proposing major work.

The sequence is:

`Onboarding → Collaboration Protocol → Specification → Task → Work`

## 2. Do not invent missing context

When information is unavailable, the collaborator must say that context is incomplete and request or seek the missing source. Missing facts must not be silently reconstructed from general knowledge.

## 3. Inspect before acting

Before starting a task, check whether the requested work already exists, whether a related decision has already been made, and whether another collaborator may already be working on the same problem.

The rule is:

`inspect → verify → propose → implement`

## 4. Work from an explicit task

Work should be attached to a clearly defined objective or task with an expected deliverable and constraints.

The collaborator should avoid broad unsupervised changes that are not tied to a project objective.

## 5. Preserve decisions

Important architectural, epistemological, organizational, or technical decisions should become durable Decision Records in the private CineGraph core.

A decision record should preserve at least:

- what was decided
- why it was decided
- alternatives considered
- consequences and risks
- related sessions and artifacts

## 6. Preserve meaningful work sessions

Significant research or development sessions should produce a Session Log in the private core. Session time is the authoritative timestamp for the intellectual work; Git commit time is the technical repository timestamp.

Session logging should be generated or assisted by AI whenever practical. Manual project-director data entry should be minimized.

## 7. Handoffs

When work is handed from one collaborator to another, the outgoing collaborator should leave a durable handoff containing:

- current state
- work completed
- evidence or sources
- unresolved questions
- next actions
- relevant artifacts or commits

## 8. Verification

AI-generated work should be reviewed according to its risk and importance. High-impact architecture, ontology, factual claims, and public-facing outputs should receive explicit verification before acceptance.

## 9. Repository hygiene

Do not expose private project material, personal information, credentials, secrets, or internal-only research in the public mirror.

The public mirror is an AI-facing context layer, not the private source of truth.

## 10. Human authority

The project director retains final authority over project direction, acceptance of major decisions, and release of work into the public project surface.

AI collaborators may research, analyze, critique, draft, prototype, and implement within their assigned scope, but should not silently override binding project decisions.

## 11. Avoid bureaucracy

Documentation exists to preserve useful project memory, not to create paperwork. Trivial work does not require elaborate records. Significant decisions and meaningful work should be durable and discoverable.

## 12. Completion

A task is considered complete when its required deliverable is produced, verified to the level appropriate for that task, and its resulting artifacts or decisions are recorded in the appropriate project location.
