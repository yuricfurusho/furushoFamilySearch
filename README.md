# Codex-Assisted FamilySearch Workflows

This small repository is a living guide for learning and documenting effective ways to use Codex, its in-app browser, and local-computer tools for family-history work on [FamilySearch.org](https://www.familysearch.org/).

## Repository shape

For now, the tracked repository contains only `README.md` and `AGENTS.md`. It is not a session log, research archive, or software project. Reusable skills are the only planned exceptions, and they should be added only after a workflow proves useful and Yuri approves expanding the repository.

## Session baseline

At the start of every session, Codex opens or reuses FamilySearch in the in-app browser and leaves it visible for Yuri to authenticate manually. Codex does not handle credentials, authentication codes, cookies, or session data.

## Learning and reusable skills

After each substantive session, Codex evaluates what made the work faster, safer, or more accurate. Only validated, privacy-safe, reusable strategies belong here; case-specific findings and raw interaction logs do not.

When a reusable workflow repeatedly saves effort, prevents meaningful errors, and needs more than a short instruction, Codex will propose turning it into a local skill and sharing the same source here. `AGENTS.md` contains the full decision criteria and safety rules. Until Yuri approves a skill, the repository stays at two files.

## Validated navigation map

When a FamilySearch person ID is known, direct routes avoid repeated menu navigation:

- Person tabs use `/en/tree/person/{tab}/{person-id}`, where `{tab}` is `about`, `details`, `sources`, `collaborate`, `memories`, `timeline`, or `ordinances`.
- Tree views use `/en/tree/pedigree/{view}/{person-id}`, where `{view}` is `landscape`, `portrait`, `fanchart`, `descendancy`, or `first-ancestor`.
- A profile's **View Tree** link uses `/en/tree/pedigree/{person-id}` and recenters the last-selected tree view on that person.
- **Recents** can filter previously viewed people by name or person ID.

The Details tab groups vitals, other information, family members, other relationships, life history, research help, notes, changes, and tools. Edit dialogs commonly separate structured values from a **Reason This Information Is Correct** field. During read-only reconnaissance, inspect forms without typing and always leave through **Cancel** or **Close**, never **Save**.

FamilySearch is a changing website. Verify the destination heading and that menus or dialogs actually opened before taking the next action.

## Observed source-title convention

A status-prefixed source-title pattern has been observed across multiple related profiles:

`{STATUS} {EVENT TYPE} | {PERSON or PERSON A + PERSON B} | {PLACE} | {YYYY-MM-DD when known} | {PROVENANCE}`

- `🟢` means fully reviewed: every extractable detail has been evaluated and placed on the correct people and fields, with applicable attachments resolved.
- `🟡` means the title has been standardized and review has begun, but extraction, verification, cleanup, or attachment work remains.
- Observed event types include `NASCIMENTO`, `CASAMENTO`, `ÓBITO`, and `MEMORIA PESSOAL`.
- Marriage titles use `PERSON A + PERSON B`.
- The ISO date segment is optional when unknown. Its absence alone does not mean a source is unreviewed.
- Provenance is the final segment. Observed forms include `FS: Registro Civil` and `Informante: {PERSON}`.

Existing titles vary in spacing and may use a four-segment form without a date. For future authorized title changes, use one space after the emoji and around each `|`, include an ISO date only when the source supports it, and never infer review status from formatting alone.

The emoji is a workflow state, not a confidence label. Do not assign `🟡` without actually inspecting the source, and do not assign `🟢` merely because no warning or image is visible. When an image is unavailable through all authorized routes, a source may still become green only after all available indexed information, citations, people, relationships, facts, and attachments have been fully processed.

## Scope and long-term goal

This is not a mobile app or conventional software product. Android, Firebase, app distribution, and device-testing instructions do not apply. The long-term goal is a lightweight starting point for other people who want safe, effective Codex assistance with FamilySearch.

This independent project is not affiliated with or endorsed by FamilySearch.
