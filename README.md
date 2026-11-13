# CloudStudy — Cloud Computing Semester Study Hub

A responsive, browser-based study website for cloud computing semester exam preparation.

## Features

- Five unit-wise study sections.
- Concise topic explanations and real-life examples.
- Topic keywords and quick search (`Ctrl`/`Cmd` + `K`).
- Expandable topic cards.
- Mark topics as completed.
- Unit-wise and overall revision progress.
- Progress saved in browser `localStorage`.
- Light/dark theme toggle.
- Responsive layout for desktop, tablet and mobile.
- No backend, build tools, API keys or installation required.

## Units included

1. Introduction to Cloud Computing
2. Cloud Deployment & Service Models
3. Virtualization
4. Networking for Cloud Computing
5. Security in Cloud Computing

## Run locally

1. Extract the ZIP file.
2. Open the `cloud-computing-semester-hub` folder.
3. Double-click `index.html`.

For a local development server, you can also run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Project structure

```text
cloud-computing-semester-hub/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Customization

- Add or edit topics in the `UNITS` array at the top of `script.js`.
- Change colors, spacing and layout in `styles.css`.
- Update the page structure in `index.html`.

## Notes on the study content

The site organizes the topics and explanations from the study summary prepared in this conversation. A few technical labels in the source notes are syllabus-specific; retain the terminology used by your course material when writing exam answers. Where a topic was only briefly outlined in the earlier summary, the site keeps that scope rather than inventing a detailed textbook treatment.

## License

For personal educational use. You may modify the project for your own study.
