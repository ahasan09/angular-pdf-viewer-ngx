# Angular PDF Viewer (ngx-extended-pdf-viewer)

An Angular application that renders PDF files in the browser using `ngx-extended-pdf-viewer`. Includes an optional Express server for production serving.

## Features

- In-browser PDF rendering using `ngx-extended-pdf-viewer`
- Customer document viewer UI
- Express server for serving the production build

## Tech Stack

- Angular (CLI v8.0.6)
- TypeScript
- ngx-extended-pdf-viewer
- Express.js

## Prerequisites

- [Node.js](https://nodejs.org/) v12+
- Angular CLI: `npm install -g @angular/cli`

## Getting Started

```bash
git clone https://github.com/ahasan09/angular-pdf-viewer-ngx
cd angular-pdf-viewer-ngx
npm install
ng serve
```

Open [http://localhost:4200](http://localhost:4200).

## Commands

| Command | Description |
|---------|-------------|
| `ng serve` | Start Angular dev server on port 4200 |
| `ng build --prod` | Production build to `dist/` |
| `node server.js` | Serve the production build with Express |
| `ng test` | Run unit tests (Karma) |

## Project Structure

```
src/app/
├── pdfviewer/    # PDF viewer component
├── customers/    # Customer document list
├── shared/       # Shared components
└── common/       # Common utilities
```
