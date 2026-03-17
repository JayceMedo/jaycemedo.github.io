# jaycemedo.github.io

Local development setup for this static site.

## Requirements
- Node.js 20+
- npm

## Setup
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the local dev server (with auto-reload):
   ```bash
   npm run dev
   ```
3. Open:
   - http://127.0.0.1:5500/

## Alternative (no browser auto-open)
```bash
npm run dev:no-browser
```

## Notes
- This is a static site (`index.html`, `style.css`, etc.), so no build step is required.
- `live-server` watches files and reloads the page when you save changes.
