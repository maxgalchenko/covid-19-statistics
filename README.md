# COVID-19 Statistics

<div align="center">

[![React](https://img.shields.io/badge/React-17-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![Create React App](https://img.shields.io/badge/Create%20React%20App-4.0.1-09D3AC?style=for-the-badge&logo=react&logoColor=white)](https://create-react-app.dev/)
[![Material UI](https://img.shields.io/badge/MUI-4.11-0081CB?style=for-the-badge&logo=mui&logoColor=white)](https://v4.mui.com/)
[![Leaflet](https://img.shields.io/badge/Leaflet-1.7.1-199900?style=for-the-badge&logo=leaflet&logoColor=white)](https://leafletjs.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-2.9.4-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.17.0-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

</div>

## Overview

Interactive COVID‑19 tracker dashboard showing global and country‑level statistics. Features live case counts, a choropleth map, and historical trends using public data from `disease.sh`.

## Key Features

- Global and per‑country stats with quick country selector
- Interactive Leaflet map with case density visualization
- Historical line charts for cases, recoveries, and deaths

## Tech Stack

React 17, Create React App 4, Material‑UI v4, Leaflet, Chart.js, Numeral.js

## Architecture

SPA built with CRA. Data fetched from `disease.sh` REST endpoints. State managed with React hooks across components: `InfoBox`, `Map`, `Table`, `LineGraph`.

## Performance & Accessibility

CRA optimizations and React 17 rendering; semantic HTML and keyboard‑navigable controls where applicable.

## Quality

- Linting: react-app ESLint • Formatting: N/A
- Type safety: N/A (JavaScript)
- Tests: CRA defaults (Jest + React Testing Library)
- CI: none

## Prerequisites

- Node.js: `18.20.3`

## Installation

```bash
git clone https://github.com/maxgalchenko/covid-19-statistics.git
cd covid-19-statistics
npm install
```

## Quick Start

```bash
npm start
# Production
npm run build
```

Open http://localhost:3000

## Available Scripts

- `npm start` – Run the development server at http://localhost:3000
- `npm run build` – Create an optimized production build in `build/`
- `npm test` – Run tests in watch mode (Jest + RTL via CRA)
- `npm run eject` – Eject CRA configuration (one‑way operation)

## Screenshots

![Dashboard](./public/screenshots/screenshot-01.png)

![Map & Trends](./public/screenshots/screenshot-02.png)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
