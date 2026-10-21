# Anti-AI-Slop Rules

Diagnose generic output from the actual rendered result, then repair its cause. These patterns are warning signs, not blanket bans on common visual primitives or on a faithful implementation of a supplied reference.

## Visual Clichés to Avoid

- endless rounded cards
- blue/purple vague gradients
- glassmorphism without structure
- fake dashboards for non-dashboard businesses
- generic bento grids
- floating icons with no meaning
- random particles
- stock-photo corporate people
- hero headline plus three cards under it
- identical spacing between every section
- too many shadows
- low-contrast gray text everywhere
- fake metrics like “10x faster” without context
- giant empty dark panels
- floating process cards connected by decorative beams
- abstract circles behind cards with no useful meaning
- trust/process diagrams that could fit any business
- oversized containers where less than half the area communicates anything
- “premium” glass cards used as decoration instead of proof

## Fake Premium Component Kill List

Delete or rebuild a component when it matches this pattern:

- a large bordered panel with lots of empty space
- 2-4 floating cards labeled with generic steps
- thin decorative line, beam, orbit, or circle
- no real product, asset, data, proof, comparison, interaction, or business-specific detail

Replace it with one of these:

- real before/after comparison
- scroll-controlled product transformation
- real service timeline with time, price, warranty, and proof
- client-specific map, device, object, case, quote, review, or diagnostic result
- interactive calculator, quote builder, diagnostic lens, x-ray, or exploded view
- compact proof block if there is not enough content for a full scene

## Copy Clichés to Avoid

- Transform your business
- Unlock your potential
- Seamless experience
- Innovative solutions
- Your trusted partner
- Tailored solutions
- Passionate team
- We put customers first
- Cutting-edge technology

## Replacement Pattern

Replace vague claims with concrete conversion messages:

- What pain disappears?
- What result appears?
- What proof supports it?
- What action should the visitor take?
- Why trust this company now?

## Detector Pass

Run this on rendered screenshots, not only source code:

1. Imagine swapping the logo, colors, and business nouns for an unrelated company. If the same scene and story still fit unchanged, specificity has failed. Preserve meaningful typography and real content when judging a typography-led concept.
2. Imagine gradients, glass, and shadows removed. If no composition or business object remains, art direction has failed.
3. Count repeated card shapes. If cards are the default answer to unrelated content, narrative structure has failed.
4. Identify the signature moment. If it cannot be named in one sentence, memorability has failed.
5. Inspect mobile separately. Reject lost hierarchy, accidental crops, unreadable scenes, or broken interactions. Simple stacking can pass when it intentionally preserves the concept, readability, and CTA.

Repair the underlying concept, asset, composition, or content. Do not mask failure with more decoration.
