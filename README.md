# Codex-Assisted FamilySearch Workflows

A lightweight, public guide to using Codex, its in-app browser, and local-computer tools for careful family-history work on [FamilySearch.org](https://www.familysearch.org/).

## Scope and safety

- The repository tracks `README.md`, `AGENTS.md`, and the approved reusable skill in `skills/familysearch-source-standardizer`. It is not an application, research archive, or session log.
- Never store private genealogy, living-person data, screenshots, exports, credentials, cookies, or authentication artifacts here.
- Each session starts by reusing or opening FamilySearch and leaving it visible for Yuri to authenticate. Codex never handles credentials or authentication codes.
- Exploration is read-only by default. Any FamilySearch modification requires explicit approval.

## Efficient browser workflow

- Known person: `/en/tree/person/{tab}/{person-id}`, where `{tab}` includes `details`, `sources`, `memories`, `timeline`, and related profile tabs.
- Known tree focus: `/en/tree/pedigree/{view}/{person-id}`. **View Tree** re-centers the last tree view.
- Unknown person: use **Recents** to identify the correct profile and branch before following relationships.
- During a task, keep a short, temporary map of active person IDs and verified parent, spouse, and child relationships. Recheck it before any modification and never persist it.
- Source review progresses from **Sources list → source card → indexed record → Source Linker → accessible image or authorized external record**. Stop wherever evidence or permission ends.
- FamilySearch loads dynamically. Wait for real content, then verify the person, heading, destination, and opened dialog before continuing. Leave reconnaissance forms through **Cancel** or **Close**, never **Save**.

## Source-title convention

- Canonical: `{STATUS} {EVENT} | {PRIMARY PERSON or PERSON A + PERSON B} | {UF - MUNICIPALITY} | {PROVENANCE}`

`🟡` means review has started; `🟢` means review has been completed using all evidence available through authorized routes. These statuses track progress, not historical reliability or freedom from human error.

Rules:

- Determine the event from the source and citation. Observed types include `NASCIMENTO`, `BATISMO`, `CASAMENTO`, `ÓBITO`, and `MEMORIA PESSOAL`.
- The person segment identifies the document's primary subject or subjects, independently of the profile where the source is attached. Birth and baptism are distinct; marriage uses both spouses.
- The canonical title never repeats the date. Verify and, with approval and supporting evidence, update **Source Date** to the primary event date. Preserve relevant secondary or administrative dates in the citation or notes.
- Use `UF - MUNICIPALITY` only when both parts are supported; never invent missing dates or places.
- Provenance follows the source's origin: use `FS: Registro Civil` for sources of civil origin and `FS: Registro Paroquial` for sources of parish origin, whether FamilySearch presents them through an index, OCR, transcription, or image; use `Acervo familiar` for material genuinely held by the family and `Informante: {PERSON}` for personal testimony. Do not copy a label from another title.
- Canonical spacing is one space after the emoji, around each `|`, and after `:`.
- A missing or restricted image does not prove completeness. Green is possible only after all information available through authorized routes has been processed.

## What each source field does

- **Source Date:** the primary event date used to sort sources chronologically.
- **Title:** a recognizable identifier for the specific record; consistent wording also improves at-a-glance scanning and Source Box title searches.
- **Citation:** where the record can be found. **Notes:** transcription, explanation, and relevant secondary details.
- **Reason to attach:** why the source belongs to the person or relationship. **Tags:** the exact facts the source supports.

These interpretations follow FamilySearch's current guidance for [creating sources](https://www.familysearch.org/en/help/helpcenter/article/how-do-i-create-a-source-in-family-tree), [outside-source fields](https://www.familysearch.org/en/help/helpcenter/article/how-do-i-add-an-outside-source-to-family-tree), [source dates](https://www.familysearch.org/en/help/helpcenter/article/how-do-i-organize-my-ancestors-sources-in-family-tree), [primary people](https://www.familysearch.org/en/help/helpcenter/article/who-is-the-primary-person), and [source tags](https://www.familysearch.org/en/help/helpcenter/article/how-do-i-tag-a-source-in-family-tree-to-a-specific-piece-of-information).

Because Family Tree is shared, clear titles, citations, reasons, and tags help collaborators find the evidence, understand why it is attached, and evaluate conflicts. FamilySearch describes these [collaboration benefits](https://www.familysearch.org/en/help/helpcenter/article/what-are-the-benefits-of-adding-sources-to-family-tree); the compact syntax itself is our convention, not an official FamilySearch standard.

## Continuous improvement

After each substantive FamilySearch interaction, assess navigation and verification, review the guidance for safe compaction, and end the report with a short confirmation quiz about new conventions or unresolved assumptions. Change documentation or the approved skill only for validated, reusable, privacy-safe lessons, and keep its repository source synchronized with the local installation.

This independent project is not affiliated with or endorsed by FamilySearch.
