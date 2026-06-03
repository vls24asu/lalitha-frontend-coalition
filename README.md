# Tech.Care : Patient Dashboard (Coalition Tech Skills Test)

Single-page React app that fetches and renders patient data for Jessica Taylor from the Coalition Technologies Patient Data API.

## Prerequisites

- Node.js 20+
- npm 10+

## Install

```sh
npm install
```

## Run

```sh
npm run dev          # http://localhost:5173
npm run build        # production build into dist/
npm run preview      # serve the built bundle
npm run check        # type-check + lint + format check
```

## Stack

React 18 · TypeScript 5 · Vite 5 · CSS Modules · Chart.js (via react-chartjs-2) · vite-plugin-svgr.

## Scope notes

- Renders only Jessica Taylor's data in the profile/diagnosis/lab sections (per the brief).
- The patient list shows all API patients to match the design.
- Out of scope per the brief: search submit logic, gear icon dropdown, sidebar ellipsis menus, patient switching, lab download behavior, responsive/mobile layouts.
