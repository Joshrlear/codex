# Josh Lear Portfolio

This repository contains a single-page personal portfolio for Josh Lear, a Solutions Architect specializing in Microsoft 365, Azure, and the Power Platform.

## Project structure

```
├── index.html          # Main portfolio page
└── assets/
    └── css/
        └── styles.css  # Styling for the site
```

## Local development

Because the site is static HTML and CSS, you can preview it with any static file server. For example:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Deployment

To publish on GitHub Pages:

1. Create a new repository on GitHub (or fork this one).
2. Push the contents of this project to the `main` branch.
3. In the repository settings, enable **Pages** and choose the `main` branch with the root directory.
4. After a few moments, your portfolio will be available at `https://<username>.github.io/<repository-name>/`.

Update the content whenever needed by editing `index.html` and `assets/css/styles.css`.
