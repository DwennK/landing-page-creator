# Creative Production Mode

Use this reference for every full landing page creation/redesign. It is mandatory, not optional.

## Core Rule

Do not build the full page in one pass. Work like a small creative team:

1. concept
2. section storyboard
3. asset plan
4. motion prototype
5. hero build
6. section-by-section build
7. screenshot critique and polish

Each pass must improve the idea, not just add more UI.

Skip this workflow only for small targeted edits or when the user explicitly requests a simple/conservative page.

## Concept Pass

Before coding, define:

- campaign idea: what makes this site memorable?
- one big trick: what visual moment will the client remember?
- world/metaphor: what world does the visitor enter?
- tone: premium, playful, cinematic, editorial, technical, surreal, luxurious, local, etc.
- commercial promise: why should the buyer act now?

If the concept sounds like “premium repair website” or “modern SaaS page,” it is too weak.

## Section Storyboard

Every section needs a named idea, not just a layout.

For each section, write:

- section name
- job in the story
- visual scene or asset
- interaction/motion
- conversion purpose
- proof/content required
- screenshot failure risk

Delete sections that do not have a job. Do not create filler sections.

## Asset Plan

List every asset before implementation:

- real client assets to reuse
- ImageGen assets to create
- product/object renders needed
- texture/background/material assets
- icons or diagrams
- video/image-sequence candidates

If a section would rely on fake UI cards because no asset exists, generate or source a better asset, or redesign the section.

## Motion Prototype

Define motion before coding:

- scroll beats
- pinned/sticky regions
- scrubbed timelines
- hover/cursor interactions
- object states
- reduced-motion fallback
- performance budget

Use GSAP/ScrollTrigger, Three.js/WebGL, canvas, Framer Motion/Motion, Rive, Spline, or image sequences only when they create the signature selling moment.

## Hero Acceptance

The hero must pass before the rest of the page is built.

Pass only if:

- the first screenshot feels like a custom campaign
- the main visual could not belong to a random company
- the one big trick is visible or strongly implied
- text and CTA are clear without explaining the design
- mobile still feels intentionally designed

If it fails, rebuild the hero. Do not compensate with lower sections.

## Section Acceptance

Each section must pass as a standalone screenshot.

Pass only if:

- the section has a clear idea
- the section contains real information, proof, asset, or interaction
- spacing and composition feel intentional
- it does not look like an empty card container
- it helps sell the business

If a section is just decorative, replace it with a tighter proof block or a more useful interactive component.

## Subagents

Use subagents when available for higher-stakes builds:

- **Art direction critic**: review screenshots and identify weak/generic/cheap sections.
- **Motion/interaction critic**: review whether motion supports the story or is decorative.
- **Conversion critic**: review whether each section helps the buyer decide.
- **Frontend QA critic**: review responsiveness, performance, accessibility, and visual bugs.

Pass screenshots and the user goal, not your preferred answer. Treat subagent output as critique; the main agent still owns the final decision.

## Long-Run Mode

For every full build, expect a longer build. For “10k site,” “Oryzo-level,” “Awwwards-level,” “spend time,” or similar requests, be even stricter:

- prioritize fewer stronger sections over many average sections
- run at least two screenshot critique loops for every full build
- keep a punch list of visual failures
- fix the biggest visible weakness before adding new content
- stop calling it done while any section looks embarrassing in isolation

The result should feel like a sellable creative prototype, not a first draft.
