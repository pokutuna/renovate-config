renovate-config
===

For pokutuna personal use, put this json to `.github/renovate.json` in a repository.

### single

- Single branch for all dependency updates.

```json
{
  "extends": [
    "github>pokutuna/renovate-config:single"
  ]
}
```

### major-or-else

- Major updates create single PR.
- Other updates do aggressive automerge.

```json
{
  "extends": [
    "github>pokutuna/renovate-config:major-or-else"
  ]
}
```

## Links

- [Renovate Docs | Renovate Docs](https://docs.renovatebot.com/)
- [hatena/renovate-config: A shareable config preset for Renovate used in Hatena.](https://github.com/hatena/renovate-config)
