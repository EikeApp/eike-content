# Eike - Inhalte

## Legal information

[LICENSE](LICENSE.md)

[CONTRIBUTOR-AGREEMENT](docs/CONTRIBUTOR-AGREEMENT.md)

## Releases

Es werden automatisiert Releases erstellt, wenn der main-Branch aktualisiert wird.

Damit [breaking changes als SemVer](https://semver.org/) korrekt erkannt werden, sollten
[conventional commits](https://www.conventionalcommits.org) verwendet werden.

### Conventional Commits

Eine Version, z.B. `1.2.3`, wobei
- 1 die Major-Version (Breaking)
- 2 die Minor-Version (Feature)
- 3 die Patch-Version (Fix)
ist, wird wie folgt ausgelöst:

#### Breaking

Die Commit-Nachricht wird wie folgt angegeben

```txt
feat: <flyer umbenannt zu Broschüre>

BREAKING CHANGE: <klarstellung des Parameters>
```

#### Feature

```txt
feat: <hintergrundfarbe hinzugefügt>
```

#### Fix

```txt
fix: <Alternativtext geändert>
```

```txt
docs: <Readme erweiter>
```
