# to-do-app
Customized app to maintain my to do lists, as well as to maintain notes around key accounts and team members

## Features
- **Subjects** (clients, team members, projects) in a sidebar, with nested **sub-categories** (any depth, collapsible)
- **To-dos** per subject with optional due dates; parent subjects roll up their sub-categories' items
- **Notes** per subject with a rich-text editor and a 6-colour **highlighter**
- **All to-dos** and **Due & overdue** views across every subject
- Global **search** across to-dos and notes (Ctrl/Cmd + K)
- **Export / Import** JSON backups

## Running it
The whole app is one file, `index.html`, with no build step or dependencies.

- Double-click `index.html` to open it in your browser, **or**
- Serve the folder locally: `python3 -m http.server 8000`, then open http://localhost:8000

## Where data is stored
Everything is saved in your browser's `localStorage` (key `subjects-app-v1`). Data is per browser and per address, so use **Export** to back up or to move data between browsers or machines, and **Import** to restore it.
