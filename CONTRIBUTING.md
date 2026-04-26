# Contributing to `uv-actions`

Thank you for considering contributing to `uv-actions`!
The following section describes how to set up and use a development environment.

## Development environment

`uv-actions` uses the following developer tools:

- [pre-commit](https://pre-commit.com) for managing pre-commit hooks
  (particularly for code formatting and linting)
- [uv](https://docs.astral.sh/uv/) for managing pre-commit versions

### Setup

Please follow these steps to set up your development environment:

1. Install `uv` if you have not already done so.
2. Clone the `uv-actions` repository and `cd` into it.
3. Install development dependencies by running `uv sync`.
4. Set up the hooks by executing `uv run pre-commit install`.
   The output should look something like this:

   ```plain
   pre-commit installed at .git/hooks/commit-msg
   pre-commit installed at .git/hooks/pre-commit
   ```

### Usage

Run pre-commit hooks:

```shell
uv run pre-commit run --all-files
```
