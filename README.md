# Mission Control

A personal life-admin dashboard — a scrolling strip of **lanes** for tasks, grad-school
applications, job hunt, projects, hobbies, life admin and more. Built with Claude.

**Live site:** https://nachiketnaik-cmd.github.io/Mission-Control/

## Features
- Horizontal **lanes** you scroll through (trackpad, the chips along the bottom, or the scroll wheel).
- **Drag** a lane by its header (⠿ grip) to reorder it; **drag its right edge** to resize it,
  and double-click that edge to reset. Lane order and widths are remembered in your browser.
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
