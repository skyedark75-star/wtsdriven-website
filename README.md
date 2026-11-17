# WTSDRIVEN website

A custom-coded, responsive portfolio website for WTSDRIVEN — automotive photography, event photography, videography/reels and creative projects.

## Project structure

```
.
├── index.html                 # Website entry point (keep at repository root)
├── assets/
│   ├── css/
│   │   └── styles.css         # All site styling and responsive layouts
│   ├── js/
│   │   └── main.js            # Navigation, portfolio filters, lightbox and enquiry form
│   └── images/
│       └── README.md          # Guidance for adding real portfolio images
├── docs/
│   └── launch-checklist.md    # Content and launch tasks
├── .gitignore
└── README.md
```

## Preview locally

Because this is a static website, no build step or package installation is required. Open `index.html` in a browser, or use a local static server (for example, VS Code Live Server).

## Before launch

- Replace all demo/Unsplash photography with approved WTSDRIVEN images.
- Replace `REPLACE-WITH-EMAIL@example.com` in `index.html` and `assets/js/main.js` with the correct enquiry email address.
- Review the copy, services, social links and image credits/permissions.
- Test the navigation, portfolio filters, lightbox and enquiry form on mobile and desktop.
- Configure GitHub Pages (or another static host) to publish from the `main` branch and repository root.

## Editing guide

- Page content and semantic structure: `index.html`
- Colours, typography, spacing and responsive styles: `assets/css/styles.css`
- Interactive behaviour: `assets/js/main.js`
- Portfolio photography: `assets/images/`

Keep `index.html` at the repository root so GitHub Pages can serve the site directly from the root folder.
