# Contributing

## Commit message convention

This repository follows [Conventional Commits](https://www.conventionalcommits.org/).

Format:

```text
<type>(<scope>): <short imperative summary>
```

### Allowed types

- `feat` - new feature
- `fix` - bug fix
- `docs` - documentation only
- `style` - formatting/style only
- `refactor` - code change without feature/fix
- `perf` - performance improvements
- `test` - tests added/updated
- `build` - build/package/dependency changes
- `ci` - CI/CD changes
- `chore` - maintenance tasks
- `revert` - revert a previous commit

### Suggested scopes for this project

- `themes`
- `rose-pine`
- `rose-pine-moon`
- `rose-pine-dawn`
- `package`
- `readme`
- `release`

### Rules

- Use lowercase imperative summary (e.g. `add`, `update`, `remove`)
- No trailing period
- Keep summary concise (prefer <= 72 chars)
- Add body when context is useful
- Add footers when relevant, e.g.:

```text
BREAKING CHANGE: ...
Refs: #123
```

### Examples

```text
feat(themes): add initial rose-pine, moon, and dawn variants
fix(rose-pine-dawn): improve contrast for muted text
docs(readme): add install and theme selection instructions
chore(release): bump version to 0.1.1
```
