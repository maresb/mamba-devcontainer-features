
# micromamba (micromamba)

Installs micromamba, the fast cross-platform package manager.

## Example Usage

```json
"features": {
    "ghcr.io/maresb/mamba-devcontainer-features/micromamba:0": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Exact version of Micromamba to install (must be X.Y.Z) | string | latest |
| reinstall | Reinstall in case Micromamba already exists | boolean | false |
| addCondaForge | Add conda-forge channel to the config? | boolean | false |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/maresb/mamba-devcontainer-features/blob/main/src/micromamba/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
