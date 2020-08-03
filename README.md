renovate-config
===

For pokutuna perlsonal use, put below json on `.github/renovate.json`.

- Group PRs by update types.
- Aggressive automerge.
  - |       | app | lib |
    | ---   | --- | --- |
    | major |  -  |  -  |
    | minor |  ✔ | - (dependencies) <br> ✔ (devDependencies)|
    | patch |  ✔ | ✔ |


### app

For applications.

```json
{
  "extends": [
    "github>pokutuna/renovate-config:app"
  ]
}
```

### lib

For libraries.

```json
{
  "extends": [
    "github>pokutuna/renovate-config:lib"
  ]
}
```


## Links

- [Renovate Docs | Renovate Docs](https://docs.renovatebot.com/)
- [hatena/renovate-config: A shareable config preset for Renovate used in Hatena.](https://github.com/hatena/renovate-config)
