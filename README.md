# Guided Site Builder

Build websites with your client, not around them.

`guided-site-builder` is a Codex skill that turns an AI coding agent into a step-by-step website creation assistant. It guides users through niche research, site architecture, visual identity, visual references, navbar/footer labs, hero sections, homepage blocks, internal pages, conversion flows, responsiveness, SEO, and final delivery.

Every stage ends with a copyable decision summary, so the agent can continue with clear context instead of guessing.

## What It Does

- Guides the client before building.
- Offers `Decide for me` when the user is unsure.
- Accepts screenshots, links, logos, palettes, and project files as visual references.
- Generates real visual labs for decisions that need interaction.
- Supports focused component workflows like navbars, heroes, toasts, pop-ups, cards, forms, CTAs, and modals.
- Produces paste-ready summaries after each stage.

## Skill Folder

The installable skill lives in:

```text
guided-site-builder/
```

Key files:

```text
guided-site-builder/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── slash-commands.md
│   ├── stages.md
│   ├── visual-references.md
│   ├── copy-choice-templates.md
│   ├── html-labs.md
│   └── use-cases.md
└── assets/
    └── labs/
        └── navbar-footer-lab.html
```

## Slash Commands

```text
/site-start
/site-research
/site-architecture
/site-design-system
/site-references
/site-navbar
/site-footer
/site-hero
/site-home-blocks
/site-page
/site-form
/site-responsive
/site-motion
/site-seo
/site-review
/component-lab
/copy-choices
```

## Example Use Cases

```text
/site-start
Build a website for a premium dental clinic.
```

```text
/site-navbar
Generate navbar variations for a luxury architecture studio.
```

```text
/component-lab
Create toast notification variants for a fintech dashboard.
```

```text
/component-lab
Create pop-up variants for a SaaS landing page.
```

## Detailed Pitch

Read the full project explanation here:

[guided-site-builder-pitch.md](guided-site-builder-pitch.md)

## Status

Experimental, but usable as a workflow spec and installable Codex skill.
