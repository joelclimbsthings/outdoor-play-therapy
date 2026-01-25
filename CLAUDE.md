# Claude Code Instructions for Outdoor Play Therapy Site

## User-Friendly Commands

### "Update the site"
When the user asks to "update the site," "publish changes," or "deploy":
1. Stage all changes: `git add -A`
2. Commit with a descriptive message summarizing the changes (do NOT include a Co-Authored-By line)
3. Push to origin/main: `git push origin main`

The site will automatically deploy after pushing to main.

## Project Overview

This is a static website for an outdoor play therapy business. The site uses:
- HTML, CSS, and JavaScript
- No build step required - files are served directly
- Hosted via GitHub Pages (or similar) - pushing to main deploys the site

## Common Tasks

- **Edit content**: Modify the HTML files directly
- **Change styles**: Edit the CSS files
- **Update images**: Add images to the appropriate folder and reference them in HTML
