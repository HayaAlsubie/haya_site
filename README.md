# Haya Alsubaie - Personal Portfolio

A fast, bilingual personal portfolio for Haya Ajab Alsubaie, a software engineer working on ERP and business systems with a background in databases, data science, and AI.

**Live site:** [hayaalsubie.github.io/haya_site](https://hayaalsubie.github.io/haya_site/)

## Highlights

- English default page and a matching Arabic RTL version
- Current professional experience in ERP and business systems
- Selected software, data, and AI work
- Responsive, dependency-free HTML and CSS
- Privacy-conscious contact options with no public phone number
- Downloadable one-page PDF resume

## Project structure

```text
.
├── index.html              # English portfolio
├── ar.html                 # Arabic portfolio
├── style.css               # Shared responsive design
└── assets/
    ├── avatar.png
    └── cv/haya_cv.pdf
```

## Run locally

No build step or package installation is required.

```bash
python -m http.server 8000
```

Open `http://localhost:8000` and use the language switch to review both versions.

## Deployment

The site is published with GitHub Pages from this repository. Changes should be reviewed on a feature branch before they are merged into `main`.
