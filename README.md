# Jeff Hodgens · Self-titled

My portfolio, designed as a record: cover, greatest hits, lead single, tracklist, awards, liner notes, credits and booking.

## Files

- `index.html` – the whole site (styles and scripts are inside)
- `404.html` – "Skipped track" page for broken links
- `favicon.svg` – the little record icon in the browser tab
- `.nojekyll` – tells GitHub Pages to serve the files as-is

## Setup

Email (jhodgens@gmail.com), LinkedIn and Google Analytics (G-8027QET3BM) are already set.

Analytics tracks page views automatically, plus three custom events:
- `contact_click` (method: `email` or `linkedin`)
- `track_open` (which tracklist item someone opened)
- 404 page views show up as views of the "Skipped track" page

## Publish on GitHub Pages

1. Create a new **public** repository named `yourusername.github.io` (use your GitHub username).
2. Click **Add file → Upload files** and drag in every file from this folder, including `.nojekyll`.
   (On a Mac, press `Cmd + Shift + .` in Finder to show hidden files.)
3. Click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
5. In a minute or two the site is live at `https://yourusername.github.io`.

To make edits later, open `index.html` on GitHub, click the pencil icon, change it and commit. The site updates on its own.

## Custom domain (optional)

Buy a domain (for example `jeffhodgens.com`), then in **Settings → Pages → Custom domain** enter it and follow GitHub's DNS instructions. Check **Enforce HTTPS** once it's verified.
