# Agent Skills

A repository of Agent Skills. Each skill is a self-contained folder under `skills/`, built around a `SKILL.md`: YAML frontmatter (`name` + `description`) followed by Markdown instructions.

Everything is plain text, with no scripts, no build step, and no fields owned by a single vendor, so any tool that reads `SKILL.md` can load it.

## Layout

```
.
├── README.md
├── .gitignore
└── skills/
    └── say-it-straight/    # folder name matches the name in frontmatter
        └── SKILL.md
```

## Adding a skill

1. Create a folder under `skills/` using lowercase letters, digits, and hyphens.
2. Add `SKILL.md` with at least `name` and `description` in the frontmatter. Keep `name` identical to the folder name.
3. Write a `description` that says what the skill does and when to use it. Tools rely on it to decide whether to load the skill; concrete trigger conditions make matching reliable.
4. Put images, templates, or reference material in the same folder and link to them with relative paths.

```
skills/
└── my-new-skill/
    ├── SKILL.md
    └── references/
        └── example.md
```

Keep the frontmatter to the minimum field set. Vendor-specific fields force edits when the same skill moves to another tool; portability comes from that restraint.

## Using the skills in AI tools

Run these from the repository root. Symlinks take the least effort: edit once here, and every linked skills directory sees the change.

```bash
# Claude Code (global)
mkdir -p ~/.claude/skills
ln -s "$(pwd)"/skills/* ~/.claude/skills/

# Claude Code (project only)
mkdir -p .claude/skills
ln -s "$(pwd)"/skills/* .claude/skills/
```

Other options:

- **Claude web / desktop**: zip a single skill folder and upload it in the Skills settings.
- **Other tools that support `SKILL.md`**: copy the folders under `skills/` into that tool's skills directory, keeping the folder names.
- **Tools that only accept a prompt**: paste everything after the second `---` in `SKILL.md` into the system prompt or custom instructions.
