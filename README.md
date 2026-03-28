# Coastal for Omarchy

Coastal is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`coastal`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `coastal`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `coastal`
- **Omarchy theme repo:** `omarchy-coastal-theme`

The Omarchy theme and the Neovim theme are intended to match visually:

- Omarchy applies the desktop/application theme files
- Neovim uses the `coastal` colorscheme
- both are built around the same palette

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

Omarchy uses the files in this repo for theme integration across supported applications and interface components.

For the editor, this Omarchy theme is expected to be paired with the Neovim theme `coastal`.

## Naming convention

- **Omarchy repo:** `omarchy-coastal-theme`
- **Neovim theme:** `coastal`

## Goal

The goal is a coherent full-system theme where Omarchy and Neovim feel intentionally connected.
