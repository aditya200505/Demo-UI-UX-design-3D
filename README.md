<div align="center">

# Demo UI/UX Design 3D

[![Animated project tagline](https://readme-typing-svg.demolab.com?font=Inter+Tight&weight=500&size=27&pause=850&color=0D0C0B&center=true&vCenter=true&width=760&height=58&lines=Scroll.+Scrub.+See+the+render.;Planets,+pixels,+and+playful+interfaces.;Two+little+web+worlds,+one+studio.)](https://github.com/aditya200505/Demo-UI-UX-design-3D)

**A pair of motion-led web experiments. Pick a world and take a look around.**

[SpaceEdu source](index.html) &nbsp; | &nbsp; [Cast & Render source](cast-render.html)

![HTML](https://img.shields.io/badge/HTML-self--contained-e76f51?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-responsive-457b9d?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-no%20framework-f4a261?style=flat-square)

</div>

## Choose your scene

| Experience | What's happening |
| --- | --- |
| [SpaceEdu](index.html) | Tour Earth, Venus, and Mars through an animated planetary interface, with interactive planet details and course panels. |
| [Cast & Render](cast-render.html) | Scroll through a 3D studio reel: the page stays in place while scrolling scrubs the video and the studio's story fades between three scenes. |

## The fun bits

- **Scroll becomes a timeline.** Cast & Render eases the video toward the frame that matches your scroll position.
- **Three scenes, one canvas.** Copy fades in and out over the fixed footage, with quiet video-only beats between panels.
- **A tiny planet switchboard.** SpaceEdu lets you switch between three worlds and explore their details.
- **Made to fit.** Both interfaces adapt to smaller screens; Cast & Render also accounts for mobile safe areas.

## Take it for a spin

No install, build step, framework, or server needed. Open either HTML file in a modern browser. Fonts, video, and some image assets load from external hosts, so connect to the internet for the full experience.

## Under the hood

Just HTML, CSS, and JavaScript. Each page keeps its styles and scripts in the page itself. Cast & Render tries to buffer the video for responsive seeking and falls back to direct streaming if that is unavailable.

```text
.
├── index.html        # SpaceEdu: planetary interface
├── cast-render.html  # Cast & Render: scroll-scrub studio reel
└── README.md         # You are here
```
