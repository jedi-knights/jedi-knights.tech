---
title: "go.nvim — Go development inside Neovim"
description: "A complete plugin for writing, testing, and debugging Go programs from Neovim."
date: 2026-08-16
tags: ["neovim", "plugin", "go"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**go.nvim** is a plugin that makes Neovim a comfortable place to write Go. It handles the day-to-day chores of Go development — running tests, debugging, formatting, linting — so you don't have to jump out to a terminal for every task.

## Who it's for

Go developers who use Neovim as their main editor and want the same conveniences a full IDE offers, but without leaving the keyboard.

## What it does

- **Find and run tests** — supports Go's built-in tests plus the [Testify](https://github.com/stretchr/testify) and [Ginkgo](https://onsi.github.io/ginkgo/) test frameworks.
- **Debug your code** — steps through your program using [Delve](https://github.com/go-delve/delve), the standard Go debugger.
- **Format on save** — runs `gofmt` and `goimports` so your code is always tidy.
- **Lint as you type** — catches style and correctness issues using `golint`, `staticcheck`, or `revive`.
- **Browse the project** — searchable pop-ups for the Go modules, packages, tests, and imports in your project.
- **Run project tasks** — integrates with [Task](https://taskfile.dev) for build automation.
- **REPL and package explorer** — try snippets and inspect packages without leaving the editor.

## Status

Stable. Comes with full documentation and example configurations.

## What you'll need

- Neovim 0.8 or newer
- Go 1.16 or newer
- The [plenary.nvim](https://github.com/nvim-lua/plenary.nvim) utility library
- Optional: [snacks.nvim](https://github.com/folke/snacks.nvim) for the picker interface

## Where to get it

[github.com/jedi-knights/go.nvim](https://github.com/jedi-knights/go.nvim)
