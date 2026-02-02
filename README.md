# dannyrusen.github.io
## Personal Website

This repo hosts a minimal professional website with a photo and links to email and CV.

### Quick Start
- Open [index.html](index.html) directly in a browser, or serve locally:

```bash
cd /Users/dannyrusen/Workspace/Personal/Code/dannyrusen.github.io
python3 -m http.server 8000
open http://localhost:8000
```

### Customize
- Photo: add your headshot at [assets/profile.jpg](assets/profile.jpg).
- CV: place your PDF at [assets/cv.pdf](assets/cv.pdf).
- Email: update the `mailto:` link in [index.html](index.html) to your address.

### Files
- [index.html](index.html): Main page with your name, photo, and links.
- [styles.css](styles.css): Styling (dark/light friendly, accessible).
- [assets/placeholder.svg](assets/placeholder.svg): Fallback image used until `profile.jpg` exists.

Deploy to GitHub Pages by pushing to `main` and enabling Pages in repo settings.
