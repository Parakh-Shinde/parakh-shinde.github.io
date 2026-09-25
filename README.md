# Parakh Shinde Security Engineering Portfolio

> Static GitHub Pages portfolio with a 3D animated profile experience, recruiter-focused cybersecurity positioning, and verified project evidence.

Live site: [parakh-shinde.github.io](https://parakh-shinde.github.io/)

## Overview

This repository hosts my public security-engineering portfolio. The site is built as a single static `index.html` file with embedded CSS and JavaScript, so it can be served directly by GitHub Pages without a build step.

The portfolio highlights AI Security, Red Team, Cloud IAM, Detection Engineering, SOC, and Incident Response work. Project claims are intentionally scoped to evidence available in the linked repositories.

## Implemented Features

- Responsive 3D profile hero with layered portrait depth, pointer tilt, idle motion, orbital rings, and wireframe cube animation
- Smooth section reveal animations and native anchor scrolling
- Motion on/off control with saved visitor preference
- Reduced-motion support for accessibility
- Keyboard-accessible mobile navigation with Escape handling and active-section tracking
- Recruiter-facing project cards for AegisForge, GCP IAMGraph, Automated LLM Vulnerability Assessment, AWS Cloud Security Monitoring, and AI SOC Triage
- No build system or external JavaScript framework required

## Repository Structure

| File | Purpose |
| --- | --- |
| `index.html` | Complete portfolio page, CSS, and JavaScript |
| `pic1111.jpg` | Portrait image used in the 3D profile section |
| `Parakh-Shinde--Resume.pdf` | Legacy resume asset; not linked from the live page until replaced with a verified current resume |
| `README.md` | Repository documentation |
| `README.txt` | Short plain-text project note |

## Local Preview

```bash
python -m http.server 8000
```

Open `http://localhost:8000` and review:

- Desktop and mobile layout
- Navigation and section anchors
- Motion on/off behavior
- Reduced-motion behavior
- Project and contact links

## Deployment

GitHub Pages serves the repository from:

```text
main / root
```

No build command is required. A commit to `main` updates the live site through GitHub Pages.

## Design Notes

The visual style is intentionally technical and restrained: dark interface, mint-green security accents, animated 3D profile treatment, dense project evidence, and minimal marketing copy. The page is meant to support job applications by making the strongest projects easy to inspect quickly.

## Responsible Positioning

All offensive-security and red-team style content linked from the portfolio is presented as isolated, authorized lab work. The portfolio avoids unsupported claims about production impact, certifications, or professional experience.
