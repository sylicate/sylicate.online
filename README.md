# SYLICATE // ARCHIVE


> A high-performance, brutalist, webcore inspired art portfolio with physics-based animations, parallax effects, and a custom geometric interface.

---

## :: SYSTEM_OVERVIEW

This project is a single-page portfolio website designed with a **Brutalist / Industrial** aesthetic. It utilizes basic Vanilla JavaScript, HTML, and CSS to create a visual experience with zero framework overhead.

The interface impersonates a futuristic terminal or archival system, utilizing a "Venn Diagram" loader, a physics-based scroll-to-unlock mechanism, and an interactable feed.

### [ LIVE DEMO ]
https://sylicate.online

## :: VISUAL_FEATURES

*   **Venn Diagram Loader:** A custom animation that simulates collision loading states with a snapping finish.
*   **Parallax Landing Page:** Multi-layered mouse-tracking depth effect featuring wires, and typography that reacts based on scroll velocity.
*   **Scroll-to-Decrypt:** A basic scroll-to-unlock mechanism that needs user interaction to redirect to the main archival log.
*   **Geometric UI:** CSS-based rotating circle and satellite orbit animations for the logo that moves according to the submenu selection.
*   **Light / Inverted Mode:** A theme toggle that inverts the color palette (Light/Dark mode).
*   **Noise Texture:** An SVG noise filter overlay for the grain texture.
*   **Custom Lightbox:** Pan and zoom image inspector.

## :: TECH_STACK

*   **Core:** HTML, CSS (CSS Variables for theming).
*   **Logic:** Vanilla JavaScript.
*   **Source:** JSON-based content injection (`fetch` API).
*   **Performance:** Native Lazy Loading, GPU-accelerated transforms (`will-change`), and requestAnimationFrame loops.


## :: CONFIGURATION
1. Image Database (data.json)
The archival log entries are populated automatically by data.json.

## :: MOBILE_OPTIMIZATION
Detecting mobile devices (width < 768px) and automatically:
Transforming the sidebar into a fixed top header.
Increasing touch area for buttons.
Accelerating the Venn Diagram animation (2.5x speed) for a faster mobile animation.
Simplifying the layout grid to a single column.

---
