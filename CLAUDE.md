# PDF Viewer 8

Angular 8 application for viewing PDFs using `ngx-extended-pdf-viewer` with Angular Material UI and an Express backend.

## Tech Stack
- Angular 8
- ngx-extended-pdf-viewer
- Angular Material
- Express (backend)
- TypeScript

## Project Structure
```
pdf-viewer-8/
├── src/
│   └── app/
├── server.js            # Express backend
├── angular.json
└── package.json
```

## Development
```bash
# Install dependencies
npm install

# Run Angular dev server
ng serve

# Run Express backend
node server.js
```

## Key Notes
- `ngx-extended-pdf-viewer` wraps Mozilla's PDF.js for in-browser PDF rendering.
