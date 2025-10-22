# pre-commit-typstyle

typstyle for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For typstyle: see https://github.com/typstyle-rs/typstyle

## Using typstyle with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
  - repo: https://github.com/typstyle-rs/pre-commit-typstyle
    rev: "" # The the revision or tag you want to use
    hooks:
      - id: typstyle
```
