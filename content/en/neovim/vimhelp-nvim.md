---
title: "vimhelp.nvim — search Neovim's help pages by meaning, not by tag"
description: "A full-text search engine over Neovim's built-in help documentation."
date: 2026-08-16
tags: ["neovim", "plugin", "search", "documentation"]
featured_image: "/images/gohugo-default-sample-hero-image.jpg"
---

## What it is

**vimhelp.nvim** makes Neovim's built-in help searchable by concept, not by exact tag name.

Neovim ships with excellent documentation, but finding the right page requires knowing what it's called. If you want to know how to make a "popup window," but the docs call it a "floating window," you're stuck. This plugin builds a full-text search index over every help file so you can search for a concept and get ranked, highlighted results.

Under the hood it uses a small companion tool written in [Rust](https://www.rust-lang.org) called `vimhelp-index`, which builds the index using [BM25](https://en.wikipedia.org/wiki/Okapi_BM25) — the same ranking algorithm search engines like Elasticsearch use.

## Who it's for

Anyone who has ever been frustrated by `:helpgrep`. Beginners who don't know the exact terminology. Experienced users who want faster answers.

## What it does

- **Full-text search** across every Neovim help page.
- **Ranks results by relevance** — the most useful hit is at the top.
- **Highlights matching snippets** so you can see the context without opening the page.
- **Searchable pop-up menu** via [snacks.nvim](https://github.com/folke/snacks.nvim) or [Telescope](https://github.com/nvim-telescope/telescope.nvim).
- **`:VimHelpSearch <term>`** — open the picker with search results.
- **`:VimHelpHover`** — jump to the top hit for whatever word your cursor is on.
- **Builds the index on first use** (or run `:VimHelpBuild` yourself), and updates it incrementally after that.

## Status

Pre-release (experimental). The core search and picker features work well; the public interface will stabilize with the version 0.1.0 tag.

## What you'll need

- Neovim 0.10 or newer
- The `vimhelp-index` command-line tool (install via [Homebrew](https://brew.sh) or build from source)
- An index — the plugin can build one for you on first use

## Where to get it

[github.com/jedi-knights/vimhelp.nvim](https://github.com/jedi-knights/vimhelp.nvim)
