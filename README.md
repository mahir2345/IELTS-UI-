# TutorMigo IELTS UI

A standalone, interactive IELTS Academic practice interface built with HTML, CSS, and vanilla JavaScript.

## Live Demo

[Open the live application](https://ieltsuidesign1.vercel.app)

## Overview

TutorMigo provides a focused practice workspace for the four IELTS skills:

- Listening
- Reading
- Writing
- Speaking

The interface includes individual skill activities, a guided mock practice flow, progress tracking, timers, answer review, and browser-based draft saving.

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Accessible navigation with keyboard-friendly controls and a skip link
- Listening practice with browser speech playback and transcript support
- Reading questions with answer checking
- Writing tasks with word-count guidance
- Speaking practice with preparation timers and optional audio recording
- Guided mock test combining listening, reading, writing, and speaking activities
- Progress dashboard with practice history and streak tracking
- Local browser storage for drafts, attempts, goals, and settings
- Print-friendly practice and review screens
- Reduced-motion support for users who prefer less animation

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web Storage API
- Web Speech API
- MediaRecorder API

No external libraries, APIs, analytics, or build tools are required.

## Getting Started

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/mahir2345/IELTS-UI-.git
   ```

2. Open the project directory:

   ```bash
   cd IELTS-UI-
   ```

3. Start the interface by opening `index.html` in a modern web browser.

For the best experience, serve the file through a local development server. Speaking recordings require a secure context such as HTTPS or `localhost`.

Example with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```text
.
├── index.html
└── TutorMigo_IELTS_UI_Complete_Interactive_Practice.html
```

`index.html` is the primary entry point for the application. The standalone HTML file contains the complete interface and interaction logic in a single document.

## Data and Privacy

Practice drafts, goals, attempts, and progress are stored locally in the browser using `localStorage`. The application does not currently send practice data to a server.

Audio recording depends on browser permissions and is kept in the current browser session unless downloaded by the user.

## Browser Support

Use a current version of Chrome, Edge, Firefox, or Safari. Some features, including speech playback and audio recording, depend on browser support and permission settings.

## Planned Production Integrations

The interface includes extension points for:

- Recorded listening audio assets
- Authenticated progress storage
- Scored writing and speaking endpoints
- A licensed full-length mock test question bank

## License

No license has been specified for this repository yet.
