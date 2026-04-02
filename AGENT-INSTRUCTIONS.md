# Agent Instructions

## Skill Zipping

- Every time a new skill is added to the `skills/` directory, create a `.zip` file of that skill inside the skill's folder. For example, if a skill called `my-skill` is added, run `cd skills/my-skill && zip -r my-skill.zip . -x "*.zip"` to create `skills/my-skill/my-skill.zip`.

- Whenever a skill is updated (any file within the skill folder is modified), re-zip that skill by deleting the old zip and creating a new one.
