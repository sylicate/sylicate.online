# SYLICATE // ARCHIVE


> A high-performance, brutalist art portfolio template featuring physics-based animations, parallax effects, and a custom geometric interface.

---

## :: SYSTEM_OVERVIEW

This project is a single-page immersive portfolio website designed with a **"True Black" / Industrial** aesthetic. It utilizes pure Vanilla JavaScript, HTML5, and CSS3 to create a heavy visual experience with zero framework overhead.

The interface mimics a futuristic terminal or archival system, featuring a "Venn Diagram" loader, a physics-based scroll-to-unlock mechanism, and a dynamic grid feed.

### [ LIVE DEMO ]
https://sylicate.online

## :: VISUAL_FEATURES

*   **Venn Loader Engine:** A custom mathematical animation that simulates fluid collision loading states with a snapping finish.
*   **Parallax Landing Zone:** Multi-layered mouse-tracking depth effect featuring wires, fluid blobs, and typography that distorts based on scroll velocity.
*   **Scroll-to-Decrypt:** A "shutter" mechanism that requires user interaction to unlock the main interface.
*   **Geometric UI:** CSS-driven rotating dials and "satellite" orbit animations for the logo.
*   **True Black / Inverted Mode:** A global theme toggle that inverts the color palette (Light/Dark mode).
*   **Noise Texture:** A procedural SVG noise filter overlay for film-grain texture.
*   **Custom Lightbox:** Pan-and-zoom image inspector with custom cursor states.

## :: TECH_STACK

*   **Core:** HTML5, CSS3 (CSS Variables for theming).
*   **Logic:** Vanilla JavaScript (ES6+).
*   **Data:** JSON-based content injection (`fetch` API).
*   **Performance:** Native Lazy Loading, GPU-accelerated transforms (`will-change`), and requestAnimationFrame loops.


## :: CONFIGURATION
1. The Art Database (data.json)
The gallery feed is populated automatically by data.json.

## :: MOBILE_OPTIMIZATION
The system detects mobile devices (width < 768px) and automatically:
Transforms the sidebar into a fixed top/bottom header.
Increases touch targets for buttons.
Accelerates the boot/loader animation (2.5x speed) for faster mobile UX.
Simplifies the layout grid to a single column.

---
