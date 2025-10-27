# Copilot Instructions for Kropp-Fitness

## Project Overview
This is a static website project for Kropp-Fitness, structured with HTML, CSS, and static assets (images, fonts, icons). There is no build system, backend, or JavaScript logic present in the current codebase.

## Key Directories & Files
- `index.html`: Main entry point. All content and structure are defined here.
- `styles.css`: Contains all styling for the site. Follows a flat CSS structure.
- `images/`, `icons/`, `fonts/`: Contain static assets referenced in HTML and CSS.

## Patterns & Conventions
- **Asset Referencing**: All images, icons, and fonts are referenced with relative paths from the HTML and CSS files. Example: `images/family/1.jpg` or `fonts/Heebo-Bold.woff2`.
- **No Build Step**: All files are served as-is. There is no minification, bundling, or preprocessing.
- **No JavaScript**: The site is currently static with no client-side scripting.
- **Font Usage**: Custom fonts are loaded via `@font-face` in `styles.css`.
- **SVG Icons**: Used directly as image sources in HTML.

## Developer Workflows
- **Preview**: Open `index.html` directly in a browser to view the site.
- **Add Assets**: Place new images in the appropriate subfolder under `images/`, icons in `icons/`, and fonts in `fonts/`.
- **Update Styles**: Edit `styles.css` for all visual changes.

## Examples
- To add a new team member photo, place the image in `images/family/` and reference it in `index.html`.
- To use a new icon, add the SVG to `icons/` and reference it in HTML as `<img src="icons/new-icon.svg">`.

## Special Notes
- There are no automated tests, build scripts, or package dependencies.
- Keep all asset references relative and consistent with the current structure.
- Maintain the flat, simple structure for ease of editing and deployment.

---

For any major changes (adding JS, restructuring, etc.), update this file to reflect new conventions or workflows.
