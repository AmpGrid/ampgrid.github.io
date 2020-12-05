# ampgrid.github.io
GitHub Pages

This is a repo for creating AmpGrid docs hosted at ampgrid.github.io

This repo uses Sphinx to build static artifacts for web-based documentation.

## Installation

[Install Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) to build. Use `pip` to get v3.3+.

```sh
pip install -U sphinx
```

## Building

Use `Makefile` to build static artifacts and copy the output directly into `docs/`:

```sh
make github
```

## Deploying

GitHub pages is configured to serve with `docs/` as the root. Merge into branch `main`, and changes will soon be reflected at https://ampgrid.github.io.