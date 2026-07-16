# CLAUDE.md

Project context and conventions for AI-assisted development in this repository.

## Stack

- **HTML** — Semantic, accessible markup
- **CSS** — Responsive layouts, modern styling
- **JavaScript** — Vanilla JS; no framework unless explicitly required

## Editor

Development is done in **Cursor**. Use the AI assistant for scaffolding, refactoring, and review — but always verify output before committing.

## Git Workflow

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<optional scope>): <short description>

[optional body]
```

### Commit types

| Type       | Purpose                                      |
| ---------- | -------------------------------------------- |
| `feat`     | New feature                                  |
| `fix`      | Bug fix                                      |
| `docs`     | Documentation changes                        |
| `style`    | Formatting only (no logic change)            |
| `refactor` | Code restructure without behavior change     |
| `test`     | Adding or updating tests                     |
| `chore`    | Tooling, dependencies, or maintenance        |

### Examples

```
feat: add hero section with call-to-action button
fix: correct mobile menu toggle on small screens
docs: update README with project structure
chore: add Node.js gitignore
```

### Branching

- `main` — stable, deployable code
- Feature branches — `feat/<name>`, `fix/<name>`, etc.
- Keep commits small and focused; one logical change per commit.

## Code Standards

### Clean code

- Use clear, descriptive names for variables, functions, and files.
- Keep functions small and single-purpose.
- Avoid duplication — extract shared logic when it appears more than twice.
- Prefer readability over cleverness.

### Responsive design

- Design mobile-first; enhance for larger breakpoints.
- Use relative units (`rem`, `em`, `%`, `vw`/`vh`) where appropriate.
- Test layouts at common breakpoints: 320px, 768px, 1024px, 1440px.
- Images and media must scale without breaking layout.

### HTML

- Use semantic elements (`header`, `nav`, `main`, `section`, `article`, `footer`).
- Include `alt` text on images and labels on form inputs.
- Maintain a logical heading hierarchy (`h1` → `h2` → `h3`).

### CSS

- Organize styles by component or section, not by property type.
- Use CSS custom properties for repeated values (colors, spacing, fonts).
- Avoid `!important` unless absolutely necessary.

### JavaScript

- Use `const` and `let`; avoid `var`.
- Prefer event delegation for dynamic content.
- Handle errors gracefully; do not leave silent failures.

## Comments

Add comments **only where necessary**:

- Complex business logic that is not self-evident
- Workarounds with a reason (include a brief explanation)
- Public API or module boundaries

Do **not** comment obvious code. Good naming is preferred over explanatory comments.

## Meaningful Commit Messages

- Use the imperative mood: "add feature" not "added feature".
- Keep the subject line under 72 characters.
- Describe **what** changed and **why** in the body when helpful.
- Reference issues or tasks when applicable.

## File Organization

```
index.html
css/
  styles.css
js/
  main.js
assets/
  images/
```

Keep assets, styles, and scripts in their respective folders as the project grows.

## AI Assistant Guidelines

When asking Cursor or Claude for help:

1. Provide context about the feature or bug.
2. Request changes that match existing conventions in this file.
3. Review generated code for accessibility, responsiveness, and simplicity.
4. Do not accept large refactors unless they solve a clear problem.
