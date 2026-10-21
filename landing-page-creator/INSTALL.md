# Install - Landing Page Creator

## Personal installation

Ask Codex to install the skill from this repository:

```text
$skill-installer Install landing-page-creator from https://github.com/DwennK/landing-page-creator, using the landing-page-creator subdirectory.
```

For a manual installation, clone or download this repository and run from its root:

```bash
mkdir -p ~/.agents/skills
cp -R landing-page-creator ~/.agents/skills/
```

Codex detects skill changes automatically; restart only if the skill or update does not appear. See the [official skill documentation](https://developers.openai.com/codex/skills/).

If an existing installation is already discovered under `~/.codex/skills/landing-page-creator`, update that copy in place instead of creating another. Keep one active copy: duplicate names can appear separately in the skill picker. Preserve any personal edits before replacing files.

## Repository-scoped installation

Copy the skill to the target project's `.agents/skills/landing-page-creator` directory, then launch Codex in that project. Choose personal or repository scope instead of duplicating the same skill in both.

## Official GSAP companion skills

For GSAP work, install the eight skills from [GreenSock's official repository](https://github.com/greensock/gsap-skills) separately:

```text
$skill-installer Install all eight skills from https://github.com/greensock/gsap-skills: gsap-core, gsap-timeline, gsap-scrolltrigger, gsap-plugins, gsap-react, gsap-frameworks, gsap-performance, and gsap-utils, each under skills/.
```

They are technical references, not bundled copies or required runtime dependencies of this skill. The motion reference selects only those needed for the chosen framework and scene. If unavailable, use official GSAP documentation. Installing skills does not install the `gsap` npm package in any project.

## Recommended prompt

```text
$landing-page-creator Build a spectacular, client-specific responsive landing page. Choose the strongest feasible direction automatically, use original ImageGen assets when useful, and create purposeful signature motion. Inspect the real desktop/mobile result, reject generic output, and reconcept failed areas within the repair budget before claiming completion. Preserve existing business behavior and do not pause for minor creative decisions.
```

## Browser checks on macOS

Use installed Google Chrome with an isolated test profile, headless by default. Keep `PLAYWRIGHT_SKIP_BROWSER_DOWNLOAD=1`; do not download Chromium or reuse a personal browser profile. Close task-owned test sessions even when checks fail, and preserve unrelated tabs and review previews. Full rules are in [SKILL.md](SKILL.md#browser-choice-and-session-cleanup).

## Optional project instruction

Copy the relevant guidance from [AGENTS-snippet.md](AGENTS-snippet.md) into your project's `AGENTS.md`.

## Verify discovery

In Codex CLI or IDE, use `/skills` or type `$landing-page-creator`. Confirm that only the intended copy is active.
