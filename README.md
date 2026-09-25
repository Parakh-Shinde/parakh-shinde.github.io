# Parakh Shinde — Security Engineering Portfolio

An animated, responsive portfolio for GitHub Pages. Open `index.html` directly or serve this directory with any static HTTP server. No build step is required.

## Files

- `index.html` — the complete page, CSS and JavaScript
- `pic1111.jpg` — the existing portrait
- `Parakh-Shinde--Resume.pdf` — legacy resume asset; currently not linked by the page

## Motion and interactions

- Gently floating portrait with pointer-based tilt and a moving highlight on supported devices
- Subtle orbital graphics, animated lab trace and scrolling topic strip
- Staggered section reveals, smooth anchor scrolling and hover effects
- Responsive navigation with keyboard access, Escape handling and active section indication
- A **Motion on/off** button that remembers the visitor's preference
- Reduced-motion system settings respected by default; content and navigation remain available without JavaScript

Animations use CSS, IntersectionObserver, requestAnimationFrame and the Web Animations API. No external JavaScript libraries are required. Google Fonts are optional; the page includes system-font fallbacks.

## Content

Featured work: AegisForge, GCP-IAMGraph, Automated LLM Vulnerability Assessment, AWS Cloud Security Monitoring, and Enterprise SOC Monitoring. Project claims are scoped to the documented repositories and lab results. Replace the legacy resume with a verified current version before restoring a resume link.

## Local preview

```sh
python -m http.server 8000
```

Open `http://localhost:8000`. Check the desktop and mobile layouts, navigation, and both motion settings.

## GitHub Pages

Repository **Settings → Pages → Deploy from a branch → main → / (root)**.

Live address: https://parakh-shinde.github.io/
