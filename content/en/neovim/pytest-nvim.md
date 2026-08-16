---
title: "pytest.nvim — run Python tests from Neovim"
description: "A focused plugin for running Pytest from inside the editor, with results in Neovim's quickfix list."
date: 2026-08-16
tags: ["neovim", "plugin", "python", "testing"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**pytest.nvim** runs the [Pytest](https://docs.pytest.org/) test framework from inside Neovim. Results appear in the built-in **quickfix window** — a list you can jump through with a keystroke — so you can go straight from a failure message to the failing line of code.

## Who it's for

Python developers who use Pytest and want to run tests, review failures, and jump around results without leaving Neovim.

## What it does

- **Run the current file's tests** with one command.
- **Run the whole project's tests** with another.
- **See failures in the quickfix window** and jump to each one by pressing a key.
- **Searchable pickers** for choosing your test environment, filtering by Pytest markers, or picking a config file.
- **Customizable** — pass any extra Pytest arguments or environment variables.
- **Loads only when you open a Python file** so it doesn't slow down other work.

## Status

Core features are stable. Planned upgrades include inline error messages next to failing lines, floating summary panels, and richer output parsing.

## What you'll need

- Neovim
- Python 3.7 or newer
- Pytest installed
- [snacks.nvim](https://github.com/folke/snacks.nvim) for the pickers

## Where to get it

[github.com/jedi-knights/pytest.nvim](https://github.com/jedi-knights/pytest.nvim)
