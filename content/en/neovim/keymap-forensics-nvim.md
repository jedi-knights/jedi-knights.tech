---
title: "keymap-forensics.nvim — figure out who bound that shortcut"
description: "A small detective tool that tells you which plugin claimed a keyboard shortcut and which shortcuts are hiding others."
date: 2026-08-16
tags: ["neovim", "plugin", "diagnostics"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**keymap-forensics.nvim** is a debugging tool for keyboard shortcuts.

If you use many Neovim plugins, they will eventually fight over the same shortcuts. One plugin wins, one loses, and you have no easy way to see what happened. This plugin gives you three commands that answer three questions:

- Who bound this key?
- Where are my shortcuts colliding?
- What's the full history of everyone who tried to bind this key?

## Who it's for

Neovim users with a lot of plugins who want to understand why a shortcut isn't doing what they expected.

## What it does

- `:WhyKey <shortcut>` — shows the file and line that bound the shortcut, and what it actually does.
- `:WhyKeyConflicts` — scans every mode for **prefix collisions** (a short shortcut that's blocking a longer one from ever firing).
- `:WhyKeyTrace <shortcut>` — shows the full history of who bound the key, with timestamps.
- Resolves `<Plug>` mappings one step so you see the real behavior, not the alias.
- On Neovim 0.10 and newer, shows real file paths instead of internal script IDs.

## Status

Pre-release (experimental). The public interface will stabilize with the version 0.1.0 tag.

## What you'll need

- Neovim 0.10 or newer (older versions work but show script IDs instead of paths)
- No other dependencies

## Where to get it

[github.com/jedi-knights/keymap-forensics.nvim](https://github.com/jedi-knights/keymap-forensics.nvim)
