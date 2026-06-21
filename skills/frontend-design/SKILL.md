---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications. Generates creative, polished code and UI design that avoids generic AI aesthetics.
license: See LICENSE.txt in the repository for full terms.
---

## Purpose
This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. It produces working, production-ready code (HTML/CSS/JS or framework components) with a clear, memorable visual direction.

## When to use
- Building pages, landing pages, dashboards, or microsites
- Creating React/Vue/Svelte components or apps with a strong aesthetic
- Styling or beautifying an existing UI where design quality matters

## Inputs (from user)
- Component/page description and purpose
- Target audience and tone
- Technical constraints (framework, browser support, asset limits)
- Any brand guidelines, fonts, or color constraints

## Outputs
- A drafted README-style usage note and a working code artifact saved in the workspace
- Design rationale and a short checklist for quality and accessibility
- Example prompts to iterate on the design

## Design Thinking Checklist (apply before coding)
1. Purpose: Define the problem and user goals.
2. Tone: Pick one bold aesthetic direction (e.g., brutalist, editorial, retro-futuristic).
3. Constraints: Note frameworks, performance, accessibility targets.
4. Differentiator: Pick one unforgettable visual/interaction idea.

## Aesthetic Guidelines (must-follow)
- Typography: Use a distinctive display font paired with a refined body font; avoid system defaults and overused AI staples.
- Color & Theme: Commit to a concise palette using CSS variables; choose dominant + one sharp accent.
- Motion: Prefer CSS-only animations for HTML pages; use staggered reveals and one high-impact entrance.
- Composition: Embrace asymmetry, overlap, or negative space appropriate to the chosen tone.
- Backgrounds & Detail: Add layered textures, gradient meshes, or subtle grain — tailored to the concept.
- Avoid: Inter/Roboto/Arial, cliché purple-on-white gradients, predictable layouts, and cookie-cutter components.

## Implementation Expectations
- Deliverables should be functional, not just mockups: working markup, styles, and minimal JS for interactions.
- Match complexity to vision: minimalism needs precision; maximalism needs layered effects.
- Include accessibility basics: semantic HTML, color contrast, and keyboard focus states.

## Quality Criteria
- Visual: Cohesive typographic scale, intentional color usage, and a memorable focal element.
- Technical: Clean, modular CSS (variables + utility classes), responsive layouts, and progressive enhancement.
- UX: Clear hierarchy, discoverable actions, and performant animations.

## Typical Workflow
1. Clarify purpose, tone, and constraints with the user.
2. Produce a 1-paragraph design rationale and moodboard suggestions.
3. Create working code (HTML/CSS/JS or component files) and a short README with usage.
4. Iterate based on feedback — tune typography, colors, spacing, and motion.

## Example prompts to run this skill
- "Build a landing hero for a boutique AI studio—luxury/refined, dark theme, responsive, provide HTML/CSS and fonts."
- "Create a dashboard card component—brutalist/raw, bold typography, hover interactions, React + CSS modules."

## Clarifying questions to ask users
- What is the primary goal of this page/component?
- Who is the target audience and what tone should we pick?
- Any brand colors, fonts, or asset limits to follow?
- Preferred framework or plain HTML/CSS/JS?

## Iteration & Handoff
- Provide a short changelog and list of files created.
- Add usage examples and minimal integration notes.

## Notes
- This skill emphasizes creative restraint or abundance depending on the chosen tone — the key is intentionality.
- Refer to LICENSE.txt for licensing details.
