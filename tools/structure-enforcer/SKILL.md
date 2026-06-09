---
name: structure-enforcer
description: Decide where new wiki files belong before creating them.
---

# Structure Enforcer

Use this before creating any new markdown file.

## Placement Map

| Content Type | Folder |
| :--- | :--- |
| Durable concept note | `wiki/notes/<domain>/` |
| Course or book notes | `wiki/notes/learning/` |
| Programming or CS notes | `wiki/notes/computer-science/` |
| Cheatsheets and commands | `wiki/notes/reference/` |
| Essays and blog drafts | `wiki/notes/writing/` |
| Goals | `wiki/entities/core/` or `wiki/entities/areas/` |
| Projects | `wiki/entities/projects/` |
| People | `wiki/entities/people/` |
| Daily or weekly logs | `wiki/logs/` |
| Temporary active plan | `wiki/today.md` |
| Raw source | `raw/inbox/` |

## Naming Rules

- Use lowercase kebab-case for general filenames.
- Use `YYYY-MM-DD.md` for dated logs.
- Avoid vague filenames like `misc.md`.
- Do not place random files directly under `wiki/`.

## Index Rules

When a new important page is created:

1. Update the nearest folder `index.md`.
2. Update `wiki/index.md` if the page is a major entry point.
3. Link back to related pages.

