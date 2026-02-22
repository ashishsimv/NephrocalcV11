# NephroCalc Pro v10.1

Clinical Nephrology Decision Support Tool

## Stats
- 60 validated calculators + 10 reference panels = 70 tools
- 18 clinical sections
- 52 Category A (published validated equations with exact coefficients)
- 8 Category B (guideline-based, tagged with warning)
- 10 [REF] panels (published criteria, no computed score)

## Tech Stack
- React 18 (single-file app in src/App.jsx)
- No external CSS — all styles inline
- No backend — fully client-side

## Setup (for developer)
```bash
npm install
npm start
```
Opens at http://localhost:3000

## Build for Production
```bash
npm run build
```
Output in /build folder — deploy to Cloudflare Pages, Vercel, or any static host.

## Deployment Notes
- Deploy as PWA (manifest.json included)
- Add access code gate before disclaimer screen
- App icons (icon-192.png, icon-512.png) need to be created and placed in /public

## Author
Dr. Ashish Patel

## License
Private — All rights reserved
