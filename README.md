# Indusha & Anjana — Wedding Invitation

Static site for GitHub Pages. No build step.

## Pages
- `/` — landing page
- `/wedding/` — wedding invitation (envelope opens to reveal the card)
- `/homecoming/` — homecoming reception: countdown, calendar buttons, venue and directions

## Deploy on GitHub Pages
1. Create a GitHub repository and push this folder's contents to `main`.
2. **Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.**
3. Live at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

## Editing
- Colors and fonts: `style.css` (`:root` variables at the top).
- Event date/time for the countdown and calendar files: the `<script>` at the bottom of `homecoming/index.html`.
