# WPS macOS Helper

A small AgentSkill for people who use WPS Office on macOS and keep running into the same annoying document problems: layout drift, export weirdness, docx compatibility issues, and the general mess that happens when Markdown, PDF, Word, and WPS all end up in the same workflow.

This skill does not try to brute-force WPS with risky GUI automation. The first version takes the safer route: clean up the document workflow, convert content into formats that are easier to inspect, and leave WPS as the final place for visual checking and export.

In practice, it helps with things like:

- preparing content before opening it in WPS
- reducing Word/WPS compatibility surprises
- choosing safer conversion paths for Markdown, docx, PDF, PowerPoint, and Excel files
- checking export and formatting steps on macOS
- troubleshooting fonts, tables, page breaks, headers, footers, and PDF output

The skill includes:

- a focused `SKILL.md`
- reference notes for workflows, compatibility, export checks, and troubleshooting
- a low-risk helper script for preprocessing guidance

The idea is simple: use text tooling for understanding and restructuring, then use WPS for the final editing pass.

## Current status

This is an early public release candidate. It has already been tested on representative Markdown and docx workflows, including dependency-fallback handling, but it is still intentionally conservative.

If you want a safer macOS + WPS workflow before jumping into heavier automation, this is the version to start with.
