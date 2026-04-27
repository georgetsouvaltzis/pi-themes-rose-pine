# pi-themes-rose-pine

Rosé Pine theme pack for [pi](https://github.com/badlogic/pi-mono), including all 3 official variants:

- `rose-pine`
- `rose-pine-moon`
- `rose-pine-dawn`

## Install

```bash
pi install npm:pi-themes-rose-pine
```

Or local development:

```bash
pi install ./pi-themes-rose-pine
```

## Select a theme

In pi, open `/settings` and set theme to one of:

- `rose-pine`
- `rose-pine-moon`
- `rose-pine-dawn`

Or in `settings.json`:

```json
{
  "theme": "rose-pine"
}
```

## Package structure

```text
themes/
  rose-pine.json
  rose-pine-moon.json
  rose-pine-dawn.json
```

This package exposes themes via:

```json
{
  "pi": {
    "themes": ["./themes"]
  }
}
```

## Publish

```bash
npm login
npm publish
```

If using a scoped package:

```bash
npm publish --access public
```
