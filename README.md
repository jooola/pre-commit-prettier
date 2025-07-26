# Pre-commit hook for Prettier

A [prettier](https://github.com/prettier/prettier) hook for [pre-commit](https://github.com/pre-commit/pre-commit).

## Usage

Add the following snippet to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/jooola/pre-commit-prettier
  rev: 3.6.2 # Pick a tag from https://github.com/jooola/pre-commit-prettier/tags
  hooks:
    - id: prettier
```
