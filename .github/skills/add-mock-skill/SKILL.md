---
name: add-mock-skill
description: Creates and documents a mock skill following the project's official skill standard.
---

This skill guides the creation of a consistent mock skill to validate structure, writing quality, and repository registration.

---

## Rules

- MUST create the skill folder at `.github/skills/add-mock-skill/`
- MUST keep the frontmatter `name` equal to the folder name
- MUST include Rules, File Structure, Examples, and Validation Checklist sections
- MUST use objective language and actionable instructions
- MUST register the skill in both the table and the `<skills>` block in `.github/copilot-instructions.md`
- MUST NOT create generic content without validation criteria
- MUST NOT duplicate an existing skill with the same purpose

---

## File Structure

```text
.github/skills/add-mock-skill/
└── SKILL.md
```

---

## Examples

### Good Example (👍)

```markdown
---
name: add-mock-skill
description: Creates and documents a mock skill following the official standard.
---

## Rules

- MUST have valid frontmatter
- MUST include a validation checklist
```

Why this is correct:

- It includes complete frontmatter
- The name follows kebab-case and matches the folder name
- It defines mandatory rules clearly

### Bad Example (❌)

```markdown
# Random skill

Do it your own way.
```

Why this is wrong:

- It does not include the required frontmatter
- It does not define rules in MUST/MUST NOT format
- It does not include both good and bad examples
- It does not include a validation checklist

---

## Validation Checklist

- [ ] Folder created at `.github/skills/add-mock-skill/`
- [ ] `SKILL.md` file exists and uses uppercase naming
- [ ] Frontmatter contains `name` and `description`
- [ ] `name` is in kebab-case and matches the folder name
- [ ] `Rules` section uses MUST/MUST NOT
- [ ] `Examples` section contains both 👍 and ❌ cases
- [ ] The ❌ case explains “Why this is wrong”
- [ ] Skill is registered in the skills table in `.github/copilot-instructions.md`
- [ ] Skill is registered in the `<skills>` block in alphabetical order

---

## Related Skills

- No related skills are currently registered in this template.
