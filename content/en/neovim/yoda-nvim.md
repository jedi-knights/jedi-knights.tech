---
title: "yoda.nvim — a friendly Neovim distribution"
description: "A batteries-included Neovim setup for people who want a working editor on day one — with AI assistance built in."
date: 2026-08-16
tags: ["neovim", "distribution", "ai"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**yoda.nvim** is a *distribution* — a complete, pre-configured version of the Neovim editor. Instead of spending your first week (or month) picking plugins, tweaking settings, and copy-pasting configs from the internet, you install yoda.nvim and start writing code.

It comes with autocomplete, project search, testing, debugging, Git integration, a nice color scheme, and an AI coding assistant already wired up.

## Who it's for

- **New to Neovim** and want a working editor on day one.
- **Coming from VS Code or another modern IDE** and don't want to give up conveniences you're used to.
- **Experienced Neovim users** who want AI features without hand-rolling their own plugin stack.

## What you get out of the box

- **Editor essentials** — fuzzy file search, project-wide search, a file tree, syntax highlighting, and a comfortable dark theme (TokyoNight).
- **Language support** — autocomplete, jump-to-definition, and error highlighting for Lua, Go, TypeScript, JavaScript, and Rust.
- **AI coding help** — [Claude Code](https://www.anthropic.com/claude-code) integrated directly, with keybindings to open a chat, review diffs, and send selections to the AI.
- **Testing and debugging** — run tests and step through code without leaving the editor.
- **Git tools** — see diffs, stage hunks, blame lines, and browse history from inside Neovim.
- **Which-Key** — a pop-up that shows you what shortcuts are available as you type them. You never have to memorize everything up front.
- **Fast startup** — plugins load only when you need them, so opening the editor stays snappy.

## Learning it

yoda.nvim ships with its own help pages. Once installed, type `:help yoda` inside Neovim to browse them.

## Status

Actively maintained. The project is well-tested (191 automated tests, 100% coverage) and updated regularly.

## What you'll need

- Neovim version 0.10.1 or newer
- Git
- [ripgrep](https://github.com/BurntSushi/ripgrep) (for fast searching)
- Optional: a [Claude](https://claude.ai) account if you want the AI features

## Where to get it

[github.com/jedi-knights/yoda.nvim](https://github.com/jedi-knights/yoda.nvim)
