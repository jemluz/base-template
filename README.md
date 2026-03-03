# base-template

This template is focused mainly on documentation and project patterns, could be reused before define a stack.

## First of all! Check `config-files/` folder

The `config-files` folder only will work if you move them to root folder. They are grouped into a folder just to facilitate your initial orientation on this template (to avoid the risk of mixing files with same name when running a CLI command for example)

The template-files folder must die when you finished your environment preparation.

# Project Name!!

### Brasilian Slogan 🇧🇷

English slogan [EN]

turma.dev is a portfolio storytelling platform where developers can present their professional journey through a timeline of milestones, projects, and personal links in a content-centered experience.

### 🌐 Online preview [your project link](https://google,com)

### 🖼️ Spoilers

Attach some prints of your app

| 🖥️ Desktop                                                                                                                      | 📱 Mobile                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| <img src="docs/imgs/print%20desktop.png" alt="turma.dev desktop preview" height="420" style="width:auto;object-fit:contain;" /> | <img src="docs/imgs/print%20mobile.png" alt="turma.dev mobile preview" height="420" style="width:auto;object-fit:contain;" /> |

## ✨ Key Features

- [List of key features here]

## 📚 Tech Stack

| Layer          | Technology                                                                                   |
| -------------- | -------------------------------------------------------------------------------------------- |
| Framework      | [Framework Name + Version](https://example.com/framework)                                    |
| UI Library     | [UI Library Name + Version](https://example.com/ui-library)                                  |
| Language       | [Primary Language + Version](https://example.com/language)                                   |
| Styling        | [Styling Solution](https://example.com/styling)                                              |
| Component Kit  | [Component Kit / Design System](https://example.com/components)                              |
| Icons          | [Icon Library 1](https://example.com/icons-1), [Icon Library 2](https://example.com/icons-2) |
| Linting/Format | [Linter](https://example.com/linter), [Formatter](https://example.com/formatter)             |

## 🚀 Start Here

1. Local setup: [docs/project-setup.md](docs/project-setup.md)
2. Product vision: [docs/vision.md](docs/vision.md)
3. Architecture: [docs/architecture.md](docs/architecture.md)
4. Folder structure: [docs/folder-structure.md](docs/folder-structure.md)
5. Development workflow: [docs/dev-workflow.md](docs/dev-workflow.md)

## 🗺️ Documentation Quick Map

### 🎯 Product and Direction

- Vision and purpose: [docs/vision.md](docs/vision.md)
- Evolution and scope boundaries: [docs/future.md](docs/future.md)

### 🏗️ Engineering and Architecture

- Architecture and invariants: [docs/architecture.md](docs/architecture.md)
- Current data model (ERD): [docs/data-model.md](docs/data-model.md)
- Code organization: [docs/folder-structure.md](docs/folder-structure.md)
- State management: [docs/state-management.md](docs/state-management.md)
- UI/UX guidelines: [docs/ui-guidelines.md](docs/ui-guidelines.md)

### 🔁 Development Process

- Workflow for issues, sub-issues, and PRs: [docs/dev-workflow.md](docs/dev-workflow.md)
- Project setup and scripts: [docs/project-setup.md](docs/project-setup.md)

## ⚙️ Operational Rules in `.github/`

The `.github` folder stores GitHub-specific configuration and workflow files that help standardize repository collaboration and automation. Common contents include:

- Source of truth for project standards and AI instructions: [.github/copilot-instructions.md](.github/copilot-instructions.md)
- Topic-specific rules: [.github/instructions/](.github/instructions/)
- Reusable skills for recurring tasks: [.github/skills/](.github/skills/)
- `ISSUE_TEMPLATE/` and `pull_request_template.md` to guide contributors when opening issues or PRs.
