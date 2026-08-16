---
title: "go-task.nvim — run Taskfile tasks from Neovim"
description: "A focused plugin for running Task (a modern Make replacement) from a searchable menu inside Neovim."
date: 2026-08-16
tags: ["neovim", "plugin", "go", "task-runner"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**go-task.nvim** connects Neovim to [Task](https://taskfile.dev) — a build tool that lets you define shortcuts like "run the tests," "build the binary," or "start the server" in a plain YAML file called `Taskfile.yml`.

Instead of typing `task test` in a separate terminal, you open a searchable menu inside Neovim, pick the task, and see the output in a floating window.

## Who it's for

Anyone (Go developers especially) who uses `Taskfile.yml` for project automation and wants to run those tasks without leaving the editor.

## What it does

- **List every task** in your project with its description.
- **Search by name** — start typing and the list filters instantly.
- **Run in a floating window** so the output doesn't take over your workspace.
- **Auto-loads** when you open a project that has a `Taskfile.yml`.
- **Debug toggle** for troubleshooting task discovery.

## Status

Stable and complete. All planned features are done.

## What you'll need

- Neovim 0.8 or newer
- The [task](https://taskfile.dev/installation/) command-line tool
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim) and [snacks.nvim](https://github.com/folke/snacks.nvim)

## Where to get it

[github.com/jedi-knights/go-task.nvim](https://github.com/jedi-knights/go-task.nvim)
