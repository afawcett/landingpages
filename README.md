# AndyInTheCloud Consulting - Presentation Landing Pages

This is a GitHub Pages site that hosts landing pages for presentations given by AndyInTheCloud Consulting.

## Structure

- `index.html` - Main page listing all presentations
- `sessions/` - Individual session pages
- `images/` - Graphics and images for presentations
- `styles.css` - Site-wide styling

## Adding a New Presentation

1. Create a new HTML file in the `sessions/` directory (e.g., `sessions/my-presentation.html`)
2. Copy the structure from an existing session page
3. Update the content:
   - Title and event badge
   - Session graphic (add image to `images/` folder)
   - Session summary
   - Resources list
4. Add a new presentation card to `index.html` in the presentation grid

## Session Page Template

Each session page includes:
- Title and event badge
- Session graphic/image
- Brief summary of the session
- List of resources (links to slides, repos, docs, etc.)
- Consulting services section with contact information

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select the branch (usually `main` or `gh-pages`)
4. Select the root directory
5. Save - your site will be available at `https://[username].github.io/landingpages`

## Local Development

Simply open `index.html` in a web browser or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

