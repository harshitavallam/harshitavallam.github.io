# Harshita Vallamsetty Personal Website

This repository contains the source for Harshita Vallamsetty's personal website and resume site, built with Hugo Blox and deployed via GitHub Pages.

## Tech Stack

- Hugo
- Hugo Blox
- Tailwind CSS
- Pagefind

## Local Development

Install Hugo first, then run:

```bash
pnpm install
pnpm run dev
```

To create a production build:

```bash
pnpm run build
```

## Content Structure

- `content/_index.md`: homepage sections
- `content/experience.md`: resume page
- `content/projects/`: project entries
- `data/authors/me.yaml`: profile, experience, education, and skills data
- `config/_default/`: site configuration and navigation

## Updating Content

Most site updates can be made by editing Markdown and YAML files directly:

- Change homepage text in `content/_index.md`
- Update resume details in `data/authors/me.yaml`
- Add or edit projects in `content/projects/`
- Adjust navigation or metadata in `config/_default/`

## Deployment

Changes pushed to `main` are published through the repository's existing GitHub Pages workflow.
