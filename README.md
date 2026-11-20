# AI Film Lab · Director's Workbench (v0.1)

A private, local-first filmmaking learning workspace for Stu.

## Getting started

Open `index.html` in Chrome, Edge, Safari or Firefox. No install, sign-up or account required. For best reliability, serve the folder locally with `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Features

- **Academy**: eight progressive modules, twenty-four lessons and progress tracking.
- **Shot Lab**: shot briefs, camera and continuity notes, take logs, actual settings and results, image/video attachments.
- **Screening Room**: side-by-side comparison of two recorded takes.
- **Field Notes**: record insights and label evidence as heard, demonstrated, tested or repeatable.
- **Productions**: a simple project slate linked to shots by project name.
- **Backup/restore**: export a JSON file that includes notes, metadata and locally stored media. Restore from the same file.

## Important limitations

- This is a **local-first prototype**, not a cloud app. Data is stored in your browser via localStorage and IndexedDB. Another device or browser will not automatically have it.
- Use **Export backup** frequently. Clearing browser data can delete your work.
- No direct ChatGPT or video-generator integration exists yet. Lesson details are outlines; work through each lesson in the AI Film Lab ChatGPT project.
- The UI font loads from Google Fonts when online, but a local fallback works offline.
- The media size limit is 150 MB per file and is subject to browser storage availability.
- Don't put confidential client footage into shared hosting without proper security and agreements.

## Next engineering steps

1. Host with authentication and backed-up storage.
2. Synchronise work across mobile and desktop.
3. Make lessons richer, add rubrics and submission/critique history.
4. Build shot-level annotations, compare sync and frame notes.
5. Explore integrations only after consent, privacy and cost considerations.