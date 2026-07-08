# CERAI — Civilian Evacuation Risk Anticipation Index

CERAI is a research prototype for anticipating civilian risk during evacuation
operations in armed conflict. It combines multi-category risk indicators
(hazards, infrastructure, population vulnerability, information environment,
weather, and more) into a composite index with Monte Carlo sensitivity
analysis, intended to support International Humanitarian Law (IHL) compliance
review and humanitarian planning.

**Live demo:** https://alanarobertson.github.io/Evac-AI-Project-2-/

> ⚠️ Research prototype. Outputs are indicative and not a substitute for
> operational decision-making or legal advice.

## What it does

- Interactive scoring across weighted risk categories
- Composite risk gauge with confidence bar
- Monte Carlo sensitivity analysis over uncertain inputs
- Location geocoding, weather integration, and ACLED conflict-event lookup
- Source credibility and data-freshness tagging for each indicator

## Running locally

The app is a single-file HTML prototype. Either:

- Open `index.html` directly in a browser, or
- Serve the directory: `python3 -m http.server 8000` then visit
  `http://localhost:8000/`.

## GitHub Pages

`index.html` at the repo root is served by GitHub Pages. To enable:

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root → **Save**

## Context

Developed as part of PhD research at NYU School of Law on IHL and AI,
with the aim of making evacuation-risk reasoning more transparent and
auditable for humanitarian and legal audiences (UN, ICRC).

## License

All rights reserved unless otherwise noted. Contact the author before reuse.
