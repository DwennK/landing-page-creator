# 10K One-Shot Production Runbook

Use this for every full landing-page creation or redesign. It converts one user prompt into a complete autonomous production run.

The user gives one brief. The agent performs several internal passes without requesting approval unless a truly material ambiguity cannot be inferred safely.

## Pass 0 — Evidence and Constraints

Inspect before inventing:

- repository structure, framework, route, package manager, and current scripts
- existing website or supplied references
- logos, photography, typefaces, colors, product imagery, and brand rules
- current copy, claims, proof, CTAs, forms, analytics, SEO, URLs, and integrations
- viewport and performance constraints

Classify each important input as preserve, improve, replace, or missing. Do not fabricate missing proof. Read `review-checklist.md` now and establish the applicable acceptance evidence before implementation.

## Pass 1 — Design Read

Write internally:

> This page should make [buyer] feel [emotion] because [specific promise], proven by [evidence], inside a [visual world].

Choose the three design dials and identify:

- the dominant business object
- the buyer’s strongest anxiety
- the most convincing proof moment
- the desired conversion action
- the visual behavior the market expects
- one convention worth breaking

## Pass 2 — Internal Creative Competition

Read `concept-collision-engine.md`. Generate raw collisions, then form three complete directions.

For each direction, define internally:

- concept name and one big trick
- emotional angle and visual metaphor
- hero composition
- signature component
- scroll-story beats
- asset strategy
- motion stack
- proof and CTA logic
- mobile adaptation

Score each from 1 to 5 on:

- three-second clarity
- client specificity
- originality
- conversion strength
- feasibility in the available stack and time
- asset feasibility
- mobile viability

Select automatically. Originality cannot compensate for unclear value, and clarity cannot compensate for a generic template. In a close result, choose the more memorable direction with the simpler implementation path.

Do not show the rejected directions unless the user asks.

## Pass 3 — Reference and Asset Direction

When network access is available, perform a short reference hunt:

1. one art-direction or hero reference
2. one interaction/component reference
3. one motion or scroll-story reference

Extract principles; do not clone layouts or copyrighted expression.

Choose an asset path:

- **real-assets first** when the client’s material is strong
- **comp-first ImageGen** for a new cinematic visual world
- **code-first** for typography-led, diagrammatic, interface, or generative directions
- **hybrid** when generated key art and coded interaction reinforce each other

If using ImageGen, read `imagegen-prompts.md`, generate the key art or comp, inspect it, and reject weak or off-brand results before coding around them.

## Pass 4 — Scene and Story Blueprint

Create a concise internal production blueprint.

### Hero scene

- main object and visual world
- foreground, midground, and background
- first-frame composition
- headline, support copy, CTA, and proof placement
- initial, interactive, and resolved states
- asset layers and cropping behavior
- mobile recomposition

### Scroll story

Plan three to five beats:

1. hook
2. tension or buyer problem
3. transformation or expertise
4. proof
5. action

Each section needs a story job, visual device, content/proof, motion behavior, and conversion purpose. Delete filler before building it.

### Motion storyboard

Define triggers, pinned regions, timeline states, handoffs between sections, reduced-motion fallback, and mobile behavior. Read `motion-engineering.md` when motion is material.

## Pass 5 — Hero-Only Build

Implement the hero and the minimum surrounding shell first.

Before expanding:

- render desktop and mobile
- confirm the promise reads in roughly three seconds
- confirm the custom scene dominates the first viewport without obscuring the CTA
- confirm the one big trick is visible or strongly anticipated
- confirm mobile is a deliberate composition
- reject anything that resembles the kill patterns in `anti-ai-slop.md`

Apply the clarity, specificity, composition, asset, and mobile gates from `review-checklist.md`. If the hero fails, use `fix-bad-output.md` before expanding the page. Capture the signature scene's key states when motion is part of the hero. Hero and full-page repairs share the same three-cycle creative budget; do not reset it at each pass.

## Pass 6 — Full Story Build

Build only the sections that advance the sales argument. Reuse the hero’s visual grammar so the page feels authored as one system.

For every major section, require at least one of:

- concrete proof
- useful comparison
- meaningful interaction
- real object or asset
- specific objection resolution
- clear conversion step

Alternate intensity. A spectacular page still needs calm reading zones, clean proof, and obvious action.

## Pass 7 — Browser Critique

Run the page in the real application. Use desktop `1440x900` or larger and mobile around `390x844`.

Perform one batched inspection across:

- hero and every major section
- page rhythm and continuity
- line breaks, contrast, alignment, and cropping
- sticky and scroll-trigger boundaries
- navigation, CTA, forms, and focus states
- console errors, overflow, loading, and reduced motion

Create one grouped punch list ordered by visible impact, with evidence and a cause for each failure. Follow `fix-bad-output.md` until the applicable gates pass or the shared creative budget is exhausted. Compare before/after evidence at matching viewports and scroll states; do not endlessly tweak low-value details.

## Pass 8 — Finish and Handoff

Read `review-checklist.md`. Claiming a successful finished design is blocked by:

- a generic or weak hero
- invented business proof
- broken mobile composition
- decorative motion that fights comprehension
- console errors or broken conversion paths
- a major section that looks unfinished in isolation

Any failed gate triggers `fix-bad-output.md`; an unverified gate cannot be called passed. Numerical scores may prioritize work but cannot authorize acceptance. If the repair budget or a real blocker prevents acceptance, hand off the strongest working result with its specific unmet gate and next practical remedy, without presenting it as finished premium work.

Finish with a concise evidence-based handoff. State what was verified and what was not.
