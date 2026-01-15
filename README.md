# [@scop](https://github.com/scop) common things

## GitHub action: Force color

GitHub action to force color output from tools,
works by setting environment variables.

Usage in a GitHub workflow job config, affects steps that come after it:

```yaml
jobs:
  my-job:
    runs-on: ubuntu-latest
    steps:
      - uses: scop/common/force-color@main
```

## Renovate preset

Opinionated
[configuration preset](https://docs.renovatebot.com/key-concepts/presets/)
for [Renovate](https://docs.renovatebot.com).

Usage in
[Renovate repository configuration](https://docs.renovatebot.com/configuration-options/):

```json5
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>scop/common"
  ],
```
