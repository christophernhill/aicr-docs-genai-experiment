# Agent Instructions -- production repository

This is the **production repository** in the three-repository MkDocs documentation
architecture. It acts as a hosting bucket for GitHub Pages.

## Purpose

Contains only compiled HTML/CSS/JS output. No source files, no build configuration,
no workflows. All content is pushed here by CI workflows running in the edit repository.

## Contents

- `docs/` -- Built site output served by GitHub Pages
- `docs/.nojekyll` -- Disables Jekyll processing
- `docs/CNAME` -- Custom domain (delete if not using a custom domain)
- `docs/index.html` -- Placeholder page (replaced by first CI deploy)

## GitHub Pages configuration

- Build type: legacy (deploy from branch)
- Branch: `main`
- Path: `/docs`
