# Copilot Instructions for `SecuredxWave-internship`

## Build, test, and lint commands

This repository currently has **no configured build system, test suite, or linter** (no `package.json`, `pyproject.toml`, `Makefile`, or similar manifests are present).

- **Build:** N/A
- **Lint:** N/A
- **Test (full suite):** N/A
- **Test (single test):** N/A

When adding automation later, prefer documenting concrete commands here in the same format.

## High-level architecture

This is an internship artifact repository organized by training timeline, not an application codebase:

- `week-01/day-*` folders contain day-wise deliverables and learning artifacts.
- Content is primarily binary assets/documents (`.docx`, `.pdf`, `.png`, `.pcapng`) rather than source code.
- A recurring structure appears across days:
  - `assets/` for media/screenshots
  - task/topic subfolders for source exercise materials
  - `report/` for day summary documents

Copilot should treat the repository as a documentation/evidence archive unless the user explicitly introduces code files.

## Key conventions in this repository

- **Chronological organization:** place new work under the appropriate `week-*/day-*` path.
- **Day-scoped deliverables:** keep supporting assets and reports grouped inside the same day folder.
- **Binary-first content:** most tracked files are non-text; avoid assumptions about code tooling, dependency managers, or runnable targets.
- **Preserve source artifacts:** when restructuring, keep original lab/task materials discoverable within the relevant day folder.
