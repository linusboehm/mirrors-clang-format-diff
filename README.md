clang-format-diff mirror
===================

Mirror of `clang-format` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For clang-format: see https://github.com/ssciwr/clang-format-wheel

Similar to https://github.com/pre-commit/mirrors-clang-format, but formats only the modified
portions of the code, rather than the entire changed files.

### Using clang-format-diff with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/linusboehm/mirrors-clang-format-diff
  rev: ''  # Use the sha / tag you want to point at
  hooks:
  - id: clang-format-diff
```
