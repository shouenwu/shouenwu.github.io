# Joseph Wu — Homepage

Only the navigation and hero from the Figma portfolio are included in this initial version. It contains a short introduction, technical focus tags, GitHub links, and the original illustrative robot viewport. The viewport is a static illustration, not live telemetry.

Experience, projects, education, research, certifications, contact details, and the resume link are deferred to a later revision. No build tools or JavaScript are required.

## Preview

```sh
python3 -m http.server 8000
```

Open http://localhost:8000. Fonts load from Google Fonts with system fallbacks. `style.css` contains the Figma base styles; `responsive.css` contains the desktop, tablet, and mobile layout adjustments. `assets/` contains original exported SVG layers.

## Validation

Local SVGs, image references, navigation targets, and the single-section document structure have been checked. Browser visual verification remains pending because this execution environment blocks browser startup.

## Deployment

Keep the existing `CNAME` unchanged. Review the draft pull request before merging into `master`, which uses the existing GitHub Pages deployment at https://shouenwu.me/.
