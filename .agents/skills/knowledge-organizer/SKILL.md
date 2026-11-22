---
name: knowledge-organizer
description: Use when the user wants to organize newly added documents, images, notes, text snippets, scans, or uncategorized files in a Personal Knowledge Store.
---
Organize new or uncategorized material in this Personal Knowledge Store.
Follow the repository's AGENTS.md instructions.
Workflow:
1. Find new, uncategorized, or recently added files.
2. Inspect file names, file types, and readable content.
3. Choose the best existing category folder.
4. If a file cannot be categorized promptly, ask the user before moving it. Present the likely categories as clickable multiple-choice options, include a choice to keep the file in `inbox/`, and briefly explain why the category is unclear. Ask as soon as the uncertainty is identified, while continuing to organize other files with clear destinations.
5. If no existing category fits, ask whether to create a new category folder.
6. Move files only after the destination is clear.
7. Update the destination folder's index.md with:
- file name
- short summary
- date, if known
- source, if known
- tags
- reason for placement
8. Never delete or overwrite original content without asking.
9. Summarize the changes at the end.
