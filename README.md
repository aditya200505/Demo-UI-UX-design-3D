# Demo UI/UX Design 3D

A small collection of standalone, motion-led web design demos. The project pairs a cinematic planetary learning interface with a 3D studio showcase driven by a scroll-scrubbed render reel.

## Pages

### SpaceEdu: Planet Exploration

Open [`index.html`](index.html) for the SpaceEdu experience. It features an animated planetary landing screen, Earth/Venus/Mars switching, and interactive course and planet details.

### Cast & Render: 3D Object Studio

Open [`cast-render.html`](cast-render.html) for the Cast & Render studio showcase. Scrolling scrubs a full-screen video while three editorial copy panels fade in and out. The page includes a loading state, progress meter, responsive navigation, and mobile safe-area support.

## Run locally

No build step, package install, framework, or development server is required. Open either HTML file directly in a modern browser. The pages load fonts and media from external hosts, so an internet connection is needed for the complete visual experience.

## Implementation

- Plain HTML, CSS, and JavaScript
- Each experience is self-contained in its HTML file
- Responsive layouts and reduced setup requirements
- Cast & Render preloads the video as a blob when possible, with direct streaming fallback

## Repository layout

```text
.
├── index.html       # SpaceEdu planetary experience
├── cast-render.html # Cast & Render scroll-scrub showcase
└── README.md
```
