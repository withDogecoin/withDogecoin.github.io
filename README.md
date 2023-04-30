# Docs Guide

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Configurations

__Install:__
- brew install mkdocs
- brew install pipx
- pip3 -v
- python3.11 -m pip install --upgrade pip

__[Configuration](https://www.mkdocs.org/user-guide/configuration/):__
- `mkdocs new .` in GitHub Pages Repository

__Start:__
- mkdocs build
- mkdocs serve
- http://127.0.0.1:8080/

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Plugins

- https://www.mkdocs.org/dev-guide/plugins/
- https://github.com/mkdocs/mkdocs/wiki/MkDocs-Plugins

## Themes

- https://github.com/squidfunk/mkdocs-material
- https://squidfunk.github.io/mkdocs-material/getting-started/