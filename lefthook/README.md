# Lefthook remote configurations

Opinionated
[remote configurations](https://lefthook.dev/configuration/remotes.html)
for [Lefthook](https://lefthook.dev).

Usage in a repo's `.config/lefthook.yaml`:

```yaml
remotes:
  - git_url: https://github.com/scop/common.git
    refetch_frequency: 24h
	configs:
	  - lefthook/all.yaml
```
