# WPS macOS Helper

## English

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

---

## 中文介绍

WPS 在 macOS 上并不是不能用，但只要 Markdown、docx、PDF、导出这些步骤混在一起，文档工作流很快就会变得很别扭：版式会跑、分页会变、字体会替换、表格会错位，前一步看着还正常，到了下一步就可能出问题。

这个 skill 想做的，就是把这条链路尽量理顺一点。

它的第一版没有走高风险的 GUI 暴力自动化路线，而是更保守一些：先把内容准备好，先选更稳的转换路径，再把 WPS 留给最后的检查、微调和导出。

它主要适合这些场景：

- 在用 WPS 打开之前，先把内容整理好
- 减少 Word 和 WPS 之间的兼容性意外
- 给 Markdown、docx、PDF、PPT、Excel 这些文件选更稳的转换路线
- 在 macOS 上做导出前的格式检查
- 排查字体、表格、分页、页眉页脚、PDF 导出这些常见问题

整个 skill 的结构也比较克制：

- 一个聚焦的 `SKILL.md`
- 几份关于工作流、兼容性、导出检查和排障的参考说明
- 一个低风险的预处理辅助脚本

核心思路其实很简单：先用更适合处理文本和结构的工具把内容理顺，再把 WPS 放在最后一公里来完成视觉检查和导出。

## 当前状态

这还是一个早期公开候选版本。现在已经跑过了有代表性的 Markdown 和 docx 工作流测试，也考虑了依赖缺失时的兜底处理，但整体上仍然保持得比较克制。

如果您本来就在 macOS 上用 WPS，又希望先把文档工作流做稳，再决定要不要上更重的自动化，这个版本比较适合作为起点。
