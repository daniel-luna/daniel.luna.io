# CV — Daniel Luna Camps

Static personal CV/portfolio site (Spanish). Vanilla HTML/CSS/JS — zero build tools or dependencies.

## Quick start

Open `index.html` in a browser (no server needed). Layout uses Google Fonts (Inter, JetBrains Mono) loaded from CDN.

## Architecture

Three files — no frameworks, no bundler, no package manager:

| File | Role |
|---|---|
| `index.html` | Content + structure (all Spanish) |
| `styles.css` | Dark theme, responsive, ~1000 lines |
| `script.js` | Sticky header, scroll reveal (IntersectionObserver), active nav, mobile menu, back-to-top |

## Notable

- Scroll-reveal is a ~20-line custom `IntersectionObserver` in `script.js`, not a library.
- Navigation uses `#` hash anchors — no router.
- Fully responsive (breakpoints at 900px, 768px, 480px).
- No test suite, no CI, no deployment config.
