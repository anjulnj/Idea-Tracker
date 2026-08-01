# Idea Tracker

A small local tool for jotting down research ideas before they slip away.

Built this over a weekend because I kept having the same problem: get an idea while reading a paper, forget it by the next section — or worse, have the same idea again months later without realizing I'd already had it.

## What it does

- Type an idea and attach the PDF you were reading — title, authors, and DOI get pulled automatically
- Gently flags if a new idea looks similar to one you've already logged
- Set a due date (with quick +3d / +1w shortcuts) and get a calendar reminder (.ics or Google Calendar)
- Everything is saved to a folder on your own machine — no account, no server, nothing sent anywhere
- A small panel shows how many ideas actually get followed up on vs. left stale

## Using it

It's a single HTML file — no install, no build step.

- **Try it live:** [your GitHub Pages link]
- **Or download `idea-tracker.html`** from this repo and open it in Chrome or Edge (needed for the local-folder saving feature; other browsers work too, just fall back to downloads instead of folders)

## Notes

- Works best in Chrome or Edge, since folder-saving relies on a browser feature (File System Access API) that Safari and Firefox don't support yet — those browsers still work fine, they just download files instead of saving to a chosen folder.
- Everything stays local. There's no backend, no tracking, no account.

Made for my own workflow, sharing in case it's useful to anyone else.

