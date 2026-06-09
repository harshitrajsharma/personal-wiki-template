---
name: note-manager
description: Ingest, format, and organize raw notes into the wiki.
---

# Note Manager

Use this skill when the user asks to import, clean, summarize, or organize notes.

## Rules

- Raw material stays in `raw/`.
- Clean knowledge goes into `wiki/notes/`.
- Trackable objects go into `wiki/entities/`.
- Time-based reflections go into `wiki/logs/`.
- Every important folder should have an `index.md`.

## Workflow

1. Read the raw source.
2. Identify the type:
   - knowledge note
   - project
   - goal
   - person
   - log
   - reference
3. Create or update the correct page.
4. Add YAML frontmatter.
5. Add related links.
6. Update the nearest `index.md`.
7. Summarize what changed for the user.

## Note Quality Checklist

- Clear title.
- Short summary.
- Useful sections.
- Links to related notes.
- No private secrets.
- Not a dump of raw unprocessed text.

