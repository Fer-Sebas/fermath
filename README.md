# Fermath — Math Notes Digital Garden

A personal math wiki and digital garden built with [Quartz v4](https://quartz.jzhao.xyz/).

This repository contains interconnected notes focused on understanding mathematics from intuition to formal definitions, with emphasis on clarity, examples, and long-term refinement.

## What this repository is

Fermath is an evolving collection of math notes organized as small, linkable concepts rather than a strict textbook sequence.

Current topics include:
- Set theory and functions
- Algebraic properties
- Algebraic structures (groups, rings, fields, vector spaces)
- Foundational glossary and number concepts

## Project goals

- Build a practical reference for learning and revisiting math topics.
- Bridge intuitive explanations with formal language.
- Keep notes concise, connected, and continuously improvable.

## Tech stack

- **Framework:** Quartz v4
- **Content format:** Markdown (with wiki-style links)
- **Runtime:** Node.js

## Local development

### 1) Install dependencies

```bash
npm install
```

### 2) Run locally

```bash
npx quartz build --serve
```

Then open the local URL shown in the terminal.

### 3) Build static site

```bash
npx quartz build
```

Generated files are output to `public/`.

## Content structure

- `content/` → primary notes and pages
- `quartz.config.ts` → site and plugin configuration
- `quartz.layout.ts` → page layout configuration
- `public/` → generated static output

## Contributing

This is primarily a personal knowledge project, but typo fixes and clarity improvements are welcome.

If you open an issue or PR, please:
- Keep explanations beginner-friendly where possible
- Prefer small, focused edits
- Preserve internal links between notes

## License

Code and configuration inherit the Quartz MIT license in this repository. Content licensing should be clarified by the repository owner as the notes evolve.
