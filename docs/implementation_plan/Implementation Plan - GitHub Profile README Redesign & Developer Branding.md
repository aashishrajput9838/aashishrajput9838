# Implementation Plan - GitHub Profile README Redesign & Developer Branding

This plan outlines the complete redesign of the GitHub Profile [`README.md`](file:///c:/github/mee/aashishrajput9838/README.md) for **Aashish Rajput**, transforming it into a modern, professional, high-impact developer portfolio.

## User Review Required

> [!IMPORTANT]
> - **Real Email Found:** We identified your active email `aashishrajput9838@gmail.com` from git config and will use it for contact links.
> - **LinkedIn Profile:** We will use `https://linkedin.com/in/aashishrajput9838` as the standard LinkedIn URL.
> - **GitHub Action Workflow:** We propose adding `.github/workflows/snake.yml` to automatically generate the contribution snake SVG (`output/github-contribution-grid-snake.svg`) via GitHub Actions.

## Proposed Changes

### 1. GitHub Profile README

#### [MODIFY] [`README.md`](file:///c:/github/mee/aashishrajput9838/README.md)

Restructure and polish the README into 10 cohesive sections:
1. **Hero Header:** Centered greeting, professional tagline, customized typing SVG animation, profile view counter, and core identity badges.
2. **About Me:** Professionally rewritten developer intro highlighting B.Tech CSE background, Full Stack/Backend focus (MERN & Next.js), AI/ML exploration, authentication/security interests, and system design goals.
3. **Tech Stack:** Cleanly grouped skill icons (`skillicons.dev`) for Languages, Frontend, Backend, Databases, and DevOps / Tools.
4. **GitHub Analytics:** Responsive cards for GitHub Stats, Top Languages, Contribution Streak, Activity Graph, and GitHub Trophies with unified `tokyonight` theme.
5. **Contribution Snake:** Embedded dark/light contribution snake widget rendered via GitHub Actions output.
6. **Featured Projects:** Enhanced project cards table featuring:
   - 🎓 **Academic Universe** (AI-powered Student ERP Platform)
   - 🎵 **SongX** (Modern Music Streaming Web App)
   - 🤖 **AI Authentication** (Google Authenticator-based 2FA Login)
   - 📊 **Life Debugger** (Daily Productivity & Mistake Tracker)
7. **Currently Learning:** Clean list/badge showcase of active focus technologies (Next.js 16, TypeScript, Docker, Firebase, System Design, AI).
8. **Developer Journey & Focus:** Visual pipeline breakdown mapping technical progression from Full-Stack to System Design & Entrepreneurship.
9. **Connect & Contact:** High-visibility contact buttons (Email, GitHub, Instagram, LinkedIn).
10. **Footer:** Clean footer badge and wave aesthetic (`capsule-render`).

---

### 2. GitHub Actions Workflows

#### [NEW] [`.github/workflows/snake.yml`](file:///c:/github/mee/aashishrajput9838/.github/workflows/snake.yml)

- Workflow to run on schedule (every 24 hours) and on push to `main`.
- Uses `Platane/snk@v3` to automatically generate contribution graph snake animations in the `output` branch.

---

## Verification Plan

### Manual Verification
1. Inspect markdown syntax and element alignment in [`README.md`](file:///c:/github/mee/aashishrajput9838/README.md).
2. Validate all badge URLs, image links, widget parameters, and profile paths.
3. Check workflow definition in `.github/workflows/snake.yml`.
