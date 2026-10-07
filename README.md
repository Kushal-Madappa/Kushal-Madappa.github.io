# Kushal Madappa — Portfolio

Personal portfolio site, live at **[kushal-madappa.github.io](https://kushal-madappa.github.io)**.

I'm an MSc Data & Computational Science student at University College Dublin, working on machine learning, statistics and backend engineering. The site covers my experience, projects, my Springer publication (Best Paper, ICACECS 2025), skills and education.

## How it's built

- A single self-contained `index.html` with no framework and no build step
- Hand-written HTML, CSS and vanilla JavaScript
- The hero plot fits a Nadaraya–Watson kernel regression to randomly sampled data, live in the browser
- Responsive layout that follows the visitor's light or dark mode, and respects reduced-motion settings
- Hosted on GitHub Pages; `.nojekyll` serves the files as-is

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site |
| `cv.pdf` | CV linked from the "Download CV" button |
| `.nojekyll` | Turns off GitHub's Jekyll processing |

## Run locally

```bash
git clone https://github.com/Kushal-Madappa/Kushal-Madappa.github.io.git
cd Kushal-Madappa.github.io
python3 -m http.server 8000
# then open http://localhost:8000
```

## Contact

[LinkedIn](https://linkedin.com/in/kushal-madappa) · [Email](mailto:kushalmadappa19@gmail.com)
