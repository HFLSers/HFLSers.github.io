# HFLSers Site

This site is now built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Setup

1.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    # or if using pip directly from pyproject.toml dependencies (if configured)
    pip install .
    # or manually
    pip install mkdocs mkdocs-material mkdocs-git-authors-plugin mkdocs-git-revision-date-localized-plugin
    ```

## Development

Run the dev server:

```bash
mkdocs serve
```

## Build

Build the static site:

```bash
mkdocs build
```

## Configuration

The site is configured in `mkdocs.yml`.
