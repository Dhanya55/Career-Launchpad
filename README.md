# Career Launchpad

A career-focused landing page and program website designed to help students and professionals explore opportunities, learn through projects, and connect with mentors and hiring partners.

## Overview

This repository contains a static website built with HTML, CSS, and JavaScript. The project presents multiple career tracks, internship paths, and placement support programs in a clean, conversion-focused layout.

## What is included

- Career landing page with hero section and CTA
- Program overview cards
- Form sections for students, colleges, and companies
- Branding assets and marketing imagery
- Documentation for repo organization and maintenance

## Quick start

To preview the site locally:

1. Open the original static page in the legacy folder, or
2. Serve the repository with a simple local web server:

```bash
python3 -m http.server 8000
```

Then open:

- http://localhost:8000/

## Repository structure

```text
Career-Launchpad/
├── README.md
├── docs/
│   └── structure.md
├── pages/
│   └── README.md
├── assets/
│   └── README.md
├── legacy/
│   └── README.md
├── Career Launchpad/
│   └── legacy static site files and assets
└── .gitignore
```

## Notes

- The original website files remain under `Career Launchpad/` to preserve compatibility.
- The new structure organizes future work into `pages/`, `assets/`, and `docs/`.
- This is a static project, so no framework build step is required.

## Suggested next improvements

- Split the page into reusable components or templates
- Move all images into `assets/images/`
- Convert repeated sections into shared CSS or includes
- Add a contact form backend or CRM integration
- Add deployment instructions for GitHub Pages or Netlify
