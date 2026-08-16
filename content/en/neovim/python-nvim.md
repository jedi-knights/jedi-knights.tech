---
title: "python.nvim — Python development inside Neovim"
description: "An all-in-one plugin for Python: testing, debugging, formatting, linting, virtual environments, and task running."
date: 2026-08-16
tags: ["neovim", "plugin", "python"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**python.nvim** is a one-stop plugin for Python development in Neovim. Instead of stitching together five different plugins for testing, debugging, formatting, and environment management, you install this one and everything works together.

## Who it's for

Python developers using Neovim who want their editor to handle the full Python workflow — from picking the right virtual environment to running tests to stepping through code with a debugger.

## What it does

- **Virtual environments** — detects them automatically and lets you switch between them.
- **Package management** — install and uninstall packages from inside the editor.
- **Formatting** — runs `black` and `isort` to keep your code tidy.
- **Linting** — highlights issues found by `flake8` and `mypy`.
- **Testing** — discovers and runs tests with Pytest or the built-in `unittest`, and remembers your history.
- **Debugging** — steps through code using `debugpy`, the standard Python debugger.
- **REPL and Jupyter notebooks** — try snippets or work through notebooks without leaving Neovim.
- **Task runners** — supports [Invoke](https://www.pyinvoke.org/), `make`, and custom scripts.
- **Refactoring and code intelligence** — rename symbols and navigate the codebase.

## Status

Stable, with a large feature set and many configuration options.

## What you'll need

- Neovim 0.8 or newer
- Python 3.7 or newer
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim)
- Optional: [snacks.nvim](https://github.com/folke/snacks.nvim) for the searchable menus

## Where to get it

[github.com/jedi-knights/python.nvim](https://github.com/jedi-knights/python.nvim)
