# High-Impact Design Patterns

Use this reference for every full landing page creation or redesign. No Compromise Mode is the default.

## No Compromise Mode

Do not aim for “clean and acceptable.” Aim for a first viewport that feels beyond what the client expected.

Default behavior:

- choose the most memorable feasible concept
- build one spectacular signature scene before filling the page
- use ImageGen, real assets, GSAP, Three.js, canvas, or polished motion when they materially improve the result
- remove safe generic patterns even if they look tidy
- accept simpler lower sections if that protects hero quality

Only downgrade ambition when the user explicitly requests a restrained/simple page or the task is a small targeted edit.

## Reference Hunt

When browsing is available, gather 3 references before coding:

1. one hero/art-direction reference from Awwwards, Codrops, a premium studio, or a top product site
2. one component/microinteraction reference from 21st.dev, Magic UI, Figma community, or similar
3. one scroll/motion reference using sticky scenes, pinned timelines, WebGL, GSAP, or canvas

Summarize the principle to reuse from each reference. Do not copy the design.

## One Big Trick

Before implementation, define the one visual idea a client will remember in one sentence.

Strong examples:

- “The phone repairs itself as the visitor scrolls.”
- “The chaotic inbox flows through a glass automation engine and exits as clean decisions.”
- “The property turns into a living control map with trust signals lighting up.”
- “The product assembles from exploded layers around the CTA.”

If the trick cannot be stated clearly, the direction is too weak.

## Hero-First Rule

The hero is the product demo. Build it before the rest of the page and preview it alone on desktop and mobile.

A strong hero needs:

- one custom scene tied to the client’s business
- one memorable interaction or scroll transformation
- one sharp conversion promise
- one premium visual asset or polished visual system
- one CTA that matches the buyer’s next action

If the first viewport could belong to another company, rebuild it.

## Signature Scene Patterns

- **Device X-Ray**: cursor or scroll reveals the inside of a phone, product, building, process, or workflow.
- **Exploded Product View**: parts separate in layers, labels or proof points appear, then reassemble into the outcome.
- **Repair Transformation**: broken object, messy process, or fragmented system becomes clean, fixed, guaranteed.
- **Mission Control**: issues orbit around one calm center and resolve through beams, paths, or status changes.
- **Scroll Tunnel**: each scroll beat moves through a cinematic tunnel from pain to diagnosis to proof to CTA.
- **Local Proof Map**: map or territory becomes a living trust surface with service areas, reviews, and response time.
- **Before/After Lens**: a draggable or cursor-reactive lens reveals the improved state.
- **Trust Beam**: animated paths connect certifications, reviews, guarantees, and CTA into one proof system.

## Component Reality

A premium component is not premium because it is dark, glassy, large, or animated. It is premium when it shows something useful in a memorable way.

Fail patterns:

- large empty frame with small cards
- generic diagnostic/repair/guarantee boxes
- decorative beams or circles that do not encode real proof
- repeated cards where a compact list would be clearer
- big “process” scene without product, price, duration, warranty, review, map, or before/after evidence

Upgrade patterns:

- show the actual object changing state
- expose the diagnostic logic visually
- connect proof points to a CTA
- compare before/after with a drag, scroll, or lens interaction
- turn service steps into a time/price/warranty decision tool
- use real customer concerns as the structure: “Combien ? Combien de temps ? Est-ce garanti ?”

## Scroll Choreography

Plan 3 to 5 beats before coding:

1. **Hook**: show the problem or desired object in a striking scene.
2. **Tension**: reveal what is broken, slow, risky, hidden, or confusing.
3. **Expertise**: show diagnosis, process, internal layers, or decision logic.
4. **Proof**: connect reviews, guarantees, speed, cases, or metrics to the visual story.
5. **Action**: land the visitor on a clear CTA that feels inevitable.

Use sticky sections, pinned scenes, progress rails, masked reveals, parallax layers, object assembly, before/after comparisons, or timeline transforms. Avoid independent sections that do not change the scene.

## Motion Stack Choices

Use the project’s existing stack when possible. Add a dependency only when it creates the signature selling moment.

- **CSS only**: microinteractions, simple parallax, masks, gradients, hover states.
- **Framer Motion / Motion**: React UI choreography, route/section transitions, layout animation.
- **GSAP ScrollTrigger**: pinned scroll stories, precise timelines, scrubbed transforms, cinematic reveals.
- **Three.js/WebGL**: spatial product scenes, device/object depth, particles with meaning, interactive cameras.
- **Canvas**: performant particles, diagnostic scans, cursor fields, custom drawing systems.
- **Spline/Rive/Lottie**: polished imported motion assets when available and brand-appropriate.

Always support reduced motion. Motion must explain, reveal, prove, or sell.

## Asset Escalation

Use ImageGen or real assets when CSS/SVG alone would look cheap.

Escalate when the hero needs:

- a premium product or object render
- a cinematic environment
- a realistic texture or material
- a client-specific metaphor asset
- an editorial hero background
- a device, place, person, vehicle, food, building, garment, or tactile object

Do not use rough handmade SVG for complex objects. SVG is fine for clean masks, paths, grids, diagrams, outlines, beams, and precise UI primitives.

## 21st.dev-Style Scouting

Scout or reproduce the behavior of 2 to 3 premium patterns before implementation:

- background paths with CTA rail
- animated beam proof system
- container scroll animation
- masked image reveal
- scroll progress story
- spotlight card with content purpose
- magnetic CTA
- parallax product stack
- liquid cursor field
- morphing tabs or service cards

Use these as ingredients inside a custom scene. Do not paste a component library layout as the page.

## Microwest Example Direction

For a Swiss phone repair and resale shop:

- Hero: premium phone in a precision repair lab, cracked glass suspended above the device.
- Scroll beat 1: cracks separate and reveal diagnostic scan lines.
- Scroll beat 2: battery, camera, screen, and board layers light up as service choices.
- Scroll beat 3: repair timeline snaps into place with warranty proof.
- Signature component: device x-ray or repair lens.
- CTA: "Réparer mon téléphone" or equivalent local action.
- Asset: ImageGen phone repair lab visual or high-quality CSS/Three.js device scene.

The page should feel like a custom diagnostic experience, not a stack of service cards.
