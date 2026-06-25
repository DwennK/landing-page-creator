# Install - Cinematic Landing Director

## Option A - Install from GitHub

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo DwennK/landing-page-creator \
  --path cinematic-landing-director
```

Then restart Codex to pick up the new skill.

Use it with:

```text
$cinematic-landing-director crée une landing page pour microwest.ch. Ils vendent et réparent des téléphones. Je veux un hero de fou, des composants 21st.dev-style et une direction ImageGen.
```

## Option B - Install manually for all Codex projects on your Mac

From this repository root:

```bash
mkdir -p ~/.codex/skills
cp -R cinematic-landing-director ~/.codex/skills/
```

Then restart Codex to pick up the new skill.

## Option C - Install only in one repo

From the repository root:

```bash
mkdir -p .codex/skills
cp -R cinematic-landing-director .codex/skills/
```

Then launch Codex from that repo.

## Optional - Add project instruction

Copy the contents of `AGENTS-snippet.md` into your repo-level `AGENTS.md`.

## Verify

In Codex CLI / IDE:

```text
/skills
```

or type:

```text
$cinematic-landing-director
```
