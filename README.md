# free_zed

Zed editor configuration + dark theme set.

## Layout

| Path | Purpose |
|------|---------|
| `themes/` | Dark themes: Zen Black, Mono Noir, Zen Fixed, Ayu, 1984, Obsidian Noir |
| `settings.json` | Zed settings (dark theme: Zen Black) |
| `keymap.json` | Key bindings |
| `prompts/` | Prompt collections |
| `snippets/` | User snippets |

## Use

Clone this repo into your Zed config directory so Zed picks up
the settings, themes, keymap, snippets and prompts:

```bash
git clone <repo-url> ~/.config/zed
```

For a clean install (no merge with the existing `~/.config/zed`),
back up the current directory first and then copy the files over.

> `settings.json` contains your local model / agent paths — edit it
> before sharing, or keep this repo private if you don't want to.
