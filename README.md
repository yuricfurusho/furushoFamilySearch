# Codex-Assisted FamilySearch Workflows

A lightweight, public guide to using Codex, its in-app browser, and local-computer tools for careful family-history work on [FamilySearch.org](https://www.familysearch.org/).

## Motivation

Elder Dale G. Renlund's April 2018 message, [“Family History and Temple Work: Sealing and Healing”](https://www.churchofjesuschrist.org/study/general-conference/2018/04/family-history-and-temple-work-sealing-and-healing?lang=eng), describes family history and temple work as a way to connect generations and bring blessings and healing to the living as well as the dead. His invitation to make time for this work inspires this project's approach: make family history easier to return to daily through small, manageable sessions, with Codex helping reduce friction while people guide the work.

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
- **VIEW**, **BROWSE THE FILM**, and **VIEW IMAGE** may open another tab. Check the tab inventory, close temporary tabs, and inspect authorized links from both current and retired records before declaring an image unavailable. Confirm the exact entry when a film link is only approximate.
- For guided review, show one concrete uncertainty at a time. Codex handles readable metadata; the human supplies judgment where the evidence needs it. Agree on a finite source set so new arrivals do not keep expanding a cleanup pass.
- Aim for about five minutes of the user's active review time per session. Prepare readable evidence and a small, achievable objective in advance; present one decision at a time and leave a clear next step. Treat five minutes as a target, not a reason to rush evidence or imply completion.
- Agree on review depth: **metadata-only** for formatting, dates, citations, and readable indexed fields; **evidence-complete** for image review and information extraction. A quick closeout stays metadata-only: do not browse film pages or expand the family. Report deeper checks and uninspected sources as pending in the chat, with stable links, without claiming the genealogy or all formatting is complete.

## Source-title convention

- Canonical: `{STATUS} {EVENT} | {PRIMARY PERSON or PERSON A + PERSON B} | {UF - MUNICIPALITY} | {PROVENANCE}`

`🟡` means review has started; `🟢` means review has been completed using all evidence available through authorized routes. These statuses track progress, not historical reliability or freedom from human error.

For a confirmed duplicate, use `⚪` and append ` | DUPLICATA`. Keep useful image links and existing attachments; identify the preferred source in the change reason or an approved note. A retired record may retain information or access that the current copy lacks.

Rules:

- Determine the event from the source and citation. Observed types include `NASCIMENTO`, `BATISMO`, `CASAMENTO`, `ÓBITO`, and `MEMORIA PESSOAL`.
- The person segment identifies the document's primary subject or subjects, independently of the profile where the source is attached. Preserve the record's spelling; state whether a proposed name comes from an index or an image when they differ. Birth and baptism are distinct; marriage uses both spouses.
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

Yuri's approval of a durable local configuration or workflow decision for this repository includes commit, push, and merge without another publication confirmation. Follow the review, privacy, synchronization, and remote verification steps in `AGENTS.md`; preserve unrelated work and report any blocked checks or protections without bypassing them. This repository-only authorization does not permit FamilySearch changes or storing genealogical decisions and case data in Git.

This independent project is not affiliated with or endorsed by FamilySearch.
