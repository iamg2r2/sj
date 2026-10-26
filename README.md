# Teacher Tools

A simple GitHub Pages landing page for two classroom tools.

## Files
- `index.html` — homepage / tool launcher
- `abc-animal-journey.html` — ABC Animal Journey
- `hibiscus-dissection-lab.html` — Hibiscus Dissection Lab

## Publish on GitHub Pages
1. Create a new GitHub repository (for example, `teacher-tools`).
2. Upload the three HTML files from this folder to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish. Open the URL GitHub shows; it should load `index.html`.
7. The two cards on the homepage open the corresponding tools.

## Notes
- Keep all three HTML files in the same folder at the repository root so the relative links work.
- Hibiscus Dissection Lab imports Three.js from jsDelivr, so it needs an internet connection.
- No build step or framework is required.
