# Said Elhefny — Software Developer Portfolio

**Live Website:** [XcharizardY.github.io](https://XcharizardY.github.io)

A personal portfolio website designed to mimic the interface of Visual Studio Code. This project was built entirely within a single HTML file to demonstrate clean architecture, utilizing embedded CSS and vanilla JavaScript without relying on any external libraries or frameworks (IBM Plex fonts are loaded from Google Fonts).

## Features
* **Interactive IDE Theme:** Features a functional file explorer sidebar and top tab navigation that switches between sections (`about.md`, `experience.md`, `education.md`, `projects.js`, `skills.json`, `contact.txt`).
* **Dynamic Gutter System:** Vanilla JavaScript is used to dynamically generate line numbers by measuring the rendered height of the active content section, and recalculating on resize and font load.
* **Responsive Design:** Automatically adapts to mobile and tablet screens by collapsing the file tree sidebar and adjusting layout padding.

## Tech Stack
* **Single-File Architecture:** The entire application is efficiently housed within one `index.html` file.
* **HTML5:** Semantic structure and custom SVG icons.
* **CSS3 (Embedded):** Flexbox, Grid, custom animations, responsive media queries, and CSS variables.
* **Vanilla JavaScript (Embedded):** DOM manipulation, state management, and event handling.

## Deployment
This repository is configured to deploy automatically via **GitHub Pages**.
