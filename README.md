# Landing Page Creator

A Codex skill for ambitious, client-specific landing pages: art direction, original ImageGen assets, purposeful scroll choreography, and rendered desktop/mobile review.

## What it does

- Chooses a creative direction autonomously, then builds and reviews the hero before expanding the page.
- Rejects interchangeable templates, weak imagery, repetitive effects, and unfinished lower sections using rendered evidence.
- Reworks the concept, assets, composition, or motion through up to three substantial creative repair cycles, shared across the task.
- Checks responsive behavior, conversion paths, accessibility, reduced motion, and animation cleanup.
- Reports failed or unverified criteria honestly when the quality target cannot be reached.

“10K One-Shot” describes the ambition and a single user handoff. It does not guarantee a price, an award, or a spectacular result on every brief. Targeted changes and restrained brands retain their scope.

## Install and use

Follow the [installation guide](landing-page-creator/INSTALL.md) for personal or project installation, updates, and discovery checks. Keep one active copy of the skill.

```text
$landing-page-creator Create a spectacular landing page for [business]. Choose the direction, generate original imagery when useful, build a meaningful signature interaction, and verify the desktop/mobile result. Reject generic output and rework its cause before claiming completion.
```

## GSAP companions

The skill routes animation work to the eight [official GSAP skills](https://github.com/greensock/gsap-skills) when installed. They remain separate upstream-maintained skills; installation instructions are in the [guide](landing-page-creator/INSTALL.md#official-gsap-companion-skills).

## Browser behavior

On macOS, scripted checks use installed Chrome, an isolated test profile, and headless mode by default. No local Chromium download or personal profile access. Task-owned test sessions are closed after checks, including failures; unrelated tabs and the review preview are preserved.

## Editing

The source is in `landing-page-creator/`. Keep the entrypoint, supporting references, installation instructions, and UI metadata consistent. Review and validate changes before committing, then update the existing installed copy while preserving personal edits.
