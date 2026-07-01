# Personal Website

My personal portfolio website. A responsive single page site built with plain HTML, CSS, and JavaScript, hosted on GitHub Pages.

**Live:** [mohd-nour.github.io/personal-website](https://mohd-nour.github.io/personal-website/)

## Overview

The site presents who I am and what I have worked on, across six sections:

- **Home** with a short intro and social links
- **About** with a background summary and current tech
- **Skills** grouped by area (frontend, backend, cybersecurity, tools)
- **Qualifications** with an education and experience timeline
- **Projects** in a swipeable carousel
- **Contact** with a working message form

## Features

- Responsive layout that adapts from mobile to desktop
- Dark theme with a single accent color
- Projects carousel powered by Swiper
- Contact form powered by FormSubmit (no backend required)
- Downloadable resume

## Tech stack

HTML5, CSS3, and vanilla JavaScript. Swiper for the carousel and Unicons for icons. Fonts are Poppins and Syne from Google Fonts.

## Project structure

```
.
├── index.html
├── assets/
│   ├── css/
│   │   ├── styles.css
│   │   └── swiper-bundle.css
│   ├── js/
│   │   ├── index.js
│   │   └── swiper-bundle.min.js
│   └── images/
└── pdf/
    └── Nour-ElArab-Resume.pdf
```

## Run locally

The site is fully static, so no build step is needed. Serve the folder with any static server, for example:

```bash
npx serve
```

```bash
python -m http.server
```

Then open the address shown in your terminal.

## Deployment

Published with GitHub Pages from the `main` branch. Pushing to `main` updates the live site.

## License

Released under the [MIT License](LICENSE).
