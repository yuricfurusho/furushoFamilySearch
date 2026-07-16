# Codex-Assisted FamilySearch Workflows

A lightweight, public guide to using Codex, its in-app browser, and local-computer tools for careful family-history work on [FamilySearch.org](https://www.familysearch.org/).

## Scope and safety

- The repository tracks only `README.md` and `AGENTS.md`. It is not an application, research archive, or session log.
- Never store private genealogy, living-person data, screenshots, exports, credentials, cookies, or authentication artifacts here.
- Each session starts by reusing or opening FamilySearch and leaving it visible for Yuri to authenticate. Codex never handles credentials or authentication codes.
- Exploration is read-only by default. Any FamilySearch modification requires explicit approval.

## Efficient browser workflow

- Known person: `/en/tree/person/{tab}/{person-id}`, where `{tab}` includes `details`, `sources`, `memories`, `timeline`, and related profile tabs.
- Known tree focus: `/en/tree/pedigree/{view}/{person-id}`. **View Tree** re-centers the last tree view.
- Unknown person: use **Recents** to identify the correct profile and branch before following relationships.
- Source review progresses from **Sources list → source card → indexed record → Source Linker → accessible image or authorized external record**. Stop wherever evidence or permission ends.
- FamilySearch loads dynamically. Wait for real content, then verify the person, heading, destination, and opened dialog before continuing. Leave reconnaissance forms through **Cancel** or **Close**, never **Save**.

## Source-title convention

- Compact: `{STATUS} {EVENT} | {PERSON or PERSON A + PERSON B} | {UF - MUNICIPALITY} | {PROVENANCE}`
- Dated: `{STATUS} {EVENT} | {PERSON or PERSON A + PERSON B} | {PLACE} | {YYYY-MM-DD} | {PROVENANCE}`

`🟡` means the title is standardized and review has begun, but work remains. `🟢` means every extractable detail has been evaluated and placed on the correct people and fields, with applicable attachments resolved.

Rules:

- Determine the event from the source and citation. Observed types include `NASCIMENTO`, `BATISMO`, `CASAMENTO`, `ÓBITO`, and `MEMORIA PESSOAL`.
- Birth and baptism are distinct and may both exist for one person. Marriage uses `PERSON A + PERSON B`.
- The compact form may rely on FamilySearch's populated **Source Date** instead of repeating the date. Compact and dated forms do not represent different review states.
- Use `UF - MUNICIPALITY` only when both parts are supported; never invent missing dates or places.
- Provenance must match the actual source, such as `FS: Registro Civil` or `Informante: {PERSON}`. Do not label church or baptism records as civil registration merely because another title does.
- Canonical spacing is one space after the emoji, around each `|`, and after `:`.
- A missing or restricted image does not prove completeness. Green is possible only after all information available through authorized routes has been processed.

## Continuous improvement

After substantive work, retain only validated, reusable, privacy-safe lessons. Prefer a short README or AGENTS rule. Propose a separate skill only when a repeated, general workflow needs reusable tooling or detailed verification, and add it only with Yuri's approval.

This independent project is not affiliated with or endorsed by FamilySearch.
