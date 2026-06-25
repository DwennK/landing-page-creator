# Landing Page Creator Skill

Public Codex skill repository for `landing-page-creator`.

## Install

Install the skill as a personal Codex/Agents skill:

```bash
mkdir -p ~/.agents/skills
cp -R landing-page-creator ~/.agents/skills/
```

Then restart Codex to pick up the new skill.

Some Codex Desktop builds still load local skills from `~/.codex/skills`. If `/skills` does not show `landing-page-creator`, mirror it there too:

```bash
mkdir -p ~/.codex/skills
cp -R landing-page-creator ~/.codex/skills/
```

## Local Editing

The editable skill source is in:

```text
landing-page-creator/
```

After editing, commit and push changes, then reinstall or update the local copy in `~/.agents/skills/landing-page-creator`.
