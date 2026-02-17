# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

- `pnpm dev` — start dev server
- `pnpm build` — production build
- `pnpm preview` — preview production build

## Architecture

Astro 5 static site with Tailwind CSS 4, deployed to GitHub Pages at confluences-citoyennes.fr.

Single-page site (`src/pages/index.astro`) composed of section components.

`src/components/**` — sections components

`src/layouts/Layout.astro` — base HTML shell, loads Itim font.

`src/styles/global.css` — Tailwind import + custom theme colors (`cc-green`, `cc-yellow`, `cc-blue`, `cc-cyan`) and `font-itim`.
