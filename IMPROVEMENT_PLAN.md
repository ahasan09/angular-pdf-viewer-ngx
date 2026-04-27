# Improvement Plan: pdf-viewer-8

## Overview
Angular 8 + ngx-extended-pdf-viewer with an Express backend. Several major Angular versions behind current (19+). Limited features beyond basic PDF display.

## Improvements

### Modernization (High Priority)
- Upgrade from Angular 8 to Angular 19+
- Update `ngx-extended-pdf-viewer` to the latest version (the library has had major updates with Angular 19 support)
- Replace TSLint with ESLint + `@angular-eslint`
- Adopt standalone components and functional Angular APIs

### Features
- Add annotation support (highlight, underline, sticky notes) using ngx-extended-pdf-viewer's built-in toolbar
- Add text search within the PDF
- Add thumbnail panel for page navigation
- Add fullscreen mode
- Add download and print buttons
- Support loading PDFs from a URL, file upload, or base64

### Testing
- Add unit tests for the PDF loading service
- Add Playwright e2e tests verifying PDF rendering and navigation

### Code Quality
- Enable TypeScript `strict` mode
- Add proper error handling for failed PDF loads (corrupted file, network error, unsupported format)
- Add loading progress indicator

### DevOps
- Add a `Dockerfile` for the Express backend
- Add `docker-compose.yml` for running app + backend together
- Add GitHub Actions CI: lint + test + build
