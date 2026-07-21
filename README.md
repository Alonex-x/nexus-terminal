# Nexus Terminal

![Nexus Terminal](https://img.shields.io/badge/Nexus-Terminal-v2.6-9D00FF?style=flat-square)

Panel de control visual del **ecosistema Nexus**, un sistema de monitoreo y orquestación de agentes de software. Este repositorio contiene la interfaz de usuario, diseñada con estética CRT y visualización en tiempo real de agentes, misiones y eventos.

## Demo en vivo

Ver Nexus Terminal en acción: [https://alonex-x.github.io/nexus-terminal/](https://alonex-x.github.io/nexus-terminal/)

## Captura de pantalla

*(Pendiente de agregar: una captura del panel con los agentes activos.)*

## Conexión con el ecosistema

El **Nexus Terminal** es parte del ecosistema Nexus, que incluye:
- [Nexus Agent Management API](https://github.com/Alonex-x/nexus-agent-api) – Backend central (Java/Spring Boot).
- [Nexus Scraper](https://github.com/Alonex-x/nexus-scraper) – Agente de web scraping (Python/Playwright).
- Y más agentes en desarrollo.

Cuando se conecta a la API real, el panel refleja el estado en vivo de los agentes y permite interactuar con el ecosistema a través de una terminal integrada.

## Tecnologías

- HTML5, CSS3 (variables, animaciones, CRT tilt, scanlines)
- JavaScript vanilla (ES6, sin frameworks)
- Three.js (orbe 3D animado)
- Fuentes: JetBrains Mono, VT323 (Google Fonts)

---

Desarrollado por [@Alonex-x](https://github.com/Alonex-x). Proyecto educativo y de portafolio.
