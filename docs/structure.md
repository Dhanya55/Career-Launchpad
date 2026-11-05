# Project structure

This repository was organized to separate the marketing website, reusable assets, and documentation.

## Current layout

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
│   └── original static files (kept for compatibility)
└── .gitignore
```

## Organization goals

- Keep the root clean and user-friendly
- Separate content and design assets from source files
- Preserve the original implementation while enabling easier maintenance
- Prepare the project for future expansion and modularization

## Recommended future structure

```text
Career-Launchpad/
├── README.md
├── assets/
│   ├── images/
│   ├── icons/
│   └── branding/
├── pages/
│   ├── home.html
│   ├── career-starter.html
│   ├── junior-career.html
│   ├── internships.html
│   ├── experienced.html
│   └── schedule-call.html
├── styles/
│   └── main.css
├── scripts/
│   └── main.js
├── docs/
│   └── content-notes.md
└── legacy/
    └── archived-static-files/
```

This structure is a clean target for future refactors without breaking the current static website.
