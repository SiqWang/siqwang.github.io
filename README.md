# Simple Personal Site

A minimal one-page-first personal website with:
- **Index (main)**: About + Projects overview (cards link to detail pages).
- **Publications**: separate page.
- **CV**: separate page with intro, education, skills, and a button to open `assets/cv.pdf`.
- **Top nav** on every page: About, Projects, Publications, CV.
- **Page views** (per-page) via Busuanzi (can swap for GoatCounter).

## How to use
1. Open `index.html` locally or host the folder (e.g., GitHub Pages, Netlify).
2. Replace text and images in `assets/`.
   - Put your actual CV at `assets/cv.pdf`.
   - Replace `assets/project-*.jpg` with real images (PNG/JPG/TIFF/etc.).
3. Add projects:
   - Duplicate a `project-X.html`, rename, and update the link and image in `index.html`.
4. Publications: edit `publications.html` list items.
5. Branding: change "Your Name" in the header of each HTML file (search/replace).

## Deploy
- **GitHub Pages**: create a repo, push this folder, enable Pages from the `main` branch. Your site will be live at `https://<username>.github.io/<repo>`.
- **Netlify/Vercel**: drag-and-drop this folder to the dashboard.

## Page views
- Busuanzi counts per-page views after the site is online. The counter shows in the footer.
- If you prefer, remove the Busuanzi `<script>` and integrate [GoatCounter] instead (insert their `count.js` in the `<head>`).

## License
MIT—do whatever you like. Attribution appreciated.
