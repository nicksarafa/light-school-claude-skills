# Agent Instructions

## Skill Zipping

- Every time a new skill is added to the `skills/` directory, create a `.zip` file of that skill inside the skill's folder. For example, if a skill called `my-skill` is added, run `cd skills/my-skill && zip -r my-skill.zip . -x "*.zip"` to create `skills/my-skill/my-skill.zip`.

- Whenever a skill is updated (any file within the skill folder is modified), re-zip that skill by deleting the old zip and creating a new one.

## README Updates

- Every time a new skill is added, add it to the skills table in `README.md`.
- The table format is:

| Skill | Description |
|-------|-------------|
| [skill-name](skills/skill-name/) | One sentence description of the skill |

- The skill name must be a clickable link to the skill's folder (e.g. `[grill-me](skills/grill-me/)`).
- Keep the table sorted alphabetically by skill name.
