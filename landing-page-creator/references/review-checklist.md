# 10K Acceptance Gate

Use this after rendering the real page. A code review alone cannot pass the gate.

## 1. Evidence, Not Self-Scoring

Keep a compact local review record: gate, pass/fail/unverified, viewport and scene state, screenshot or interaction observation, defect, next action. Inspect the actual images; merely creating screenshot files is not review. Use section-size captures as well as page overview. DOM checks cannot establish art direction, and a still image cannot establish motion quality.

For a full ambitious build, every applicable gate must pass:

| Gate | Evidence required to pass |
| --- | --- |
| Clarity | The first viewport states the real offer and next action without waiting for animation. This is an agent inspection, not a measured user comprehension test. |
| Specificity | Point to a client-specific object, content treatment, or visual relationship that would need redesign for an unrelated business. Swapping only logo, nouns, and colors must not reproduce the design. |
| Signature | Name the memorable moment and show its actual rendered state. For motion, inspect initial, intermediate, and resolved states plus real forward/reverse playback. A promised effect in source code is insufficient. |
| Composition | Identify the dominant focal point and intended reading order; inspect real line breaks, scale, crop, contrast, and negative space. The hero must still work in its static or reduced-motion state. |
| Assets | Inspect at display size and both target crops: no distracting generation artifacts, distorted products, baked-in UI text, or placeholder-quality art. The asset must support the offer. |
| Full-page coherence | Every major section advances a specific claim, proof, objection, or action. Repeated visual motifs are intentional; lower sections do not collapse into unrelated filler cards. |
| Mobile | Show the focal point, usable CTA, intentional crop, and signature translation at mobile size. A simpler static scene can pass when it retains the idea and hierarchy. |

Apply the remaining commercial, browser, motion, and technical gates below. Mark genuinely irrelevant criteria not applicable with a reason (for example, no animation in a restrained typographic brief). Do not use this exception to evade a requested cinematic experience. For a targeted edit, judge only the requested surface and affected behavior; preserve explicit user references and brand constraints.

Scores can help prioritize a defect, but a high average or an unsupported adjective such as “premium” never overrides a failure. Missing browser evidence remains unverified, even if the build passes.

## 2. Anti-Template Rejection

A single material failure is enough; do not wait for two clichés to accumulate:

- the hero's entire idea is a generic headline, background effect, and CTA with no authored composition or client-specific content treatment
- swapping the logo, colors, and business nouns leaves a page equally suitable for an unrelated company
- cards, bento panels, stock icons, or ornamental diagrams replace concrete product, proof, comparison, or story
- the requested signature experience reduces to the same fade/slide entrance repeated throughout
- the main asset has obvious defects, misrepresents the real product, or cannot support the intended responsive composition
- desktop spectacle hides an unreadable, broken, or visually anonymous mobile result
- a strong hero leads to unfinished or interchangeable lower sections

These are failures of execution and purpose, not bans on centered text, cards, gradients, or simple layouts. A supplied reference, conservative brand, or typography-led concept can use familiar forms deliberately. Read `anti-ai-slop.md` to diagnose the cause, then `fix-bad-output.md` to repair it.

## 3. Commercial Gate

- The buyer, offer, outcome, and next action are explicit.
- Proof appears near the claims it supports.
- No review, award, client, metric, price, guarantee, or performance claim was invented.
- The CTA language and destination match the real funnel.
- Important objections are answered with concrete content, not empty confidence.
- The final CTA is a culmination of the story, not a generic banner.

## 4. Browser and Responsive Gate

Verify at desktop `1440x900` or larger and mobile around `390x844`:

- no unexpected horizontal scroll
- no clipped headline, CTA, media, sticky scene, or focus ring
- intentional image crop and content order
- navigation remains usable
- touch targets and interactive elements are usable
- every major section looks finished in isolation
- no breakpoint where the cinematic scene obscures comprehension

## 5. Motion Gate

- Motion explains, reveals, proves, transforms, or guides action.
- ScrollTrigger start/end boundaries feel intentional.
- Pinned sections release cleanly in both directions.
- Fast scroll does not leave content invisible or in a broken state.
- Mobile has a designed timeline or a deliberate static fallback.
- Reduced motion exposes the resolved content and keeps CTAs functional.
- No duplicate timelines or obvious leaks appear after navigation or hot reload.
- Scrolling remains acceptably fluid on the available test device.

## 6. Technical Gate

- The target route loads without obvious console errors.
- Primary links, buttons, forms, and CTA paths behave as intended.
- Existing analytics, SEO, consent, and integration behavior was preserved unless intentionally changed.
- Semantics, keyboard focus, alt text, contrast, and reduced motion are handled.
- Generated assets are sensibly optimized.
- Dependencies are justified and framework cleanup is correct.

## 7. Final Critic Questions

- Would the first viewport still justify the project if lower sections were hidden?
- Is there one moment the client can describe from memory tomorrow?
- Could this exact page be sold unchanged to another company?
- Does the spectacular part help the buyer decide?
- Is mobile intentionally art-directed rather than merely stacked?
- Can the agent show the demo without apologizing for any section?

Any answer exposing a concrete weakness is a repair target. Record the evidence and follow `fix-bad-output.md`; do not downgrade a failed gate to a cosmetic suggestion simply to finish.
