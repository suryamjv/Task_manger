# My Task Tracker

A lightweight, single-file task tracker you can run in any browser or host as a static site.

**Live page:** _after you enable GitHub Pages, your URL will be_ `https://<your-username>.github.io/<repo-name>/`

## Features

- Add tasks with status, priority, due date, and who assigned them
- Log a dated **daily update** on each task
- **Hand off** a task to a coworker — the current owner and handoff history are tracked
- Filter and sort by status, owner, priority, or due date
- **Manager report** — a clean, read-only status page to print or share
- **Export for Jira** — download a CSV to bulk-import tasks into Jira
- **Backup / Restore** your data as a JSON file

## How your data is stored

The tracker saves everything **in your own browser** (local storage) — nothing is uploaded, and the published page contains no personal data. Each person who opens the page keeps their own private list. Use **Backup** regularly and to move data between devices.

## Use it

- **Online:** open the GitHub Pages URL above.
- **Offline:** download `index.html` and double-click it.

## Tech

One self-contained `index.html` — no build step, no dependencies, no server.
