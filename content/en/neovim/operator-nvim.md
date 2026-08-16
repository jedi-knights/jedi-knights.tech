---
title: "operator.nvim — invent your own Vim commands, without the boilerplate"
description: "A small library for plugin authors who want to define custom keyboard commands that behave like Vim's built-ins."
date: 2026-08-16
tags: ["neovim", "plugin", "library"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**operator.nvim** is a helper library for people who write Neovim plugins.

Vim has a concept called an **operator** — a command like "delete" or "change" that combines with a **motion** like "the next word" or "the whole paragraph." Together they make commands like `daw` (delete a word) or `cip` (change inside a paragraph).

Building your own operator normally requires a working knowledge of Vim's internal API (`operatorfunc`, `g@`, and `<Plug>` mappings). This library hides that complexity behind a one-line function call. You get automatic support for motions, visual selection, and the dot-repeat shortcut for free.

## Who it's for

Plugin authors and advanced Neovim users who want to define their own operators — things like "uppercase this," "wrap this in quotes," or "send this to a REPL" — without memorizing Vim internals.

## What it does

- **One simple call** — `operator.define(name, opts)` and you're done.
- **Handles every motion type** — character-wise, line-wise, and block-wise selections.
- **Works in visual mode too.**
- **Dot-repeat** works out of the box (if the popular [vim-repeat](https://github.com/tpope/vim-repeat) plugin is installed).
- **Claims no keys of its own** — you decide how users trigger the operator.

## Status

Pre-release (experimental). The public interface will stabilize with the version 0.1.0 tag.

## What you'll need

- Neovim 0.10 or newer
- Optional: [vim-repeat](https://github.com/tpope/vim-repeat) for dot-repeat support

## Where to get it

[github.com/jedi-knights/operator.nvim](https://github.com/jedi-knights/operator.nvim)
