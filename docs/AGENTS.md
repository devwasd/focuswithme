# Agent Rules

## Must

- Read docs/PRD.md and docs/ARCHITECTURE.md before coding.
- Keep widgets under 150 lines when practical.
- Separate UI, state, and services.
- Run `flutter analyze` after changes.
- Run relevant tests when tests exist.

## Must Not

- Do not rewrite the entire project without permission.
- Do not introduce new packages without explaining why.
- Do not mix audio logic directly into widgets.
- Do not use setState for feature state unless trivial local animation state.
