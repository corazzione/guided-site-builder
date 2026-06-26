# Slash Commands

Slash commands let users enter the workflow at the exact level they need. Treat these as natural-language shortcuts, not as hard shell commands.

## Full Workflow

### `/site-start`

Use when the user wants to build a whole website from scratch or redesign a full site.

Ask for:

- niche;
- business type;
- target audience;
- website goal;
- references;
- autonomy level;
- existing assets.

Then proceed stage by stage.

## Strategy Commands

### `/site-research`

Use for market research, niche analysis, competitor patterns, CTA recommendations, and differentiation opportunities.

Output:

- market patterns;
- recommended page count;
- trust signals;
- expected CTAs;
- risks to avoid;
- copyable research summary.

### `/site-architecture`

Use when the user only needs sitemap, pages, redirects, navigation, or a client-facing flowchart.

Output must include:

- page list;
- menu structure;
- footer link structure;
- CTA destinations;
- user journey;
- Mermaid flowchart;
- copyable architecture summary.

### `/site-design-system`

Use when the user wants palette, typography, tokens, theme, components, or visual direction before building.

If design-focused skills are available, recommend `impeccable`, `ui-ux-pro-max`, or equivalent design workflows.

## Visual Reference Commands

### `/site-references`

Use when the user attaches images, screenshots, links, or files and wants the agent to extract a direction.

Analyze:

- layout structure;
- spacing;
- type scale;
- color strategy;
- component style;
- image treatment;
- motion cues;
- mobile implications;
- what to avoid.

Return:

- extracted design principles;
- what to borrow;
- what not to copy;
- copyable reference summary.

## Website Section Commands

### `/site-navbar`

Generate or refine navbar variants. Include desktop/mobile behavior, dropdowns, CTA placement, sticky/floating behavior, transparency, glass, motion, and accessibility.

### `/site-footer`

Generate or refine footer variants. Include link groups, CTA area, social links, legal links, newsletter, contact details, and mobile layout.

### `/site-hero`

Generate or refine hero section variants. Include headline, subheading, CTA, media, proof, layout, motion, and mobile behavior.

### `/site-home-blocks`

Plan homepage blocks and their order. Use for services, benefits, process, testimonials, portfolio, FAQ, contact, CTA, and social proof.

### `/site-page`

Plan or build one internal page. Ask the page goal, CTA, required sections, SEO needs, visuals, and reused components.

## Conversion And Quality Commands

### `/site-form`

Use for contact forms, quote forms, booking flows, multi-step forms, newsletter signup, checkout lead capture, CRM handoff, or WhatsApp pre-filled messages.

### `/site-responsive`

Use for responsive behavior, breakpoints, mobile menus, sticky CTAs, overflow, text wrapping, and mobile section order.

### `/site-motion`

Use for animations, hover states, scroll reveal, menu transitions, reduced motion, and microinteractions.

### `/site-seo`

Use for SEO, accessibility, performance, metadata, schema, alt text, content hierarchy, URLs, and Core Web Vitals.

### `/site-review`

Use at the end to audit readiness: content, links, CTAs, responsive states, forms, SEO, accessibility, performance, and pending items.

## Component Command

### `/component-lab`

Use when the user wants variants for one UI component instead of a full website stage.

Examples:

- `/component-lab toasts for a fintech dashboard`
- `/component-lab pop-ups for a beauty clinic website`
- `/component-lab pricing cards for a SaaS landing page`
- `/component-lab testimonial sections for a premium architect`
- `/component-lab floating WhatsApp CTA for a local service business`

Workflow:

1. Ask for component type and context.
2. Ask for brand/design system or visual references.
3. Offer `Decide for me`.
4. Generate several real variants.
5. Let the user pick a base.
6. Refine details.
7. Produce `Copy choices`.

## Summary Command

### `/copy-choices`

Use when the user wants to continue in another agent, another thread, or a later stage.

Output a paste-ready summary with decisions, references, assumptions, and next instruction.
