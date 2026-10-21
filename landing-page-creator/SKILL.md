---
name: landing-page-creator
description: Create or redesign a premium, client-sellable landing page, homepage, or hero in autonomous 10K One-Shot mode. Use for Awwwards-level art direction, cinematic product storytelling, original ImageGen assets, GSAP/ScrollTrigger motion, signature interactions, conversion copy, and browser-based desktop/mobile visual QA. Not for dashboards, routine product UI, or tiny style fixes.
---

# Landing Page Creator — 10K One-Shot

## Mission

Produce a page that can credibly be presented as high-end agency work: unmistakably specific to the client, commercially clear, visually memorable, technically solid, responsive, and polished in a real browser.

“10K” is the quality tier, not a price guarantee. Spectacle alone does not pass. The result must sell the offer, preserve trust, and survive desktop and mobile review.

## Default Mode: One User Prompt, Full Production Run

For any full landing-page creation or redesign, use **10K One-Shot mode** unless the user explicitly asks for collaboration, restraint, or a small targeted edit.

In One-Shot mode:

- make reasonable assumptions from the brief, repository, current site, brand assets, and market
- do not pause for concept approval when the required context can be inferred safely
- explore multiple directions internally, score them, select one, and continue automatically
- do not dump internal concept lists, contracts, or checklists into the chat unless requested
- create the assets, implement the page, run the app, inspect it, fix it, and verify it
- surface a question only when a missing choice would materially alter the business, brand, or architecture and cannot be inferred

One-shot does not mean one implementation pass. It means one user handoff with several bounded internal production passes.

## Reject Generic Work Before Calling It Finished

Read `references/review-checklist.md` before implementation to establish the acceptance evidence, then apply it to the rendered hero and completed page. A successful build, expensive-looking effects, or a self-awarded score cannot establish visual quality.

For an ambitious full build, reject a transferable template, an anonymous hero, a missing signature moment, or a mobile composition that loses the idea. Record the visible failure and change its cause: concept, asset, composition, or choreography. Do not count a new gradient, reveal animation, or larger heading as a new concept.

Use `references/fix-bad-output.md` to continue automatically through up to three substantial creative repair cycles across the task. Stop earlier only when the applicable gates pass with evidence. If the limit or a real blocker prevents acceptance, preserve the strongest working version and explicitly report the unmet quality gate; never relabel it as spectacular. This budget bounds creative rework, not required functional fixes. Respect explicit user budgets, references, conservative brands, and targeted scope.

## Load References Progressively

For every full build or redesign, read `references/creative-production-mode.md` first and follow it as the production runbook.

Then load only what the current pass needs:

- concept selection: `references/concept-collision-engine.md`
- art direction and signature-scene ideas: `references/high-impact-design-patterns.md`
- hero composition: `references/hero-patterns.md`
- custom component mutation: `references/component-bank.md`
- generated visual assets or a full-page visual comp: `references/imagegen-prompts.md`
- GSAP, ScrollTrigger, scroll storytelling, and performance: `references/motion-engineering.md`
- generic-output detection: `references/anti-ai-slop.md`
- repair after a failed visual review: `references/fix-bad-output.md`
- final acceptance: `references/review-checklist.md`

## Context Modes

Choose the mode from the request; do not ask the user to name it.

### Full creation

Own art direction, copy structure, assets, motion, implementation, and QA. Use the complete One-Shot pipeline.

### Redesign in an existing repository

Preserve proven business behavior while replacing weak presentation. Before editing, inspect the stack, routes, content model, analytics, forms, SEO metadata, URLs, and current brand assets. Do not casually break or replace working integrations.

### Targeted hero or section

Apply the same quality bar only to the requested surface. Do not expand into a full-site redesign.

### Conservative brand

Lower visual density, not quality. Prefer editorial composition, tactile imagery, precise typography, and subtle motion over WebGL or spectacle that conflicts with the brand.

## Internal Design Read

Before coding, form one compact internal sentence:

> This page should make [buyer] feel [emotion] because [specific promise], proven by [evidence], inside a [visual world].

Set three internal dials. Defaults for a “site de dingue” request:

- `DESIGN_VARIANCE = 8/10` — original composition without sacrificing comprehension
- `MOTION_INTENSITY = 8/10` — one cinematic sequence plus restrained support motion
- `VISUAL_DENSITY = 4/10` — enough richness to feel authored, enough space to feel premium

Adapt these to the offer and brand. Never make the page harder to understand merely to maximize a dial.

## Creative Director Autopilot

Before implementation:

1. Extract the real offer, audience, buyer anxiety, desired action, proof, and brand constraints.
2. Generate raw concept collisions and three viable creative directions internally.
3. Score the directions for business specificity, three-second clarity, visual originality, conversion strength, technical feasibility, asset feasibility, and mobile viability.
4. Select the strongest feasible direction automatically. Prefer the boldest direction that still communicates clearly.
5. State the memorable idea in one line: **the one big trick**.
6. Define the hero scene, scroll story, asset plan, motion beats, proof placement, CTA path, and mobile adaptation.
7. Start implementation without waiting for approval.

Reject a direction if it is primarily a layout, depends on generic cards or gradients, could serve another company, needs fabricated claims, or has no strong mobile translation.

## The Sellable Page Contract

Every full page must have all of the following:

- a promise understood within roughly three seconds
- a first viewport composed as a custom scene, not a centered template hero
- one client-specific signature moment worth showing in a sales call
- one continuous visual or argumentative scroll story
- original or real visual assets strong enough for the concept
- concrete proof and objection handling without invented metrics
- a primary CTA that matches the buyer’s real next step
- intentional desktop and mobile compositions
- accessible semantics, visible focus, useful alt text, and reduced-motion behavior
- no obvious console errors, horizontal overflow, broken interactions, or dead CTA paths

Fewer excellent sections beat a long page of filler. Lower sections may be calmer than the hero, but none may look unfinished in isolation.

## Hero and Signature Scene

Invest most creative attention in the first viewport and the scene that continues from it.

The hero needs:

- a sharp, specific headline and supporting line
- a visible, commercially useful CTA
- a real visual object, environment, image, typographic construction, or interactive system
- depth through foreground, midground, and background when the direction is cinematic
- proof or reassurance embedded near the decision, not hidden far below
- a signature interaction whose purpose can be explained in one sentence

Do not build lower sections to hide a weak hero. Build the hero first, inspect it at desktop and mobile sizes, repair it if necessary, then expand the story.

## Assets: Comp-First When It Helps

Use real client assets first when they are good enough. Use ImageGen when custom photography, renders, textures, environments, or metaphor assets would materially raise the result.

When image generation is available and the page needs strong original imagery:

1. Generate a wide visual direction comp or hero key art before detailed implementation.
2. Use that comp as an art-direction reference, not as a screenshot pasted over the product.
3. Generate isolated production assets with deliberate negative space and no embedded text.
4. Implement typography, UI, interactions, and responsive behavior in code.

If image generation is unavailable, create the strongest feasible code-first system with real assets, typography, masks, SVG primitives, canvas, or 3D. Never substitute weak homemade illustration merely to say an asset exists.

## Motion and GSAP

Motion must reveal, transform, explain, prove, or guide action. It is not decorative confetti.

Use the project’s existing motion stack when adequate. For a concept built around precise scroll choreography, pinned scenes, scrubbed transformations, or object continuity, use GSAP with ScrollTrigger when the project can support it. Load `references/motion-engineering.md` before implementation.

Required behavior:

- one dominant motion system, not competing effects everywhere
- transforms and opacity for frequent animation where possible
- cleanup on unmount and no duplicate triggers during development
- specific mobile choreography, not a broken compressed desktop timeline
- reduced-motion fallback that preserves the story and CTA
- progressive enhancement: content remains understandable without animation

Add WebGL, Three.js, canvas, Rive, Spline, or image sequences only when they create the signature selling moment and have a credible fallback.

## Content and Truth

Use real supplied content, repository content, or verified public information. Improve positioning and wording, but do not invent awards, clients, reviews, prices, guarantees, performance claims, or metrics.

If exact proof is missing, use honest qualitative copy and leave clearly localized placeholders only where the project convention supports them. A spectacular lie is not a sellable design.

## Implementation Discipline

- adapt to the existing framework and conventions; do not force a new stack
- inspect dependencies before adding packages
- preserve existing links, analytics, forms, consent flows, SEO, and accessibility unless the task explicitly changes them
- use tokens or variables for color, type, spacing, radii, depth, and motion
- keep components editable and boundaries understandable
- optimize generated assets and avoid needless payload
- avoid fragile absolute positioning without responsive constraints
- avoid animation that blocks navigation or delays the CTA

## Browser Proof Is Mandatory When Available

Do not call a page premium without seeing it rendered.

For a full build:

1. Run the real app and target route.
2. Inspect at least one desktop viewport at `1440x900` or larger.
3. Inspect a representative mobile viewport around `390x844`.
4. Capture or inspect the hero and every major section, not only the full-page thumbnail.
5. Check console errors, overflow, text wrapping, stacking, focus states, CTA paths, motion timing, and reduced motion.
6. Apply `references/review-checklist.md`, recording pass, fail, or unverified with the relevant screenshots and interaction observations.
7. If a gate fails, follow `references/fix-bad-output.md`: repair the cause, compare the same viewport and scene states, and repeat within the shared creative repair budget. Recheck affected interactions after each change.

### Browser choice and session cleanup

- Use Playwright for repeatable scripted checks and screenshots; use the in-app Browser for interactive visual inspection and user-facing review.
- On macOS, use the installed `/Applications/Google Chrome.app` with `chromium.launch({ channel: 'chrome', headless: true })` and fresh browser contexts. Use a temporary or dedicated test profile, never the user's personal profile, cookies, or signed-in sessions without explicit authorization.
- Keep `PLAYWRIGHT_SKIP_BROWSER_DOWNLOAD=1` for local checks. Do not download Chromium, its headless shell, or Chrome for Testing. If installed Chrome is unavailable, use the in-app Browser when suitable or report the verification limit. CI may install its own browsers.
- Default automated checks to headless mode to avoid opening desktop windows. Use a visible test window only when the user requests it or a specific check requires it. Set the viewport before interacting with the page.
- Reuse a suitable task-owned test session across checks. With the Playwright CLI wrapper, select Chrome explicitly and use a uniquely named, isolated session; close that specific session after QA, including after a failed check.
- For scripts, place cleanup in `finally`: close owned contexts and ensure the launched browser is closed even if a check or context cleanup fails. Close task-created test windows and tabs when finished unless the user asked to keep them open; preserve the in-app preview intended for user review.
- Never quit Chrome globally, use broad process-kill commands, or close unrelated sessions or user tabs. If cleanup fails, report the remaining task-owned session instead of silently leaving it behind.

If browser proof is unavailable, state exactly what remains unverified.

## Final Delivery

Lead with the outcome. Briefly report:

- the chosen creative idea and signature interaction
- what was created or changed
- the desktop/mobile and functional checks actually performed
- any real limitation, placeholder, or unverified item
- how to run or review the page

Do not expose long internal deliberation. Do not claim Awwwards quality, production readiness, or a monetary value as a fact; show the concrete evidence that supports the quality tier.
