# Timeline Planner

A responsive, local-first project timeline planner built with plain HTML, CSS and JavaScript.

## Features

- Add, edit and delete tasks
- Add milestones
- Start and end dates
- Status, priority and progress tracking
- Horizontal timeline view
- Drag tasks and milestones to reschedule by whole days
- Search and filters
- Automatic browser storage
- JSON import and export
- Responsive interface
- Dark mode
- No account, backend or build step

## Run locally

Open `index.html` in a modern browser.

## GitHub Pages

Publish directly from the repository root:

1. Open **Settings**
2. Select **Pages**
3. Choose **Deploy from a branch**
4. Select `main`
5. Select `/ (root)`
6. Save

## Project structure

```text
timeline-planner/
├── index.html
├── assets/
│   ├── app.js
│   └── styles.css
├── .gitignore
├── LICENSE
└── README.md
```

## Data and privacy

Project data is stored in the browser using `localStorage`. Nothing is intentionally uploaded to a server. Export JSON regularly if the project is important because clearing browser storage can remove saved data.

## Roadmap

- Resize task duration by dragging edges
- Task dependencies
- Multiple projects
- Monthly and quarterly zoom levels
- Undo and redo
- CSV import and export
- Printable project report
- Automated browser tests

## License

MIT
