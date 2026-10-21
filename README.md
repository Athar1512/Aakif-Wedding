# Aakif & Fatema — Wedding Invitation

A single-page wedding invitation, hosted on GitHub Pages.

**Live site:** https://athar1512.github.io/Aakif-Wedding/

## Files

- `index.html` — the whole invitation (styles, countdown script and content are all inline)
- `.nojekyll` — tells GitHub Pages to serve the files as-is, without running Jekyll

## Editing

Edit `index.html`, commit, and push to `main`. GitHub Pages redeploys automatically within a minute or two.

Each event (Baarat, Nikah, Reception) has its own countdown. The target time is the `data-t`
attribute on that event's `<div class="count">`, for example `data-t="2026-11-21T17:30:00+05:30"`.
Change the attribute and the countdown follows; the script needs no edits.
