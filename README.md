# SEO-AI-Buildathon-2026
Networking Tracker

# Coffee Chat Tracker

A single-file app (HTML, CSS, vanilla JS) for tracking networking conversations: calendar, people, tags, AI summaries and an "Ask AI" page that answers from your own notes.

## Run it
Open `networking-tracker.html` in a browser, or host it with GitHub Pages.

## What works outside claude.ai
- Calendar, People, tags and filters, notes, undo, JSON export/import, demo data
- Data is stored in the browser (`localStorage`)

## What only works inside claude.ai
The AI features (summaries, suggested questions, Ask AI), account-based storage and the export download button use the `window.claude` runtime. Outside claude.ai they are hidden or show a "not available" message.
To use them elsewhere, add a small server-side API route that calls an AI provider and keep the API key on the server.

## Not implemented
- Google Calendar / Outlook sync (needs OAuth credentials and a backend)
- Live web research for people

All demo contacts are fictional.
