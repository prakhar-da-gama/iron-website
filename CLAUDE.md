# Instructions for Claude

## Do not run or launch the website unless explicitly asked

Do **not** run, serve, launch, or open the website — and do **not** use any
skill/tool (e.g. `run`, `verify`, Playwright, `Start-Process`, a dev server,
etc.) to do so — unless the user **explicitly** requests it in that message.

- Make the code changes and report what changed. That is enough by default.
- Only launch/preview/verify the site when the user says so (e.g. "run it",
  "open it", "verify it", "take a screenshot").

## Project notes

- Single-page site: `index.html` (all HTML, CSS, and JS inline).
- The site is a horizontal "reel": each section is a full-screen snap panel,
  navigated with arrows, progress dots, wheel→horizontal scroll, keyboard, and
  anchor links. Panels that overflow vertically show an animated "Read more"
  swipe-down cue.
