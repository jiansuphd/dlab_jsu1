# Repository Refactoring Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Refactor personal repository structure to mirror the enterprise repository structure, ensuring standard naming conventions and GitHub-compatible Markdown.

**Architecture:** Standardized folder naming (lowercase), centralized MOC management, and regex-based link conversion.

**Tech Stack:** Bash, sed/perl (for regex), Git.

---

### Task 1: Directory Renaming
- [ ] Rename `00_meta` to `meta`
- [ ] Rename `10_projects` to `projects`
- [ ] Rename `20_wiki` to `wiki`

### Task 2: MOC Relocation
- [ ] Move `00_meta/root_MOC.md` to `root_MOC.md`
- [ ] Move `00_meta/10_projects_MOC.md` to `projects/projects_MOC.md`
- [ ] Move `00_meta/20_wiki_MOC.md` to `wiki/wiki_MOC.md`

### Task 3: Link Syntax Conversion
- [ ] Regex replace Obsidian wiki-links `[label](file.md)` to `[label](file.md)` across all markdown files.
- [ ] Regex replace backlink footers if present.

### Task 4: Linting
- [ ] Run lint tool to identify broken links or orphan pages.
