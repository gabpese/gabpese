# Hi, I'm Gabriel Pesegoginski

**Full Stack Developer** · PHP, Ruby and TypeScript · Porto Alegre, Brazil (UTC-3)

I build web applications end to end: interface, back end, API and database. I came to software from architecture and technical drawing, which taught me to look at the product from the user's side and understand the business problem before writing code.

In my last role I worked on a desktop application (a SketchUp extension in Ruby) integrated with a PHP and MySQL web platform through a REST API. Some of that work:

- contributed to an automation that cut the preparation of component libraries from up to 2 years to about 5 days;
- implemented the telemetry collection for an APM, used to spot regressions by version before they reached support;
- refactored Ruby code with SOLID principles and documented business rules to support AI-assisted development.

## Featured projects

### [Singalong](https://github.com/gabpese/singalong) · [try it](https://singalong.duckdns.org) · [download the app](https://github.com/gabpese/singalong/releases/latest)

A self-hosted collaborative karaoke: guests queue songs from their phones, a TV plays the instrumental with word-by-word lyrics, and a worker turns any YouTube video into a karaoke track (vocal separation, synced lyrics, key change, pitch scoring, MP4 export).

- **Released and in use:** the web app for the TV and the phones, plus an installable app for Windows, macOS and Linux, shipped through GitHub Releases. The server runs at zero cost on a cloud VM with Docker Compose and Caddy.
- **Four apps in one monorepo:** React and Vite pages; a NestJS API on Fastify with MikroORM, SQLite, Redis and WebSocket rooms; a Python worker with PyTorch (Demucs for the vocals, stable-ts for the lyrics alignment); and an Electron desktop app.
- **Decisions on record:** 20 architecture decision records, every doc in English and Portuguese, and the interface in Portuguese, English and Spanish.
- **Tested on every pull request:** GitHub Actions runs the unit, API and end-to-end (Playwright) tests and builds the installers for the three systems.

### Mini APM, in two stacks

| Project | What it is | Stack |
| --- | --- | --- |
| [**mini-apm-laravel**](https://github.com/gabpese/mini-apm-laravel) · [live demo](https://mini-apm.onrender.com) | A small APM: apps send usage, error and crash events to a REST API, and a dashboard flags crash regressions by version | Laravel 13 · React 19 · TypeScript · Pest |
| [**mini-apm-rails**](https://github.com/gabpese/mini-apm-rails) | The same product and the same API contract, rebuilt in Ruby on Rails | Rails 8.1 · React 19 · TypeScript · PostgreSQL |

Same product, two stacks: both APIs accept the same JSON contract, so the JavaScript and Ruby clients work with either one.

## Tech stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/Rails-D30001?style=flat&logo=rubyonrails&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## Currently learning

Machine Learning, one lesson at a time and written by hand: [machine-learning-studies](https://github.com/gabpese/machine-learning-studies).

## Open to work

Full stack and back-end roles: remote, or hybrid in Porto Alegre. Native Portuguese, fluent English.

[LinkedIn](https://www.linkedin.com/in/gabrielpesegoginski/) · [gabrielpese.arq@gmail.com](mailto:gabrielpese.arq@gmail.com)
