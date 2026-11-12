# Task 5: Static Website on GitHub Pages

A responsive developer portfolio website built with plain HTML, CSS, and JavaScript. It is designed to be hosted for free with GitHub Pages.

## Files

- `index.html` - page structure and content
- `styles.css` - responsive layout, colors, typography, and animations
- `script.js` - mobile navigation and dynamic footer year

## Run locally

From this folder, start any local static server:

```bash
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a browser.

## Deploy with GitHub Pages

This project is deployed from the `HJ9002/Task5.github.io` repository.

To publish changes from the project folder:

```bash
git add .
git commit -m "Update portfolio website"
git push -u origin main
```

To enable GitHub Pages with the GitHub CLI, authenticate first with `gh auth login`, then run:

```bash
gh api --method POST repos/HJ9002/Task5.github.io/pages `
  -f "source[branch]=main" -f "source[path]=/"
```

If Pages is already enabled, use the repository's **Settings > Pages** page instead and choose **Deploy from a branch**, `main`, and `/ (root)`.

The live URL is:

```text
https://hj9002.github.io/Task5.github.io/
```

## Customization

Update the name, email, social links, project details, and colors in `index.html` and `styles.css` before publishing.
