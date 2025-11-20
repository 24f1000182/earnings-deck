# earnings-deck — Reveal.js Quarterly Earnings Presentation

This repository contains an interactive Reveal.js presentation for the quarterly earnings report.

Files added:

- `index.html` — Reveal.js presentation (Markdown slide, fragments, code sample, math, speaker notes).

How to publish on GitHub Pages

1. Commit the new files and push to the `main` branch:

```bash
git add index.html README.md
git commit -m "Add Reveal.js earnings presentation"
git push origin main
```

2. Open the repository on GitHub, go to Settings → Pages, and ensure the site is served from the `main` branch (root). For user/organization Pages the URL will be:

```
https://24f1000182.github.io/earnings-deck/
```

3. After a short delay (a minute or two) the site should be live. If you prefer, you can enable Pages from branch settings or use a GitHub Actions workflow.

Viewing the presentation locally

You can also open `index.html` in a browser for a quick preview. For full plugin functionality (math highlighting), hosting via HTTP is recommended (simple local server):

```bash
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

Contact

24f1000182@ds.study.iitm.ac.in
# earnings-deck