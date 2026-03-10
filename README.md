# WPS macOS Helper

WPS on macOS is usable, but once Markdown, docx, PDF, and export steps start mixing together, things get messy fast. Layout shifts, page breaks move, fonts change, tables drift, and what looked fine in one place suddenly looks wrong in another.

This skill is meant to make that workflow less painful.

It does not try to control WPS with aggressive GUI automation. The first version takes a more conservative route: prepare the content first, choose a safer conversion path, and treat WPS as the place for final checking, polishing, and export.

It is useful for things like:

- preparing content before opening it in WPS
- reducing Word/WPS compatibility surprises
- choosing safer conversion paths for Markdown, docx, PDF, PowerPoint, and Excel files
- checking export and formatting steps on macOS
- troubleshooting fonts, tables, page breaks, headers, footers, and PDF output

The skill itself is simple:

- a focused `SKILL.md`
- reference notes for workflow, compatibility, export checks, and troubleshooting
- a low-risk helper script for preprocessing guidance

The basic idea is straightforward: use text-first tools for understanding and restructuring, then use WPS for the last mile.

## Current status

This is an early public release candidate. It has already been tested on representative Markdown and docx workflows, including dependency fallback handling, but it is still intentionally conservative.

If you use WPS on macOS and want a workflow that is safer and less brittle before moving into heavier automation, this is a good place to start.
