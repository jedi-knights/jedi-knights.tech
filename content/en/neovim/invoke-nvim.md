---
title: "invoke.nvim — run Python Invoke tasks from Neovim"
description: "A searchable menu inside Neovim for running Invoke tasks from any Python project."
date: 2026-08-16
tags: ["neovim", "plugin", "python", "task-runner"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**invoke.nvim** connects Neovim to [Invoke](https://www.pyinvoke.org/), a popular Python task runner. Invoke lets you define common project chores — running tests, formatting code, starting a server — as functions inside a `tasks.py` file.

This plugin makes those tasks browsable and runnable from inside Neovim, so you don't have to remember every task name or drop into a terminal.

## Who it's for

Python developers who already use Invoke for project scripts and want a friendlier way to run them.

## What it does

- **Discover tasks** — reads your `tasks.py` and shows every task with its description and aliases.
- **Fuzzy search** with a live preview panel.
- **Run in a floating terminal** so output stays out of the way.
- **Remembers history and favorites** so your most-used tasks are one keystroke away.
- **Ask for arguments** when a task needs input, with saved presets.
- **Get notified** when a long-running task finishes.
- **Plays nicely** with other popular plugins ([overseer.nvim](https://github.com/stevearc/overseer.nvim), [trouble.nvim](https://github.com/folke/trouble.nvim), [which-key.nvim](https://github.com/folke/which-key.nvim)).

## Status

Feature-complete. All roadmap items are implemented.

## What you'll need

- A Python project with Invoke installed and a `tasks.py` file
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim), [snacks.nvim](https://github.com/folke/snacks.nvim), and [toggleterm.nvim](https://github.com/akinsho/toggleterm.nvim)

## Where to get it

[github.com/jedi-knights/invoke.nvim](https://github.com/jedi-knights/invoke.nvim)
