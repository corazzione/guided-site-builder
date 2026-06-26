---
name: guided-site-builder
description: Use when the user wants to plan, design, or build a website through a guided client workflow instead of a one-shot generation. Guides niche discovery, market research, site architecture, flowcharts, visual identity, design systems, visual references, navbar/footer labs, hero sections, homepage blocks, internal pages, forms, responsiveness, animations, SEO, accessibility, and final delivery. Also use for focused website UI decisions such as generating variants of navbars, footers, heroes, cards, toasts, pop-ups, modals, forms, pricing sections, testimonials, CTAs, or any individual site block.
---

# Guided Site Builder

Turn website creation into a client-friendly, step-by-step studio workflow. Do not rush into implementation. Discover the business, collect decisions, show real options, refine them, and produce copyable summaries before building.

## Core Rules

- Never build the full site immediately unless the user explicitly asks to skip the guided workflow.
- Always offer `Decide for me` when asking the user to choose.
- Treat every choice as a direction, not a prison. Preserve the user's intent while improving the final implementation.
- Use real previews when visual decisions matter. Prefer HTML/React/Vue labs over text-only descriptions.
- Make clear that preview labs do not generate infinite variants by themselves. The chat/agent generates new variants, then updates the lab.
- End each stage with a `Copy choices` summary the user can paste back into the agent.
- Mark all agent-assumed decisions in the summary so the user can review them later.

## Slash Commands

If the user invokes one of these command-like requests, route directly to that workflow:

- `/site-start` - run the full guided website workflow from niche discovery.
- `/site-research` - research or structure market analysis for the niche.
- `/site-architecture` - define pages, sitemap, CTAs, redirects, and a flowchart.
- `/site-design-system` - define visual identity, palette, typography, tokens, and design rules.
- `/site-references` - analyze attached screenshots, links, or files and extract design principles.
- `/site-navbar` - generate/refine navbar variants with desktop/mobile behavior.
- `/site-footer` - generate/refine footer variants.
- `/site-hero` - generate/refine hero section variants.
- `/site-home-blocks` - plan or generate homepage sections block by block.
- `/site-page` - plan or generate a specific internal page.
- `/site-form` - design conversion forms, quote flows, booking flows, or lead capture.
- `/site-responsive` - review and refine desktop/tablet/mobile behavior.
- `/site-motion` - design animations and microinteractions.
- `/site-seo` - define SEO, accessibility, performance, metadata, schema, and content structure.
- `/site-review` - run final delivery review and produce pending-items checklist.
- `/component-lab` - generate variants for a focused component such as toasts, pop-ups, cards, pricing, testimonials, CTAs, banners, accordions, tabs, forms, or modals.
- `/copy-choices` - summarize current decisions in a paste-ready format.

For detailed command behavior and examples, read `references/slash-commands.md`.

## Workflow

Use the full workflow when the user wants a complete website. For focused tasks, jump to the relevant stage and still produce `Copy choices`.

1. **Niche and context** - business type, goal, audience, constraints, references, anti-references.
2. **Market research** - competitors, common pages, CTAs, trust signals, differentiation.
3. **Architecture and flowchart** - pages, navigation, footer links, user journey, CTA destinations.
4. **Auxiliary skills and design system** - recommend design skills when available; define visual rules.
5. **Visual identity** - logo, palette, typography, imagery, style, references, forbidden styles.
6. **Assets and base content** - images, copy, testimonials, contact details, placeholders.
7. **Navbar and footer** - real visual lab, desktop/mobile toggle, dropdowns, refinements, summary.
8. **Hero section** - real first-fold variants, headline, CTA, media, proof, mobile behavior.
9. **Homepage blocks** - build the homepage section by section.
10. **Internal pages** - define and build each page with goal, sections, CTA, SEO, and content.
11. **Forms and conversion** - fields, destinations, success states, consent, anti-spam.
12. **Responsiveness and states** - breakpoints, mobile menu, overflow, loading/error/success.
13. **Animations and microinteractions** - entry, hover, scroll reveal, dropdowns, reduced motion.
14. **SEO, performance, accessibility** - metadata, headings, schema, images, fonts, contrast, focus.
15. **Final review and delivery** - links, CTAs, content gaps, responsiveness, SEO, performance, deploy readiness.

Read `references/stages.md` for detailed questions, decisions, and copy-choice templates per stage.

## Visual References

The user may build from their own idea or provide visual references. Accept:

- images attached in chat;
- screenshots;
- files in the project folder;
- website links;
- inspiration folders;
- logos, palettes, layouts, competitor examples;
- references for specific components such as navbars, heroes, toasts, pop-ups, forms, cards, or pricing blocks.

When analyzing a reference, extract principles rather than copying blindly: structure, hierarchy, spacing, density, palette, typography, borders, buttons, media treatment, motion, mobile behavior, and what to avoid.

Read `references/visual-references.md` before doing detailed visual-reference work.

## Visual Labs

When a visual choice would benefit from interaction, create a temporary lab. A lab should:

- show several real variants;
- include desktop/mobile toggles when relevant;
- demonstrate actual dropdowns, menu states, hover, motion, or form states;
- allow the user to select a base direction;
- refine that base in later steps;
- generate a copyable summary.

Use `assets/labs/navbar-footer-lab.html` as the starting example for Stage 7. Adapt it to the user's project, brand, design system, and chosen stack.

Read `references/html-labs.md` for lab rules and extension patterns.

## Focused Component Mode

Use focused component mode when the user wants only one piece of a site or app, for example:

- toast variants;
- pop-up or modal variants;
- announcement bars;
- hero options;
- pricing sections;
- testimonial layouts;
- service cards;
- product cards;
- contact forms;
- newsletter blocks;
- FAQ accordions;
- mobile menus;
- floating WhatsApp buttons;
- cookie banners;
- checkout CTAs;
- lead-capture forms.

Do not force the full 15-stage workflow. Ask only the context needed for that component, show variants, refine the chosen direction, and produce `Copy choices`.

Read `references/use-cases.md` for examples.

## Copy Choices

Every stage and focused component workflow should end with a paste-ready summary:

```text
Stage approved:
User goal:
Selected direction:
Visual references:
Specific choices:
Agent-assumed decisions:
Open questions:
Instruction for the agent:
```

Read `references/copy-choice-templates.md` for reusable templates.
