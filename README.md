# F1 AI Chatbot · Pit Lane Intel

A single-page, self-contained Formula 1 chatbot. The entire app — UI, styling,
and chat logic — lives in [`f1.html`](./f1.html); just open it in a browser.

## How it works

On first load, the app prompts for an API key (see the in-app modal for setup
steps) and stores it for the session. Once configured, you can chat about F1
drivers, teams, races, and stats directly in the browser — no build step or
server required to run the UI.

## Files

- `f1.html` — the entire application (markup, styles, and client-side logic).
- `API.ts` / `rout.ts` — placeholders for a future backend API/routing layer;
  currently empty and not wired up.

## Running locally

Open `f1.html` directly in a browser, or serve the directory with any static
file server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/f1.html`.
