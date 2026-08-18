---
title: "Neovim"
description: "A plain-English tour of the Neovim distribution, plugins, and tools I've built."
date: 2026-08-16
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
menu: main
---

## What this section is about

This part of the site is a plain-language tour of the work I've done for **Neovim** — a keyboard-driven code editor that runs in your terminal. Everything here is free, open source, and lives on [GitHub](https://github.com/jedi-knights).

If you've never used Neovim, the vocabulary below will help. If you have, skip past it — the good stuff is further down.

## A quick vocabulary for newcomers

- **Neovim** — a text editor that runs in a terminal window. It descends from Vim, which descends from Vi. It's fast, it works over SSH, and it's controlled almost entirely from the keyboard.
- **Plugin** — a small add-on that gives Neovim a new capability. Think "browser extension," but for a code editor.
- **Distribution** — a bundle that combines Neovim with a curated set of plugins, sensible defaults, and a pre-wired configuration. If a plugin is a Chrome extension, a distribution is a whole browser like Brave — same engine, opinionated defaults.
- **LSP (Language Server Protocol)** — the technology that powers autocomplete, jump-to-definition, error underlines, and rename-across-a-project. Editors talk to a "language server" for each programming language.
- **Picker** — an interactive pop-up list you can fuzzy-search. If you've used the Command Palette in VS Code (Ctrl+Shift+P), it's the same idea.
- **Keymap** — a shortcut. `<leader>ff` means "press your leader key, then f, then f."

## What's in this section

### The distribution

- [**yoda.nvim**](yoda-nvim/) — my full Neovim distribution. Batteries-included, beginner-friendly, and set up so you can start writing code the day you install it.

### General-purpose tools

- [**keymap-forensics.nvim**](keymap-forensics-nvim/) — a debugger for keyboard shortcuts. Tells you which plugin bound a key and which shortcut is hiding another one.
- [**operator.nvim**](operator-nvim/) — a small library for plugin authors who want to invent their own keyboard commands without wrestling with Vim's internals.
- [**vimhelp.nvim**](vimhelp-nvim/) — a full-text search engine over Neovim's built-in help pages. Search for a concept, not just an exact tag.

### Python-focused tools

- [**python.nvim**](python-nvim/) — a one-stop plugin for Python development in Neovim: testing, debugging, formatting, virtual environments, and task runners.
- [**pytest.nvim**](pytest-nvim/) — a focused plugin for running the pytest test framework from inside the editor.
- [**invoke.nvim**](invoke-nvim/) — runs [Invoke](https://www.pyinvoke.org/) tasks (a Python task runner) from a searchable menu in Neovim.

### Go-focused tools

- [**go.nvim**](go-nvim/) — a full plugin for Go development in Neovim: tests, debugging, formatting, linters, and module management.
- [**go-task.nvim**](go-task-nvim/) — runs [Task](https://taskfile.dev) commands (a modern Make replacement) from a searchable menu in Neovim.

## Where this is going

This section will grow as I publish more plugins, distributions, and command-line tools around Neovim. Expect additions covering:

- More language-specific plugins (Rust, TypeScript, Lua tooling).
- Command-line utilities that pair with Neovim but run outside it.
- Guides for using the tools together.

If you'd like to follow along or contribute, everything lives under [github.com/jedi-knights](https://github.com/jedi-knights).
