---
name: landing-page-creator
description: Create premium landing pages, homepages, and hero sections with hero-first design, one memorable visual trick, client-specific art direction, scroll-story motion, ImageGen visuals, and anti-AI-slop gates. Use for Awwwards-level pages, 21st.dev-style components, cinematic heroes, B2C pages, SaaS/product pages, and conversion-focused redesigns.
---

# Landing Page Creator

## Mission

Create landing pages with exceptional art direction, memorable hero sections, uncommon component composition, strong conversion logic, and production-ready frontend implementation.

The goal is not a clean template. The goal is a custom, cinematic, brand-specific landing page that feels closer to high-end agency work than generic AI-generated UI.

No Compromise Mode is the default for every landing page creation or redesign task. Do not wait for the user to ask for “insane” or “Awwwards-level”; assume the first version must be surprising, premium, and directly sellable.

For every full landing page creation or redesign, always use Creative Production Mode: read `references/creative-production-mode.md` and work in passes instead of building the whole page in one shot.

## Non-Negotiable Rule

Do not start by coding.

Always follow this order:

1. Understand the business and conversion goal.
2. Create multiple creative directions.
3. Choose one strong visual metaphor.
4. Define the one big visual trick people will remember.
5. Invent or scout component patterns and references.
6. Decide the hero asset strategy before implementation.
7. Generate or request ImageGen visuals before building the hero when useful.
8. Design and build the hero first.
9. Preview the hero on desktop and mobile.
10. Pass the mandatory gates before building the full page.
11. Implement the selected direction.
12. Preview and polish.
13. Review against the mandatory gates and anti-slop checklist.

If the user explicitly asks to code immediately, still do a very short creative direction pass first unless the task is a small targeted edit.

## Quality Bar

The result must feel:

- custom
- premium
- memorable
- conversion-focused
- emotionally clear
- visually coherent
- technically clean
- mobile-polished
- non-generic

Avoid:

- generic SaaS dashboard heroes
- random gradient blobs
- vague floating cards
- decorative beam-and-card diagrams
- large empty panels pretending to be premium UI
- meaningless fake metrics
- cheap glassmorphism
- over-rounded cards
- stacked template sections
- random icons
- lorem ipsum
- AI-looking bento grids
- decorative animation with no purpose
- generic headlines like “Transform your business”

## Mandatory Gates

Treat these gates as hard blockers. If any gate fails, stop expanding the page and revise the concept, hero, component, copy, or interaction until it passes.

### No Compromise Gate

For full landing page creation or redesign, default to the most memorable feasible execution, not the safest clean layout. Prefer one extraordinary signature scene over a complete but average page.

Do not downgrade to a generic hero unless the user explicitly asks for a conservative/simple page or the task is only a small targeted edit.

### One Big Trick Gate

Before coding, write the one-liner for the visual trick the client will remember.

Examples: “the phone repairs itself on scroll,” “the building turns into a living control map,” “the invoice chaos flows through a glass automation engine,” “the product assembles from exploded layers.”

If there is no one-liner, the concept is not strong enough.

### Hero Production Budget Gate

Spend most of the creative effort on the first viewport and signature scene. Lower sections can be simpler; the hero cannot.

For full landing pages, allocate roughly 60-70% of design attention to hero composition, asset quality, motion, copy, CTA, and mobile hero polish before expanding the page.

### Hero-First Build Gate

Build the hero before the rest of the page. Do not fill out generic sections to compensate for a weak first viewport.

Pass only after desktop and mobile hero preview. If the hero does not look client-ready, rebuild the hero before continuing.

### Hero Gate

The hero must make the client feel they are seeing a custom, high-value demo.

Pass only if:

- the hero is the most impressive part of the page
- the first viewport contains a custom visual scene, not a centered text block
- the scene connects directly to the client’s business, product, service, or proof
- the primary CTA is visible, specific, and commercially useful
- the above-the-fold experience would still feel premium with the rest of the page hidden

Fail if it is only headline, subheadline, gradient, floating cards, fake metrics, and CTA.

### Visual Ambition Gate

Choose an execution tier before coding:

- **Premium static**: strong composition, real assets, refined typography.
- **Cinematic interactive**: layered scene, cursor/scroll response, custom transitions.
- **Awwwards-grade**: sticky scroll story, GSAP/ScrollTrigger or equivalent, WebGL/Three.js/Spline/Rive/canvas if the concept needs depth, physics, object motion, or product presence.

Default to Cinematic interactive or Awwwards-grade for full landing page creation/redesign. Use Premium static only when it better fits the brand or the user explicitly wants restraint.

### Anti-AI Gate

Reject anything that looks like a generic AI landing page.

Fail immediately on this pattern:

- centered hero
- blurred gradient background
- three floating cards
- features section
- process section
- testimonials section
- final CTA

Replace it with a client-specific scene, signature component, proof moment, and scroll/hover mechanic.

### Component Reality Gate

Every visible component must earn its space. Fail any section that is mostly an empty dark/glass panel, floating cards, abstract circles, beams, fake diagrams, or vague process boxes without a concrete client-specific visual, useful data, or meaningful interaction.

If a component cannot be explained as “this helps the buyer decide by showing [specific proof/process/outcome],” delete it or rebuild it around real content, real assets, or a stronger interaction.

### Client-Specific Gate

The page must feel impossible to reuse for a random business.

Pass only if the hero, metaphor, copy, imagery, components, icons, proof, and CTA all name or imply the real client’s offer, market, and buyer anxiety. For a repair shop, show repair, diagnosis, devices, warranty, speed, trust, and local service. For another market, create equivalent domain-specific proof.

### Scroll Story Gate

Do not build a stack of generic sections. Build a scroll story.

Pass only if scrolling changes the scene or argument in a meaningful way: broken to fixed, unknown to diagnosed, risk to trust, scattered to organized, before to after, hidden system to visible proof, or problem to outcome. At least one section must have a scroll-linked, sticky, progressive, reveal, compare, timeline, or transformation mechanic.

### Motion Library Gate

Use serious motion tools when they materially improve the result. If the chosen concept depends on scroll choreography, use GSAP ScrollTrigger, Framer Motion/Motion, CSS scroll timelines, or the project’s existing motion stack. If it depends on a spatial product, device, map, particle field, or 3D scene, use Three.js/WebGL/Spline/Rive/canvas or a high-quality CSS 3D simulation.

Do not add heavy libraries for decorative motion. Do add them when they create the signature selling moment. Respect reduced-motion settings.

### Signature Component Gate

Invent at least one custom component that could be shown in a sales call.

It must combine a client-specific metaphor, content function, interaction mechanic, and conversion purpose. Examples: device x-ray, repair timeline, before/after slider, trust beam, service orbit, diagnostic scanner, quote builder, guarantee rail, process tunnel, proof constellation.

### Asset Escalation Gate

Do not accept weak homemade visuals. If the hero needs a product, object, place, person, cinematic background, texture, or premium metaphor asset, use ImageGen, real client assets, high-quality photography, WebGL/canvas, or a polished CSS/SVG system.

Avoid rough hand-drawn SVGs, distorted device mockups, fake app screenshots, messy illustration, or random abstract shapes. SVG is acceptable only when it is clean, deliberate, and production-grade.

### 21st.dev Scouting Gate

Before implementing, scout or invent at least 2-3 premium interaction patterns inspired by 21st.dev, Magic UI, Codrops, Awwwards, Figma community, or similar sources when network access is available. Use them as raw material, not copied templates.

If browsing is available, perform a short reference hunt before coding: one hero/art-direction reference, one component/microinteraction reference, and one scroll/motion reference.

### Sellable Demo Gate

Before final delivery, ask: “Could I show this demo to the client without apologizing for the hero, generic sections, weak mobile, or missing business specificity?”

Pass only if the answer is yes after desktop and mobile preview. If not, iterate on the weakest gate first, usually the hero.

### Screenshot Critic Gate

After preview, judge the hero screenshot as an art director. If the first viewport does not feel surprising, specific, polished, and worth paying for, revise only the hero and signature scene before touching lower sections.

### Section Screenshot Gate

Capture or inspect each major section, not only the hero. Any section that looks sparse, unfinished, generic, low-effort, misaligned, oversized, or hard to sell must be rewritten before delivery.

## Phase 1 — Business Reading

Identify:

- what the company sells
- who the buyer is
- what the buyer wants
- what pain the buyer feels
- what trust barriers exist
- what action the page should drive
- what the market expects visually
- what the page must make the visitor feel within 3 seconds

Write one sentence:

> This landing page should make [target] feel [emotion] because [core promise].

## Phase 2 — Creative Directions

Create 5 radically different directions before implementation.

Each direction must include:

- concept name
- emotional angle
- visual metaphor
- hero layout
- signature component idea
- motion idea
- ImageGen asset idea
- conversion logic
- why this is not generic

Then select the strongest direction and explain why.

Do not choose the safest direction by default. Choose the one with the best balance of memorability, clarity, conversion, brand fit, and feasibility.

## Phase 3 — Visual Metaphor

Every premium landing must be built around one clear metaphor. Read `references/high-impact-design-patterns.md` for examples.

The metaphor must guide:

- hero visual
- section rhythm
- component shapes
- motion language
- copywriting
- CTA placement
- image style

If there is no metaphor, stop and create one.

## Phase 4 — Component Invention Framework

Do not only copy component libraries. Invent signature components by combining:

1. **Metaphor** — what world does the visitor enter?
2. **Content function** — what does this component explain or prove?
3. **Interaction mechanic** — hover, scroll, drag, cursor, reveal, timeline, compare, focus, spotlight, orbit, x-ray, morph.
4. **Visual primitive** — path, beam, glass panel, card, canvas, SVG, mask, parallax layer, device frame, timeline, grid, marquee, 3D tilt.
5. **Conversion purpose** — clarity, trust, desire, proof, objection removal, CTA.

A great component must pass this sentence:

> This component helps the user understand [message] by making them interact with [metaphor].

If it only looks cool but says nothing, remove it.

## Phase 5 — Component Scouting

Use 21st.dev/Magic UI-style components as raw material, not templates.

Read `references/component-bank.md` when choosing component patterns.
Read `references/high-impact-design-patterns.md` for Awwwards-grade hero, motion, ImageGen, GSAP, Three.js, and scroll-story ideas.
Read `references/creative-production-mode.md` for full-site concept, section storyboard, asset plan, motion prototype, and QA workflow.

Rules:

- Do not copy component libraries blindly.
- Compose components into a custom scene.
- Every animation must support the metaphor.
- Every component must increase clarity, trust, desire, proof, or conversion.
- Prefer one unforgettable hero component over ten average components.

## Phase 6 — Signature Hero Requirements

The hero must be the page’s strongest section.

It must include:

- a sharp, specific headline
- a precise subheadline
- one primary CTA
- one secondary CTA or reassurance
- a memorable visual metaphor
- premium typography
- strong spacing
- one signature interaction
- clear above-the-fold conversion logic

The visitor must understand the promise in less than 3 seconds.

Read `references/hero-patterns.md` before selecting the final hero pattern.

## Phase 7 — ImageGen Direction

Use image generation when the page needs:

- a cinematic hero background
- product/service illustration
- abstract brand visual
- premium device scene
- custom texture
- atmospheric image
- visual metaphor asset
- before/after visual
- icon style exploration
- campaign imagery

If an image generation tool is available, invoke it explicitly when useful. If `$imagegen` is available, use `$imagegen`. If not available, produce precise image prompts and tell the user where to place the generated assets.

Decide the hero asset strategy before building the hero: ImageGen, real assets, CSS/SVG, canvas, 3D, or hybrid.

Before generating, create 3 image prompt options.

If the hero would otherwise rely on a weak fake SVG, generic cards, fake dashboards, or abstract gradients, escalate to ImageGen or a better visual system before implementation.

Each ImageGen prompt must define:

- subject
- composition
- lighting
- material
- mood
- brand fit
- camera angle
- negative constraints
- usage in the landing page

ImageGen prompts must avoid:

- generic stock photo look
- fake smiling corporate people
- unreadable text inside images
- random tech holograms
- cliché AI gradients
- messy details
- irrelevant objects

## Phase 8 — Landing Structure

Use strong rhythm.

Recommended structure:

1. Hero — promise + metaphor + CTA
2. Pain — show the current frustration clearly
3. Transformation — show the better future
4. Services/Product — explain the offer visually
5. Proof — trust signals, cases, reviews, numbers, brands
6. Process — how it works in simple steps
7. Differentiation — why this company is better
8. Objections — answer doubts
9. Final CTA — strong, simple, direct

Do not use generic section labels unless the section itself is distinctive.

## Phase 9 — Copywriting Rules

Copy must be:

- specific
- concrete
- direct
- emotionally sharp
- conversion-focused
- adapted to the market

Avoid:

- “we are passionate”
- “tailored solutions”
- “innovative services”
- “your trusted partner”
- “transform your business”
- “seamless experience”
- “unlock your potential”

Every headline must either:

- name a pain
- promise an outcome
- create curiosity
- prove credibility
- reduce friction
- push action

## Phase 10 — Implementation Rules

Build with the existing project stack and conventions.

Code must be:

- componentized
- responsive
- accessible
- performant
- easy to edit
- visually polished
- production-ready

Use dependencies only if justified.

Prefer:

- clean reusable components
- CSS variables or design tokens
- strong layout primitives
- accessible buttons and links
- reduced-motion support
- mobile-first polish
- browser preview verification

For ambitious scroll or 3D concepts, justify the motion stack explicitly. Use GSAP/ScrollTrigger, Three.js/WebGL, Framer Motion/Motion, canvas, Spline, or Rive when the concept needs them and the project can support them.

When working in React, Nuxt, Vue, or plain HTML/CSS, adapt the implementation to the existing structure. Do not force a new stack.

## Phase 11 — Browser Polish Loop

After implementation:

1. Run the app.
2. Open the page in a desktop-sized viewport.
3. Inspect the hero first.
4. Inspect mobile.
5. Run the Hero-First, Hero, Visual Ambition, Anti-AI, Client-Specific, Scroll Story, Motion Library, Signature Component, Component Reality, Asset Escalation, 21st.dev, Sellable Demo, Screenshot Critic, and Section Screenshot gates.
6. Fix spacing, typography, contrast, overflow, motion issues, and weak states.
7. Remove anything that looks generic.
8. For full builds, run at least two screenshot critique loops before delivery.

Do not claim the design is premium without looking at it if a browser/preview is available.

## Phase 12 — Review Checklist

The page fails if:

- the hero could fit any random company
- the visual metaphor is unclear
- the layout looks like a template
- the page is just stacked sections
- a section is an empty decorative panel with floating boxes
- the animations are decorative but pointless
- the copy is generic
- the mobile version feels secondary
- the CTA is weak
- the page lacks trust
- the design looks AI-generated

The page passes only if:

- the hero is memorable
- the metaphor is visible
- the offer is clear
- the design feels custom
- the interactions are polished
- the page is conversion-focused
- the code is clean
- the mobile result is strong
- the visual identity fits the brand

## Default User Flow

When the user says something like:

“Use this skill and create a landing page for [company].”

Do this:

1. Inspect the existing project if available.
2. Read the existing website if a URL is provided and browser/network access is available.
3. Produce 5 creative directions.
4. Pick the strongest one.
5. Read relevant references for hero, components, ImageGen, high-impact design, and creative production.
6. Define the one big trick, section storyboard, asset plan, signature scene, motion stack, hero budget, and scroll story before coding.
7. Decide the hero asset strategy: ImageGen, real assets, CSS/SVG, canvas, 3D, or hybrid.
8. Do a short reference hunt if browsing is available.
9. If the hero would be stronger with ImageGen, create 3 prompt options and invoke ImageGen before implementation.
10. Build and preview the hero first.
11. Check the gates on the hero and revise if needed.
12. Implement the full page.
13. Preview the full page.
14. Improve any gate failure, starting with the hero.
15. Summarize what changed and how to review it.
