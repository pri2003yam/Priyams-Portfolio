Priyam’s Portfolio

A fast, modern developer portfolio built with Astro, optimized for performance, accessibility, and clean design.
Showcases my projects, skills, achievements, competitive programming profiles, and engineering philosophy.

<p align="center"> <img src="image.png" alt="Portfolio Banner" /> </p>
Features

Static Site Generation — blazing-fast load times

Minimal JavaScript — only essential interactive pieces

Dark/Light Theme — persistent, smooth theme toggling

Dynamic Content Collections — type-safe project organization

Responsive UI — tailored for all screen sizes

Accessible Design — keyboard-friendly & WCAG-conscious

SEO-ready — structured metadata, OpenGraph tags, canonical URLs

Performance Highlights

Lighthouse Score: 100 / 100 / 100 / 100

JavaScript Size: < 50KB total

First Contentful Paint: < 1.2s

Time to Interactive: < 2.5s

Tech Stack

Framework: Astro

Language: TypeScript

Styling: Custom CSS + CSS variables

Deployment: Vercel / Netlify

Content: Astro Content Collections

Animations: Pure CSS (no GSAP)

Getting Started
npm install
npm run dev
npm run build
npm run preview

Project Structure
src/
  components/       UI components (Header, Cards, Forms, etc.)
  layouts/          Page layouts
  pages/            Routes (Home, Contact, etc.)
  content/
    projects/       Your project markdown files
  styles/           Global styles (theme, animations, typography)
public/             Icons, logos, fonts, and static assets
astro.config.mjs    Astro configuration

Add a New Project

Create a new .md file inside src/content/projects/:

---
title: "Project Name"
description: "Short description of the project."
tech: ["React", "Node.js", "MongoDB"]
github: "https://github.com/pri2003yam/repo"
live: "https://example.com"
order: 1
---


Astro will automatically include it in the Projects section sorted by order.

Customizing Your Portfolio

Colors: Edit src/styles/variables.css

Fonts: Update src/styles/fonts.css

Dark Mode: Modify rules in src/styles/dark-mode.css

Animations: Change timings in src/styles/animations.css

Tech Stack Logos: Add PNG/SVGs in public/logos/

Notable Improvements

Compared to older versions of my portfolio:

Drastically reduced JavaScript

Removed heavy animation libraries

Improved content architecture

Added coding profiles (LC/CF/AtCoder/GFG)

Reworked skills grid + responsive layout

Enhanced SEO metadata and schema

Commands
Command	Description
npm install	Install dependencies
npm run dev	Start local dev server at localhost:4321
npm run build	Build production files to ./dist/
npm run preview	Preview the production build
npm run astro ...	Run Astro CLI commands
npm run astro help	Show Astro CLI help
License

MIT License

Author

Priyam Raj

GitHub: @pri2003yam

LinkedIn: Priyam Raj

Email: priyamjha78@gmail.com
