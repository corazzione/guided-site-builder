# Copy Choice Templates

Use these summaries at the end of each stage or focused component workflow.

## Generic Stage

```text
Stage approved:

User goal:
Selected direction:
Visual references:
Specific choices:
Agent-assumed decisions:
Open questions:

Instruction for the agent:
Continue from these decisions. Preserve the user's choices, improve implementation quality, and ask only for missing information that cannot be safely assumed.
```

## Component Lab

```text
Component lab approved:

Component:
Context:
Selected base variant:
Refinements:
States required:
Desktop behavior:
Mobile behavior:
Visual references:
Agent-assumed decisions:

Instruction for the agent:
Implement this component in the project style. If the design system exists, follow it. If it does not, infer the best fit from the context and mark assumptions.
```

## More Variations Request

```text
Request: generate more variations.

Current context:
Current favorite:
What the user liked:
What the user disliked:
Visual references:
Design system:
Avoid:

Instruction:
Generate a new round of variants. Keep the interactive preview behavior and make each variant meaningfully different.
```

## Final Build

```text
Project approved for final build:

Niche:
Goal:
Architecture:
Design system:
Visual references:
Navbar:
Footer:
Hero:
Homepage blocks:
Internal pages:
Forms:
Responsiveness:
Animations:
SEO:
Performance:
Accessibility:
Pending content:
Agent-assumed decisions:

Instruction:
Build the complete website based on all decisions above. Do not reinvent the visual direction without calling it out. If information is missing, use "Decide for me" based on the niche, goal, design system, references, and approved choices.
```
