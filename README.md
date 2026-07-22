# Nexus Terminal

![Nexus Terminal](https://img.shields.io/badge/Nexus-Terminal-v2.6-9D00FF?style=flat-square)

Visual control panel for the Nexus ecosystem, a monitoring and orchestration system for software agents. This repository contains the user interface, designed with CRT aesthetics and real-time visualization of agents, missions, and events.

## Live Demo

See Nexus Terminal in action: https://alonex-x.github.io/nexus-terminal/

## Demo

[Watch the demo video](demos/demo-nexus-terminal.mp4)

## Connection to the Ecosystem

Nexus Terminal is part of the Nexus ecosystem, which includes:
- Nexus Agent Management API (Java/Spring Boot)
- Nexus Scraper (Python/Playwright)
- And more agents under development.

When connected to the real API, the panel reflects the live status of agents and allows interaction with the ecosystem through an integrated terminal.

Note: This project is a Single Page Application (SPA) contained in a single HTML file by design. All logic, styles, and 3D rendering reside in index.html without framework dependencies.

## Technologies

- HTML5, CSS3 (variables, animations, CRT tilt, scanlines)
- Vanilla JavaScript (ES6, no frameworks)
- Three.js (animated 3D orb)
- Fonts: JetBrains Mono, VT323 (Google Fonts)

---

Developed by @Alonex-x. Educational and portfolio project.

