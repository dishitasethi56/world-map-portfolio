# Dishita Sethi — World Map Portfolio

A fantasy-map portfolio built with React + Vite + TypeScript. The map has four regions and twelve résumé-based story landmarks. These are honest student activities, volunteering, creative experiences, and academic highlights—not invented client or design case studies.


## Run locally

```bash
npm install
npm run dev
```

## Customize content
Edit `src/data.ts` to change region and landmark data. Each landmark panel includes a summary, role, year, areas of focus, story text, optional image URLs, and optional external link. Add real images only when you have them; empty galleries are intentionally represented as résumé-story panels.


## Controls
- Drag the map to pan
- Scroll to zoom toward the cursor
- `+` / `−` and Home buttons
- Fast Travel fly-to region menu
- List view for quick recruiter browsing
- Click landmarks for detail panels; arrows cycle within a region
- `Esc` closes a panel
- Discovered landmarks persist in localStorage and update the progress counter
- Direct links use `#landmark-id`


## Map art
The map artwork is inline SVG in `src/main.tsx`, styled with CSS. Replace terrain SVG or add custom map art while preserving the 4000 × 3000 coordinate space.


## Regions
- Leadership Grove: Organica Club activities and workshop/exhibition experience
- Kindness Coast: Art Club social contribution and peer-support experience
- Creative Highlands: Graphics volunteer and creative/certificate activities
- Scholar’s Archive: Olympiads, awards, and school/college education highlights


## Notes
Frontend only; no backend. Current camera supports pointer drag, wheel zoom, clamping, fast travel, minimap navigation, reduced-motion flights, and responsive bottom-sheet panels. Pinch gestures, momentum/inertia, and a full focus trap remain polish items.
