# CS-499 ePortfolio (GitHub Pages)

This repository contains my SNHU **Computer Science Capstone (CS‑499)** ePortfolio.  
The site is built with **GitHub Pages** (Cayman theme) and published from the repository **root**.

## Structure
```
/ (root)
  |_ index.md                 # Professional self-assessment + nav (homepage)
  |_ code-review.md           # Code review video link/embed
  |_ artifacts/
      |_ artifact1.md         # Software Engineering & Design
      |_ artifact2.md         # Algorithms & Data Structures
      |_ artifact3.md         # Databases
  |_ code/
      |_ original/README.md   # Put original source code here
      |_ enhanced/README.md   # Put enhanced source code here
  |_ media/
      |_ screenshots/         # Any images you want to show on pages
  |_ _config.yml              # GitHub Pages theme + metadata
```
## How to publish
1. Commit this repository to GitHub.
2. On GitHub: **Settings → Pages → Build and deployment**  
   Source: `main` branch, Folder: `/ (root)` → Save.
3. Open the public URL shown on the Pages settings panel.

## Notes
- Prefer **relative links** in Markdown.
- For large videos, upload to YouTube as **Unlisted** and link from `code-review.md`.
