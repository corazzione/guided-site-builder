# Guided Site Builder Skill

A skill that turns coding agents into guided website creation consultants: first they understand the business, then they plan the architecture, then they walk the client through real visual choices, and only then do they build the website.

## Name Ideas

### Clear And Direct

- `guided-site-builder`
- `site-building-wizard`
- `site-creation-flow`
- `client-site-planner`
- `website-brief-to-build`
- `site-architecture-builder`
- `stepwise-site-builder`

### More Brandable

- `siteforge`
- `sitecraft-guide`
- `webstudio-agent`
- `clientflow-sites`
- `brief-to-website`
- `studio-site-builder`
- `website-concierge`

### More Agent-Focused

- `agentic-site-builder`
- `agentic-web-studio`
- `site-agent-workflow`
- `ai-web-director`
- `web-design-agent-flow`
- `agentic-website-planner`

### Recommended Name

Recommended GitHub name:

```text
guided-site-builder
```

Why: it is short, clear, easy to remember, and describes the core differentiator: building websites through a guided workflow instead of a single generic prompt.

## The Problem This Skill Solves

Many agents can generate a full website in seconds, but that usually creates three problems:

1. The website feels generic.
2. The client does not participate in important decisions.
3. The agent has to guess the architecture, visual identity, content, CTA, pages, user flow, and responsive details.

`guided-site-builder` solves this by turning website creation into a guided studio-like process:

- understand the niche first;
- research or suggest market research;
- define architecture and user flow;
- collect visual identity;
- accept visual references;
- show real HTML options;
- refine block by block;
- generate copyable decision summaries;
- implement only after the direction is clear.

## Core Idea

The skill prevents the agent from building too early.

Instead of answering "here is your website", the agent guides the user through stages:

```text
Discover -> Research -> Plan -> Show options -> Refine -> Copy choices -> Build
```

Each stage removes ambiguity before the next one begins.

This improves:

- visual quality;
- niche alignment;
- site architecture;
- implementation precision;
- client satisfaction;
- the agent's ability to make good design decisions.

## Skill Principles

### 1. Always Offer "Decide For Me"

The user should never get stuck because they do not know how to answer.

For every important decision, the agent offers:

```text
1. Choose an option
2. See more variations in chat
3. Mix options
4. Adjust details
5. Decide for me
6. Copy choices to continue
```

When the user chooses "Decide for me", the agent decides based on:

- niche;
- website goal;
- target audience;
- market research;
- design system;
- visual references;
- UX best practices;
- previous choices.

### 2. HTML Previews Show, Chat Generates

The visual HTML lab should not pretend to generate infinite options by itself.

The role of HTML is to:

- show real options;
- let the user test dropdowns, mobile menus, hover states, motion, and layout;
- collect choices;
- generate a copyable summary.

The role of the chat/agent is to:

- generate new variations;
- adapt based on visual references;
- update the HTML lab;
- refine the implementation;
- build the final website.

### 3. Every Stage Ends With "Copy Choices"

At the end of each stage, the skill generates a copyable decision summary.

This lets the agent continue without losing context.

Example:

```text
Stage 7 approved: Navbar and footer

Navbar base: floating pill
Footer base: CTA-first
Padding: spacious
Organization: logo left, CTA right
Material: glass
Animation: subtle motion
Visual reference used: /references/premium-navbar.png

Instruction for the agent:
Use these choices as direction, not as a rigid limit. Integrate the navbar and footer into the final site while preserving the design system, logo, CTA, architecture, and responsiveness.
```

### 4. Visual References Are First-Class Inputs

The user can build from their own idea or attach visual references.

The skill accepts:

- images attached in chat;
- screenshots;
- files inside the project folder;
- website links;
- inspiration folders;
- logos;
- palettes;
- competitor layouts;
- examples of navbars, heroes, footers, cards, forms, or sections.

The agent extracts design principles from references instead of copying blindly.

When analyzing a visual reference, the agent looks for:

- structure;
- hierarchy;
- spacing;
- density;
- palette;
- typography;
- border style;
- button style;
- image treatment;
- menu behavior;
- brand feeling;
- boldness level;
- responsive patterns;
- elements the user wants to avoid.

## Where Visual References Fit

Visual references appear throughout the workflow, but they serve different purposes at each stage.

### Stage 1: Niche And Context

Ask:

```text
Do you already have a website, image, screenshot, or visual reference that represents the direction you want?
```

Use it to:

- understand initial taste;
- identify competitors;
- capture anti-references;
- avoid choosing the wrong direction early.

Copy choices:

```text
Initial references:
Anti-references:
Taste notes:
```

### Stage 4: Auxiliary Skills And Design System

Ask:

```text
Do you want me to use visual references to create or adjust the design system?
You can attach images, send links, or point me to files in the project folder.
```

Use it to:

- create a palette;
- define typography;
- define component style;
- choose light/dark theme;
- recommend skills such as `impeccable` and `ui-ux-pro-max`.

Copy choices:

```text
References used for the design system:
Extracted palette:
Suggested typography:
Inspired components:
Forbidden styles:
```

### Stage 5: Visual Identity

This is the main stage for visual references.

Ask:

```text
Do you have a logo?
Do you have a palette?
Do you have screenshots of websites you like?
Do you have examples of websites you do not want to resemble?
Do you want me to analyze an attached image?
Do you want me to research references for this niche?
```

Use it to:

- turn subjective taste into visual rules;
- extract design tokens;
- define brand direction;
- create a mini design system.

Copy choices:

```text
Approved visual references:
Attached files:
Links used:
Elements to use as inspiration:
Elements to avoid:
Extracted visual direction:
```

### Stage 7: Navbar And Footer

Ask:

```text
Do you want to choose from the generated navbars, or attach a navbar/footer reference?
```

Use it to:

- create navbar variations based on the user's taste;
- adapt dropdowns, mobile menu, glass, transparency, CTA, and organization;
- generate a more precise second round.

Copy choices:

```text
Navbar/footer reference:
What to borrow from the reference:
What to avoid from the reference:
Selected navbar:
Refinements:
```

### Stage 8: Hero Section

Ask:

```text
Do you have a reference for the first fold, hero, cover, banner, or landing page?
```

Use it to:

- define composition;
- choose image/video treatment;
- adjust headline style;
- decide whether the hero is emotional, premium, commercial, editorial, or product-first.

Copy choices:

```text
Hero reference:
Desired composition:
Image/video direction:
Headline style:
Social proof in the hero:
```

### Stage 9: Homepage Blocks

Ask:

```text
Should any specific section follow a visual reference?
Examples: service cards, testimonials, portfolio, before/after, FAQ, form.
```

Use it to:

- adapt each block to the user's taste;
- avoid a generic homepage;
- create consistency across sections.

Copy choices:

```text
References by block:
Blocks inspired by references:
Blocks decided by the agent:
```

### Stage 15: Final Review

Ask:

```text
Compared with the approved references, does the final website follow the right direction?
What still feels off?
```

Use it to:

- validate visual alignment;
- adjust details before delivery;
- detect mismatch between reference and implementation.

Copy choices:

```text
Validated references:
Final adjustments based on references:
Approved items:
Pending items:
```

## Full Workflow

### Stage 1: Niche And Context

Discover the website type, goal, audience, constraints, initial references, and how much autonomy the user wants the agent to have.

### Stage 2: Market Research

Research or suggest research about the niche, competitors, opportunities, page patterns, CTAs, and conversion funnel.

### Stage 3: Architecture And Flowchart

Define pages, menu, footer links, user journey, CTA destinations, and redirects.

### Stage 4: Auxiliary Skills And Design System

Recommend using skills such as `impeccable`, `ui-ux-pro-max`, `frontend-design`, and `using-superpowers` when available.

### Stage 5: Visual Identity

Collect logo, palette, fonts, images, references, anti-references, and desired visual style.

### Stage 6: Assets And Base Content

Gather images, copy, testimonials, contact details, social links, certificates, maps, external links, and authorized placeholders.

### Stage 7: Navbar And Footer

Create a real visual lab with HTML variants, desktop/mobile toggle, dropdowns, mobile menu, and a copyable summary.

### Stage 8: Hero Section

Generate real first-fold options with headline, CTA, image/video, social proof, and responsive composition.

### Stage 9: Homepage Blocks

Build the homepage block by block: pain points, solution, services, benefits, process, social proof, FAQ, and final CTA.

### Stage 10: Internal Pages

Create each page with goal, sections, CTA, SEO needs, images, social proof, and reused components.

### Stage 11: Forms And Conversion

Define fields, submission destination, WhatsApp, email, CRM, calendar, success message, privacy consent, and anti-spam.

### Stage 12: Responsiveness And States

Test desktop, tablet, mobile, menus, dropdowns, forms, long text, overflow, loading, error, and success states.

### Stage 13: Animations And Microinteractions

Choose intentional motion: entry animations, hover states, scroll reveal, dropdowns, mobile menu, forms, and reduced motion.

### Stage 14: SEO, Performance, And Accessibility

Define title, description, headings, URLs, alt text, schema, images, fonts, contrast, focus states, and Core Web Vitals.

### Stage 15: Final Review And Delivery

Review architecture, identity, pages, links, CTAs, responsiveness, SEO, performance, accessibility, and pending content.

## Slash Commands

The skill supports command-style entry points so users can run the whole workflow or jump into a single stage/component.

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

### Full Site

```text
/site-start
I want to create a website for a premium dental clinic.
```

The agent runs the full process: niche, research, architecture, design system, visual identity, assets, navbar/footer, hero, homepage, internal pages, forms, responsiveness, motion, SEO, and final review.

### Architecture Only

```text
/site-architecture
Create the sitemap and user flow for a local restaurant website.
```

The agent only defines pages, menu, footer links, CTAs, redirects, and a client-facing flowchart.

### Navbar Only

```text
/site-navbar
Generate navbar variations for a luxury architecture studio. I want desktop/mobile previews and dropdown options.
```

The agent creates a focused visual lab for navbars, lets the user choose a base, refines it, and generates copyable choices.

### Hero Only

```text
/site-hero
I have a screenshot reference. Create hero variants inspired by it.
```

The agent analyzes the reference, extracts design principles, generates hero variants, refines the chosen one, and summarizes the direction.

### Component Lab

```text
/component-lab
Create toast notification variants for a fintech dashboard.
```

The agent does not force the full website workflow. It asks only for the context needed for the component, generates variants, refines the choice, and produces copyable implementation instructions.

## Focused Component Use Cases

The skill is not limited to complete websites. It can guide focused UI decisions for individual blocks and components.

### Toasts

Use for success, error, warning, info, loading, upload, payment, sync, or system-status notifications.

Decisions to collect:

- status types;
- tone;
- position;
- duration;
- stacking behavior;
- icons;
- color role;
- dismiss behavior;
- motion;
- mobile behavior;
- accessibility announcements.

Copy choices example:

```text
Component lab approved: Toasts

Context: fintech dashboard
Selected style: compact stacked toasts
States: success, error, warning, info, loading
Placement: bottom-right desktop, top mobile
Motion: subtle slide + fade
Accessibility: aria-live polite for non-critical, assertive for errors
Agent-assumed decisions: neutral tinted background, status icon per type

Instruction for the agent:
Implement toast notifications matching the product design system and these states.
```

### Pop-Ups And Modals

Use for lead capture, exit intent, newsletter signup, discount offers, onboarding prompts, confirmation dialogs, warnings, or feature announcements.

Decisions to collect:

- purpose;
- trigger;
- urgency;
- copy;
- CTA;
- dismissal;
- backdrop;
- size;
- animation;
- mobile behavior;
- accessibility;
- whether a modal is actually the right pattern.

### Cards

Use for service cards, product cards, pricing cards, blog cards, case-study cards, feature cards, team cards, or location cards.

Decisions to collect:

- density;
- image usage;
- icon usage;
- border/elevation;
- hover behavior;
- CTA placement;
- metadata;
- responsive grid;
- content length rules.

### Forms

Use for contact forms, quote builders, booking forms, checkout lead capture, newsletter signup, multi-step flows, or WhatsApp pre-filled flows.

Decisions to collect:

- fields;
- required fields;
- validation;
- submission destination;
- success state;
- error state;
- privacy consent;
- anti-spam;
- integrations;
- mobile layout.

### Banners, CTAs, And Announcement Bars

Use for promo strips, sticky CTAs, floating WhatsApp buttons, cookie banners, launch banners, or campaign alerts.

Decisions to collect:

- placement;
- persistence;
- scroll behavior;
- dismiss behavior;
- CTA destination;
- visual priority;
- animation;
- mobile compactness.

## How The Skill Handles Indecisive Users

If the user does not know how to answer, the agent must not stop.

It should say:

```text
I can decide for you based on the niche, goal, and best practices. I will mark that as an "agent-assumed decision" in the summary so you can review it later.
```

Every assumed decision must appear in the copy choices summary:

```text
Agent-assumed decisions:
- Temporary palette selected based on the niche
- Recommended navbar: floating pill
- Recommended CTA: Request a quote
```

## How The Skill Handles New Variations

When the user asks for "more variations", the HTML should not try to generate them by itself.

The correct flow is:

1. The user clicks "request more variations in chat".
2. The HTML generates a summary of the current state.
3. The user sends or pastes that summary to the agent.
4. The agent generates new variations.
5. The agent updates the visual lab.

Example summary:

```text
Request: generate more navbar variations.

Context:
- Niche: premium clinic
- Design system: light, sophisticated, green tones
- Current favorite navbar: floating pill
- User wants: something more exclusive and less SaaS-like
- Avoid: generic navbar with common links

Instruction:
Generate 5 new navbar families in HTML, keeping desktop/mobile toggle and real dropdowns.
```

## What Makes This Skill Different

This skill is not just a website generator.

It is a guided client workflow:

- talks with the user;
- understands the end client;
- researches the market;
- defines architecture;
- accepts references;
- creates real previews;
- collects decisions;
- generates copyable prompts;
- builds from choices, not guesses.

The result feels closer to a design studio workflow than a one-shot prompt.

## README Promise

```text
Build websites with your client, not around them.

guided-site-builder turns an AI coding agent into a step-by-step website creation assistant. It guides users through niche research, site architecture, visual identity, references, navbar/footer labs, hero sections, home blocks, internal pages, conversion flows, responsiveness, SEO, and final delivery.

Every stage ends with a copyable decision summary, so the agent can continue with clear context instead of guessing.
```

## Suggested Project Status

```text
Experimental, but usable as a workflow spec.
```

## Recommended Files

To turn this idea into an installable skill, create:

```text
guided-site-builder/
├── SKILL.md
├── references/
│   ├── stages.md
│   ├── visual-references.md
│   ├── copy-choice-templates.md
│   └── html-labs.md
└── assets/
    └── labs/
        └── navbar-footer-lab.html
```

The `SKILL.md` should be shorter than this document. It should contain the main workflow and link to detailed references only when needed.
