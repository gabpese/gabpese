# Hi, I'm Gabriel Pesegoginski

**Full Stack Developer** · PHP, Ruby and TypeScript · Porto Alegre, Brazil (UTC-3)

I build web applications end to end: interface, back end, API and database. I came to software from architecture and technical drawing, which taught me to look at the product from the user's side and understand the business problem before writing code. What I like most is turning slow, manual processes into software that really solves the problem.

## Experience

At **Gabster**, a SaaS platform for the furniture industry (from 3D design to pricing and CNC production), I started as a 3D modeler and moved to the development team at my own request.

**Full Stack Developer** · Jun 2025 – Sep 2026 · a SketchUp extension in Ruby integrated with a PHP and MySQL web platform through a REST API

- Built the prototype components and the download-time personalization that tailor one master component library to each client's engineering rules. It was replicated into 40+ client libraries of about 500 components each, and preparing one dropped from up to 2 years to about 5 days.
- Built the extension's telemetry (feature usage, errors, version, operating system, GPU and RAM, sent to Elastic). Cross-referenced with the crash reports, it caught per-version regressions before they reached support.
- Moved business rules hard-coded in the extension into platform settings, in Ruby and PHP, so a new rule no longer needs a new release.
- Refactored the Ruby code with SOLID principles and used Claude Code to document the business rules and a code map, so anyone on the team could work on the repository with AI assistance.

**3D Modeler** · Jun 2024 – Jun 2025

- Created a way to generate DXF and CNC drilling straight from parametric SketchUp components, which cut a drilling component from about 28 days to about 5 and earned the company's Outstanding Performer award (Destaque Fora da Curva, July 2025).
- Trained 12 people, about 90% of the team, on the app, the platform and the modeling tools; a new modeler's full training dropped from about 6 months to about 3.

Before Gabster: six years as a technical and architectural drafter (2018–2024).

## Featured projects

### [Singalong](https://github.com/gabpese/singalong) · [try it](https://singalong.duckdns.org) · [download the app](https://github.com/gabpese/singalong/releases/latest)

A self-hosted collaborative karaoke: guests queue songs from their phones, a TV plays the instrumental with word-by-word lyrics, and a worker turns any YouTube video into a karaoke track (vocal separation, synced lyrics, key change, pitch scoring, MP4 export).

- **Released and in use:** the web app for the TV and the phones, plus an installable app for Windows, macOS and Linux, shipped through GitHub Releases. The server runs at zero cost on a cloud VM with Docker Compose and Caddy.
- **Four apps in one monorepo:** React and Vite pages; a NestJS API on Fastify with MikroORM, SQLite, Redis and WebSocket rooms; a Python worker with PyTorch (Demucs for the vocals, stable-ts for the lyrics alignment); and an Electron desktop app.
- **Decisions on record:** 20 architecture decision records, every doc in English and Portuguese, and the interface in Portuguese, English and Spanish.
- **Tested on every pull request:** GitHub Actions runs the unit, API and end-to-end (Playwright) tests and builds the installers for the three systems.

### Mini APM, in two stacks

A public, from-scratch version of the telemetry work from Gabster, built around an invented application.

| Project | What it is | Stack |
| --- | --- | --- |
| [**mini-apm-laravel**](https://github.com/gabpese/mini-apm-laravel) · [live demo](https://mini-apm.onrender.com) | A small APM: apps send usage, error and crash events to a REST API, and a dashboard flags crash regressions by version | Laravel 13 · React 19 · TypeScript · Pest |
| [**mini-apm-rails**](https://github.com/gabpese/mini-apm-rails) | The same product and the same API contract, rebuilt in Ruby on Rails | Rails 8.1 · React 19 · TypeScript · PostgreSQL |

Same product, two stacks: both APIs accept the same JSON contract, so the JavaScript and Ruby clients work with either one.

## Tech stack

**At work**

![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)
![SketchUp](https://img.shields.io/badge/SketchUp_Ruby_API-005F9E?style=flat&logo=sketchup&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat&logo=elastic&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**In my projects**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-D30001?style=flat&logo=rubyonrails&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## Currently learning

Machine Learning, one lesson at a time and written by hand: [machine-learning-studies](https://github.com/gabpese/machine-learning-studies).

## Open to work

Available now for full stack and back-end roles: remote (companies abroad included), or hybrid in Porto Alegre. Native Portuguese, fluent English.

[LinkedIn](https://www.linkedin.com/in/gabrielpesegoginski/) · [gabrielpese.arq@gmail.com](mailto:gabrielpese.arq@gmail.com)
