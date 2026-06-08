# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the **GitHub profile README** repository (`jacquemar/jacquemar`). The sole file is `README.md`, which renders as the public-facing profile page at github.com/jacquemar. There is no build system, no tests, and no source code.

## README Structure

The profile is organized into these sections (in order):

1. **Header** — name, role tagline, LinkedIn & Connect2Card badges
2. **À propos de moi** — bullet list of focus areas and interests
3. **Stack & Outils** — badge grids grouped by category (Frontend, Backend, GIS, DevOps, Design)
4. **Projets phares** — personal/open-source projects with stack, concept, and link
5. **Projets SIG professionnels** — client GIS projects (AFOR, Orange CI)
6. **Stats GitHub** — dynamic stats cards via github-readme-stats
7. **Trophées & Contributions** — github-profile-trophy card
8. **En ce moment** — current focus, learning, and availability

## Conventions

- Language: **French** throughout
- Badges use [shields.io](https://shields.io) `style=for-the-badge` format
- Project entries follow a consistent template: stack badge, concept/objective, key points, link
- Dynamic cards (stats, trophies) use `vercel.app` hosted services and reference username `jacquemar`
- Sections are separated by `---` horizontal rules
- All links open inline (no `target="_blank"` — GitHub strips it anyway)

## Editing Guidelines

When adding or updating projects, match the existing entry format:
```markdown
### <emoji> <Project Name>
> <one-line description>

- ⚙️ **Stack** : <technologies>
- 💡 **Concept** : <what it does>
- ✅ **Points clés** :
  - <bullet 1>
  - <bullet 2>
- 🔗 **Lien** : [Visiter ..](url)
```

For GIS professional projects, omit the `>` tagline and use `🎯 **Objectif**` + `🚀 **Infra**` fields instead of `💡 **Concept**`.
