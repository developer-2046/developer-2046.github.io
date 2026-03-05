# Yuvraj Malik - Portfolio Website

A static, zero-dependency portfolio website designed for a quant researcher/developer. Emphasizes performance, accessibility, and clean aesthetics.

## Features
- **Zero Dependencies:** Pure HTML/CSS/JS. No npm, no build steps.
- **Theme Support:** Dark mode default, with a light mode toggle saving preference to `localStorage`.
- **Responsive:** Mobile-friendly layout wrapping properly on smaller screens.
- **Performant:** Intersection Observer for subtle scroll animations without hurting frame rates.
- **Semantics & SEO:** Uses Open Graph meta tags and semantic HTML5 elements.

## File Structure
- `index.html`: Main page content and structure.
- `styles.css`: All styling, including CSS variables for theme management.
- `script.js`: Theme toggle, smooth scrolling, active nav state, and scroll animations.
- `assets/favicon.svg`: Minimalistic SVG favicon.

## How to Deploy to GitHub Pages
1. Create a new repository on GitHub (e.g., `yuvraj-malik.github.io` or just `portfolio`).
2. Upload `index.html`, `styles.css`, `script.js`, `README.md`, and the `assets` folder directly to the `main` branch.
3. In your GitHub repository, go to **Settings > Pages**.
4. Under "Build and deployment", select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Wait 1-2 minutes. Your site will be live at `https://[username].github.io/` (or your custom domain if configured).
