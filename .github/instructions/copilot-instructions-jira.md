# Copilot Instructions: Jira Epics (P81)

Use these instructions whenever the user asks to review, fix, or write a Jira Epic description.

## Goals

- Make the epic description readable, structured, and actionable.
- Preserve the existing required section structure.
- Convert vague placeholders ("…", "TBD") into concrete, non-speculative statements.

## Workflow (Always)

1. Fetch the Jira issue (summary + current description).
2. Identify the required section structure:
	- If the description already contains the section headings below, keep them.
	- If the user provides a structure elsewhere, follow that exactly.
3. Rewrite the content to fit the structure:
	- Fix spelling/grammar and improve clarity.
	- Keep scope realistic; do not invent facts.
	- Make criteria measurable (success + acceptance).
4. Update the Jira issue description.
	- If editing is blocked, post the corrected full description as a comment.

## Writing Rules

- Keep the same headings and ordering (do not add sections unless the user asks).
- Prefer short paragraphs and bullets.
- Avoid internal jargon where possible; if unavoidable, define it once.
- Do not promise timelines, points, systems, or deliverables you cannot infer from context.
- Ensure “Acceptance Criteria” is checkable: each item should be verifiable.
- “Technical Scope” must include **In scope** and **Out of scope**.
- If information is missing, do one of the following (choose the minimal option):
  - Write an explicit assumption as an assumption (only if unavoidable), or
  - Add a single “Open Questions” bullet list inside an existing section (prefer **Technical Scope**) and keep it short.

## Jira Epic Description Template (Markdown)

Copy this structure exactly (titles and order). Fill all placeholders.

### Problem Statement

- What is broken / inefficient today?
- Who is impacted and how?
- What is the desired change (one sentence)?

### Solution Overview

- High-level approach (what will change).
- How the new flow/process will work.
- Key constraints/decisions.

### Success Criteria

- Outcome-focused, measurable statements (3–6 bullets).

### Technical Scope

In scope:

- …

Out of scope:

- …

### Sprint-Based Delivery (how many sprints, how many weeks)

#### Sprint 1 (3 weeks, 8 points): What has to be done

- …

#### Sprint 2 (3 weeks, 8 points): What has to be done

- …

### Acceptance Criteria

This epic is considered complete when:

1. …
2. …
3. …

