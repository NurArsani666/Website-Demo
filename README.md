# Website-Demo
# Harbor Health Mission — Nonprofit Website Concept

**Live demo:** _add your GitHub Pages link here once it's live_

## Overview

A front-end concept for a fictional community health nonprofit, built to demonstrate the kind of update a WordPress-based nonprofit site (like a mobile clinic organization) could use: a warmer visual identity, clearer navigation, and interactive elements that help visitors actually find and use the site's information — not just read it.

This is a static HTML/CSS/JS build — no framework, no backend, no build step. It's meant to be viewed as a UI/UX and front-end coding sample, not a production CMS.

## The brief I designed against

Nonprofits that rely on outreach — clinics, food banks, mobile services — usually need a site to do three things well:

1. Help a visitor immediately understand who the organization serves and how
2. Make it easy to find practical, time-sensitive information (where, when, how to get help)
3. Convert visitors into volunteers or donors without friction

I designed every section around one of those three jobs.

## Design decisions

- **Palette:** a seafoam/teal base with a warm gold accent, instead of a generic dark-mode or beige-and-terracotta template look — chosen to feel like healthcare + coast, not "generic SaaS."
- **Typography:** Fraunces (serif, warm, a little unconventional) for headlines paired with Public Sans for body text, giving the page personality without sacrificing readability.
- **Layout:** an asymmetric hero (copy + a functional-looking clinic finder widget) instead of a centered hero graphic, so the first thing a visitor sees is something they can actually use.

## Front-end features demonstrated

- **Responsive layout** — from desktop down to mobile, including a collapsing hamburger nav
- **Interactive components built from scratch in vanilla JS:**
  - Zip-code clinic finder (demo interaction)
  - Tabbed program browser with full keyboard support (arrow-key navigation, proper ARIA roles)
  - Testimonial carousel with dot navigation
  - Accordion-style FAQ using native `<details>`/`<summary>`
- **Accessibility basics** — skip-to-content link, visible focus states on every interactive element, semantic HTML, `aria-live` regions, and respect for `prefers-reduced-motion`
- **No dependencies** — a single HTML file with embedded CSS and JS, so it's easy to read, deploy, and hand off

## Tech

HTML5, CSS3 (custom properties, no framework), vanilla JavaScript. Fonts loaded from Google Fonts.

## Why I built this

I'm applying to volunteer on front-end updates for a nonprofit's WordPress site, and wanted a work sample that showed the same priorities that project needs: a modern, accessible, mobile-friendly redesign with real interactivity — not just a static mockup.
