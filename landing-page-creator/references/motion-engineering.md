# Motion Engineering for Sellable Landing Pages

Use this reference when scroll, cursor, spatial, or cinematic motion is material to the concept.

## Motion Has a Job

Every animation must do at least one useful thing:

- reveal information
- transform problem into outcome
- demonstrate product behavior
- connect proof to a claim
- focus attention on the next decision
- preserve continuity between story beats

If removing an animation does not weaken meaning, hierarchy, or desire, remove it.

## Choose the Lightest Credible Stack

- CSS transitions/keyframes: microinteractions, masks, simple entrances, subtle loops.
- Motion/Framer Motion: component and layout choreography in a project that already uses it.
- GSAP + ScrollTrigger: precise scrubbed timelines, pinning, multi-step transformations, and scene continuity.
- Canvas/WebGL/Three.js: meaningful spatial scenes or generative systems that cannot be achieved credibly with DOM/CSS.
- Rive/Spline/video/image sequence: polished authored assets with an appropriate fallback.

Inspect the existing stack first. Add weight only for the signature selling moment.

## Official GSAP Skills

When GSAP is selected, locate the following skills by name in the available skill catalog and read the installed files needed for the actual work. The links below point to their official upstream sources for portable documentation. Do not load all eight by default or copy their demo animation as the creative concept.

- [gsap-core](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-core/SKILL.md): tweens, easing, responsive and reduced-motion setup.
- [gsap-timeline](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-timeline/SKILL.md): sequencing, labels, coordinated scene states.
- [gsap-scrolltrigger](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-scrolltrigger/SKILL.md): scrub, pinning, refresh, scroll lifecycle.
- [gsap-plugins](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-plugins/SKILL.md): only the plugins the scene needs, such as SplitText, Flip, or MorphSVG.
- [gsap-react](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-react/SKILL.md): React/Next.js lifecycle and scoped cleanup.
- [gsap-frameworks](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-frameworks/SKILL.md): Vue/Nuxt, Svelte, and other framework lifecycles.
- [gsap-performance](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-performance/SKILL.md): heavy scenes, many animated elements, or observed jank.
- [gsap-utils](https://github.com/greensock/gsap-skills/blob/main/skills/gsap-utils/SKILL.md): mapping, clamping, snapping, and reusable math helpers when needed.

These are technical references; the landing-page concept and rendered acceptance gates still determine the design. Use only the relevant framework guide. Respect the existing stack and explicit user choices. If a referenced skill is unavailable, use official GSAP documentation and report that limit without silently installing dependencies.

## Motion Storyboard

Before implementation, define:

- trigger element and start/end positions
- initial, intermediate, and resolved visual states
- whether motion is scrubbed, triggered, looped, or input-driven
- which content becomes readable at each state
- how the timeline hands off to the next section
- mobile behavior
- reduced-motion equivalent
- failure fallback if the advanced effect does not load

Use one dominant timeline. Supporting interactions should be quieter.

## GSAP and ScrollTrigger Rules

- Register plugins only in the browser/client environment.
- Scope animations to the component and revert/kill them on unmount.
- Avoid duplicate triggers during hot reload or route navigation.
- Prefer transforms and opacity for frequently updated animation.
- Calculate distances from real element or viewport dimensions; do not rely on one desktop pixel constant.
- Refresh ScrollTrigger after fonts, generated images, or layout-critical assets settle.
- Keep pinned scenes bounded and test what enters and exits before and after the pin.
- Avoid nested pinning and custom scroller proxies unless the project truly uses a custom scroller.
- Use framework lifecycle primitives correctly: GSAP context or cleanup in React, `onMounted`/`onBeforeUnmount` in Vue/Nuxt, and client-only guards for SSR.
- Use match-media logic to create a specific mobile timeline or disable the cinematic sequence when it harms clarity.

## High-Value Signature Patterns

Use a pattern only after adapting it to the client’s business object and proof:

- pinned object transformation across three to five scroll beats
- before/after mask or lens tied to a concrete outcome
- exploded object that reassembles around proof labels
- typography-to-object transition that reveals the offer
- continuous object handoff between hero and proof section
- scroll-controlled camera move through a real process
- local map, timeline, or document system that resolves buyer anxiety
- image sequence with a static poster fallback

Avoid a collection of unrelated parallax effects, flying text, magnetic elements, cursors, and marquees competing for attention.

## Performance Floor

- Keep the main thread responsive during scroll.
- Animate compositor-friendly properties where possible.
- Avoid layout reads and writes on every frame.
- Pause loops, video, canvas, and observers when offscreen when practical.
- Compress imagery and preload only the critical first-frame assets.
- Cap device-pixel ratio or visual complexity for canvas/WebGL on weaker devices.
- Test real scrolling, not only a still screenshot.
- Preserve readable content and functional CTAs before animation initializes.

Aim for visually stable, fluid motion on a representative device. If the effect stutters, simplify it before adding another effect.

## Accessibility and Input

Respect `prefers-reduced-motion`. The fallback should show the resolved visual state, keep all content available, and remove pinning/scrubbing that traps the user.

Do not make essential content hover-only. Support keyboard focus and touch. Custom cursors must never hide the native ability to click, select, or navigate.

## QA

Test:

- desktop at `1440x900` or larger
- mobile around `390x844`
- fast and slow manual scroll
- refresh while mid-route and direct route entry
- resize or orientation change when relevant
- reduced motion
- navigation away and back for duplicate triggers
- console warnings/errors and animation cleanup

Follow [Browser choice and session cleanup](../SKILL.md#browser-choice-and-session-cleanup): on macOS, run installed Chrome headlessly with an isolated test profile, without downloading a browser. Close task-owned test sessions after QA, including failures, and preserve unrelated user windows. Use the in-app Browser for interactive review.
