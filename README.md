# uv-actions

Composite actions for [`uv`](https://docs.astral.sh/uv/)-based projects.

## Actions

- [`set-up-pre-commit`](set-up-pre-commit/action.yml):
  Caches and sets up `pre-commit` environments (requires `set-up-uv`).
- [`set-up-uv`](set-up-uv/action.yml):
  Installs `uv` and Python.
  Optionally installs and caches dependencies.
- [`set-up-uv-and-pre-commit-for-copilot`](set-up-uv-and-pre-commit-for-copilot/action.yml):
  Combines `set-up-uv` and `set-up-pre-commit` with the exact configuration
  required by `copilot-setup-steps.yml` workflows.
