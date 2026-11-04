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

Replace `YOUR_USERNAME` with your GitHub username:

```bash
git init
git add .
git commit -m "Create static portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

Create a public repository named `YOUR_USERNAME.github.io` before running the commands above. GitHub Pages will normally publish the site automatically from the `main` branch. If it does not, open the repository's **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.

Your live URL will be:

```text
https://YOUR_USERNAME.github.io
```

## Customization

Update the name, email, social links, project details, and colors in `index.html` and `styles.css` before publishing.
