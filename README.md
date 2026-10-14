# devbox-schema

The JSON Schema of `devbox.yaml`, the recipe a project keeps at its repo root
for Devbox. Generated from the recipe types Devbox decodes and published by
its deploy: never edit it here.

Point an editor at it with a first line in `devbox.yaml`:

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/henderson-tech/devbox-schema/main/v1/devbox.schema.json
```

`v1` moves to `v2` only when a recipe valid under v1 stops being valid.
