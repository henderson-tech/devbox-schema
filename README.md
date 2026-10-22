# devbox-schema

The JSON Schemas of `devbox.yaml`, the recipe a project keeps at its repo root
for Devbox. Generated from the recipe types Devbox (`henderson-tech/devbox`)
decodes and published by its deploy: never edit the schemas here.

Point an editor at one with a first line in `devbox.yaml`. A v1 recipe (no
top-level `version`):

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/henderson-tech/devbox-schema/main/v1/devbox.schema.json
```

A recipe v2 file (`version: 2`):

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/henderson-tech/devbox-schema/main/v2/devbox.schema.json
```

`v1` changes version only when a recipe valid under v1 stops being valid.
`v2/` is the separate recipe-v2 dialect's schema (`version: 2`).
