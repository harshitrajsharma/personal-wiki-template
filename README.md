# Wiki Manager Template

A clean, AI-friendly personal wiki starter kit.

This repo is designed for people who want to manage notes, goals, projects, raw sources, and personal knowledge with an AI assistant while keeping the structure simple enough to use every day.

## Quick Start

1. Download or clone this template.
2. Rename the folder to your own wiki name.
3. Open the folder in Obsidian, VS Code, Cursor, Codex, or any AI coding assistant.
4. Fill in:
   - `wiki/entities/core/profile.md`
   - `wiki/entities/core/goals.md`
   - `wiki/entities/core/dashboard.md`
5. Drop raw source files into `raw/inbox/`.
6. Ask your AI assistant:
   - "Read AGENT.md and help me set up my wiki."
   - "Organize the files in raw/inbox into my wiki."
   - "Create a study plan from my goals."
   - "Lint my wiki and find stale pages."

## What This Template Gives You

- A stable folder structure for a personal wiki.
- Rules for AI assistants so they know where to write things.
- Separation between raw material and polished notes.
- Templates for notes, projects, goals, people, and logs.
- Reusable local skills in `tools/` for note management and structure enforcement.
- No personal data, credentials, exam-specific trackers, or sync scripts.

## Core Structure

```text
.
├── AGENT.md                 # Main AI operating rules
├── README.md                # This guide
├── raw/                     # Immutable source material
├── wiki/                    # Your actual knowledge base
│   ├── index.md             # Main wiki catalog
│   ├── today.md             # Active daily working page
│   ├── entities/            # Life/project/system tracking
│   ├── notes/               # Durable knowledge notes
│   ├── logs/                # Daily, weekly, monthly records
│   └── templates/           # Markdown templates
└── tools/                   # AI skills and helper rules
```

## The Big Rule

Do not mix raw sources, polished notes, and progress tracking.

- `raw/` is the inbox and archive for source material.
- `wiki/notes/` is for durable knowledge.
- `wiki/entities/` is for goals, projects, people, dashboards, and trackers.
- `wiki/logs/` is for chronological records.

## Recommended AI Workflow

Use these commands with your AI assistant:

```text
Read AGENT.md and follow the wiki rules.
Ingest raw/inbox/<file> into the correct wiki location.
Create a new note about <topic>.
Update wiki/index.md after adding new pages.
Review today's page and suggest next actions.
Lint the wiki for broken links, stale tasks, and misplaced files.
```

## What Not To Commit

The template intentionally ignores personal/private files such as:

- Obsidian workspace state
- local credentials
- tokens
- private raw documents
- generated caches

See `.gitignore`.

