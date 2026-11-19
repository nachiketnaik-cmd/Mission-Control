# Mission Control

A personal life-admin dashboard — a scrolling strip of **lanes** for tasks, grad-school
applications, job hunt, projects, hobbies, life admin and more. Built with Claude.

**Live site:** https://nachiketnaik-cmd.github.io/Mission-Control/

## Features
- **Movable, resizable blocks** — drag any block by its header (⠿ grip) to place it anywhere;
  drag its right edge, bottom edge, or corner to resize width and height. Positions and sizes
  persist in your browser, and **Reset layout** in the top bar restores the default arrangement.
- **Add / remove blocks** — **＋ Add block** in the top bar creates your own custom blocks or
  restores ones you've hidden; the **✕** on any block's header removes it.
- **The ONE Thing** — a dedicated focus block that shows only your single most important thing.
- **Editable boards** — tick items off, double-click text to edit, `+` to add, `×` to delete,
  across Tasks, Grad applications, Job hunt, Life admin, Projects, Hobbies and Saved.
  Everything saves locally in your browser (`localStorage`).
- **Email & Calendar** snapshot panes and a quick-launch grid.

## The "Ask Claude" chat
The chat dock at the bottom only works inside **claude.ai** — it uses a capability the Claude
host provides (`window.claude`), which a plain website doesn't have. On this GitHub Pages site
it will show *"open in claude.ai to chat"*; every other part of the dashboard works as a
fully static page.

## Tech
A single self-contained `index.html` — no build step, no dependencies, no tracking.
Styled in Times New Roman. Just open the file.
