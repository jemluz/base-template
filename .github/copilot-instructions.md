# GitHub Copilot Instructions - [PROJECT_NAME]

## Project Context

- [Short description of the project purpose]
- [Primary audience or users]
- [Current maturity stage: template / MVP / production]

## 🏗️ Tech Stack

- **Status**: [Defined | Not defined]
- **Frontend**: [Framework/library or N/A]
- **Backend**: [Framework/runtime or N/A]
- **Language(s)**: [Primary language(s)]
- **Styling/UI**: [Approach or N/A]
- **Data layer**: [Database/ORM or N/A]
- **Rule**: Document decisions before introducing new dependencies.

## 📁 Project Structure

### Main Folders

- `docs/` - [Vision, architecture, process, and guidelines]
- `.github/` - [Collaboration standards, templates, and AI instructions]
- `src/` - [Application source code, if applicable]
- `config-files/` - [Reference setup/configuration files]
- `README.md` - [Project overview and entry point]

### Files Naming Convention

| Type           | Convention | Examples                              |
| -------------- | ---------- | ------------------------------------- |
| Document files | kebab-case | `ui-guidelines.md`, `dev-workflow.md` |

## 💻 Code Standards

**Types/Functions/Constants Naming Convention**

| Type                | Convention                                            | Examples                                         |
| ------------------- | ----------------------------------------------------- | ------------------------------------------------ |
| Functions/variables | camelCase                                             | `getProjectContext`, `handleSubmit`, `isEnabled` |
| Constants           | SCREAMING_SNAKE_CASE                                  | `DEFAULT_LOCALE`, `MAX_SECTION_COUNT`            |
| Types/Interfaces    | PascalCase                                            | `ProjectVision`, `ArchitectureLayer`             |
| Enums               | PascalCase (name), SCREAMING_SNAKE_CASE (keys/values) | `enum DecisionState { DRAFT = "DRAFT" }`         |

## 🥸 Important Decisions

- [Decision 1: Core architecture approach]
- [Decision 2: Documentation requirements]
- [Decision 3: Dependency management rule]
- [Decision 4: Source of truth in case of conflict]

## 🧭 Instructions Map (Single Source of Truth)

Use this map to find authoritative rules. Avoid duplicating detailed rules in this file.

| Topic                   | Source                  | When to consult                                          |
| ----------------------- | ----------------------- | -------------------------------------------------------- |
| Project overview        | `README.md`             | When understanding purpose, scope, and direction         |
| Vision and principles   | `docs/vision.md`        | Before proposing changes to project direction            |
| Conceptual architecture | `docs/architecture.md`  | When structuring layers and responsibilities             |
| Workflow guidelines     | `docs/dev-workflow.md`  | Before defining contribution and collaboration flow      |
| Experience guidelines   | `docs/ui-guidelines.md` | When defining UX/UI behavior at a conceptual level       |
| Future directions       | `docs/future.md`        | When evaluating ideas that should not be implemented yet |

Maintenance rule:

- If a rule changes, update the corresponding canonical document.
- Keep this map concise and avoid duplicating detailed content.

## 💪 Skills

Skills are modular, context-specific knowledge modules that guide AI assistants on how to perform common tasks following project conventions.

Available skills:

| Skill          | Description                                 | Path                                     |
| -------------- | ------------------------------------------- | ---------------------------------------- |
| [skill-name-1] | [Short description of what this skill does] | `.github/skills/[skill-name-1]/SKILL.md` |
| [skill-name-2] | [Short description of what this skill does] | `.github/skills/[skill-name-2]/SKILL.md` |

<!-- The XML structure below is automatically processed for tool integration. Keep it in sync with the table above. -->

<skills>
  <skill>
    <name>[skill-name-1]</name>
    <description>[Short description of what this skill does.]</description>
    <file>/workspaces/base-template/.github/skills/[skill-name-1]/SKILL.md</file>
  </skill>
  <skill>
    <name>[skill-name-2]</name>
    <description>[Short description of what this skill does.]</description>
    <file>/workspaces/base-template/.github/skills/[skill-name-2]/SKILL.md</file>
  </skill>
</skills>
