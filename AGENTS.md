# Repository Guidelines

## Project Structure & Module Organization
This repository is a collection of standalone skill artifacts stored at the root. Expect mostly `*.skill` files plus a few packaged assets like `*.zip`. There is no nested source tree or test directory in the current layout. When adding new skills, place them at the root and use clear, descriptive filenames (e.g., `New Feature Skill.skill`).

## Build, Test, and Development Commands
There are no build or test scripts in this repository. If you add automation later, document it here with concise examples (e.g., `make validate` or `npm test`).

## Coding Style & Naming Conventions
- Use ASCII text in skill files unless non-ASCII is required for the content.
- Keep filenames descriptive and consistent, using title case and the `.skill` suffix.
- If adding archives, prefer `.zip` and mirror the skill name (e.g., `Example Skill.zip`).

## Testing Guidelines
No automated tests are present. If you introduce tests, include the framework, coverage expectations, and how to run them.

## Commit & Pull Request Guidelines
This repository is not a Git repository, so there is no commit history to infer conventions from. If you initialize Git, adopt clear, imperative commit messages (e.g., `Add data-cleaning skill`) and include a short PR description with purpose, scope, and any supporting files or screenshots.

## Security & Configuration Tips
Avoid embedding secrets or private data in `.skill` files. If a skill requires credentials or API keys, document environment variable placeholders instead of real values.
