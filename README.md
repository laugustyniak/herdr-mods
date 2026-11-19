# herdr-mods

Mods for the [Herdr desktop app](https://github.com/herdrdev/herdr-app).

Each mod lives in its own folder, laid out like `~/.config/herdr-app`:

```
<name>/
  mods/<name>/      mod.json, main.js, assets
  keys.json         keys the mod expects (optional)
  RECIPE.md         the brief to rebuild it from scratch
  preview.png       screenshot
```

## Install

Ask your agent to add `github.com/laugustyniak/herdr-mods/<name>`, or copy
`mods/<name>/` into `~/.config/herdr-app/mods/`, merge `keys.json` into yours
and run `herdr-app check <name>`.

## License

Apache-2.0. Mods derived from mods shipped with Herdr keep a header naming the
original (herdrdev/herdr-app, Apache-2.0).
