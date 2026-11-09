# greet-release

A small Python greeting program.

## Install and run

```sh
uv sync --locked
uv run --locked python greet.py Hee
uv run --locked python greet.py
uv run --locked pytest -q greet.py
uv build
```

Versioning follows Semantic Versioning (MAJOR.MINOR.PATCH).
