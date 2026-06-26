# HTML Labs

HTML labs are temporary interactive previews for visual decisions.

## Role Of A Lab

A lab should:

- show real variants;
- demonstrate interactions;
- let the user test desktop/mobile states;
- collect choices;
- refine a selected base;
- generate copyable summaries.

A lab should not pretend to generate unlimited options by itself. New variants come from the agent in chat.

## Required Controls

For visual components, include as relevant:

- desktop/mobile toggle;
- variant selector;
- state selector;
- refinement controls;
- reference notes;
- `Request more variants in chat`;
- `Decide for me`;
- `Copy choices`.

## Good Lab Targets

- navbars;
- footers;
- heroes;
- toasts;
- pop-ups;
- modals;
- pricing cards;
- service cards;
- testimonials;
- forms;
- FAQ accordions;
- banners;
- cookie notices;
- floating CTAs.

## Navbar/Footer Example

Use `assets/labs/navbar-footer-lab.html` as a starting point for Stage 7. Adapt brand, copy, pages, CTAs, variants, and code style to the user's project.

## Lab Lifecycle

1. Create or adapt the lab.
2. Let the user choose a base.
3. Refine the base.
4. Generate `Copy choices`.
5. Integrate the approved direction into the real project.
6. Remove the temporary lab unless the user wants to keep it.
