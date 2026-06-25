# Install - Landing Page Creator

## Option A - Install manually for all Codex/Agents projects on your Mac

Clone or download this repository, then run from the repository root:

```bash
mkdir -p ~/.agents/skills
cp -R landing-page-creator ~/.agents/skills/
```

Then restart Codex to pick up the new skill.

Use it with:

```text
$landing-page-creator crée une landing page pour microwest.ch. Ils vendent et réparent des téléphones. Je veux un hero de fou, des composants 21st.dev-style et une direction ImageGen.
```

## Option B - Install only in one repo

From this repository root:

```bash
mkdir -p .agents/skills
cp -R landing-page-creator .agents/skills/
```

Then launch Codex from that repo.

## Optional - Legacy Codex Desktop fallback

Some Codex Desktop builds still load local skills from `~/.codex/skills`. If `/skills` does not show `landing-page-creator`, mirror the skill there:

```bash
mkdir -p ~/.codex/skills
cp -R landing-page-creator ~/.codex/skills/
```

Then restart Codex.

## Optional - Add project instruction

Copy the contents of `AGENTS-snippet.md` into your repo-level `AGENTS.md`.

## Verify

In Codex CLI / IDE:

```text
/skills
```

or type:

```text
$landing-page-creator
```
