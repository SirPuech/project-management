# Project Management — Demo

Public demo of **KRIDA Projects**, a private, calm project command center. This
build runs entirely in the browser with **dummy data** (`localStorage`) — no
backend, no real data. Part of the KRIDA Mini-ERP series.

**Live:** enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root),
then open `https://sirpuech.github.io/project-management/`. Or just open
`index.html` locally.

## What it shows

- **Board / Calendar / Today** views across categories, drag-and-drop or `‹ ›` to move cards.
- Rich cards: stage, start/due dates, details, references, tools, tags,
  **checklist with per-sub-task due dates**, and **image attachments**.
- Bilingual **TH / EN**. **No notifications** — date awareness is pull-only.

## The real thing

The private version is a Google Apps Script web app backed by Google Sheets +
Drive (data you own, syncs across Mac & iPhone). Same UI, one store layer that
uses the Sheet when hosted by Apps Script and this dummy `localStorage` seed
otherwise. The demo carries no real project data.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
