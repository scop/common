# force-color GitHub action

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

See the
[coverage wiki page](https://github.com/scop/common/wiki/force%E2%80%90color-coverage)
for some tool coverage info.
