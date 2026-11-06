# Gatherly — Event Management Website

A responsive event discovery and registration website built with **HTML5, CSS3 and vanilla JavaScript**.

## Features

- Responsive layout for desktop, tablet and mobile screens
- Hero section, featured events, about section and footer
- Six sample events with date, venue, category, image and description
- Live event search and category filters
- Event detail modal with registration call-to-action
- Registration form with JavaScript validation for name, email and Indian mobile number
- Successful registration confirmation
- Registrations stored in browser `localStorage`
- Dark/light theme toggle (preference is remembered)
- Mobile navigation, keyboard shortcuts (`Ctrl/Cmd + K`) and Escape-to-close modals

## Project structure

```text
event-management-website/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Run locally

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`, or use the VS Code **Live Server** extension.

No build tools or package installation are required.

## Deploy with GitHub Pages

1. Create a new public repository on GitHub, for example `gatherly-event-management`.
2. Upload `index.html`, `style.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish. Your website URL will appear in the Pages section and usually looks like:
   `https://YOUR-USERNAME.github.io/gatherly-event-management/`

## Git commands

Run these commands inside the project folder after creating your empty GitHub repository:

```bash
git init
git add .
git commit -m "Build Gatherly event management website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/gatherly-event-management.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and use the repository URL GitHub gives you.

## Demo data and limitations

The events are sample/demo content. Registration records are stored only in the visitor's browser using `localStorage`; this project does not include a backend, database, payment gateway or email service. The confirmation shown on submission is a front-end demo confirmation, not an email or externally verified booking.

Event photos are loaded from Unsplash and Google Fonts are loaded from Google Fonts, so those visual assets require an internet connection.
Website deployment verification — Gatherly 2026.
## Technologies

- HTML5 — semantic page structure and forms
- CSS3 — responsive grid/flex layouts, transitions, theme variables and media queries
- JavaScript — event rendering, filtering, validation, modals and local storage
- Git/GitHub — version control and hosting
