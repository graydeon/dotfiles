# Arch Linux Dotfiles

Personal Arch Linux / Hyprland workstation configuration.

## Current environment

- Arch Linux
- Hyprland 0.56+
- Waybar
- Wofi
- Mako
- Kitty
- Thunar
- Hyprlock / Hypridle
- NetworkManager
- PipeWire

## Layout

Each top-level directory mirrors its destination beneath `$HOME`.

Examples:

- `hypr/.config/hypr/`
- `waybar/.config/waybar/`
- `kitty/.config/kitty/`

`packages/pacman-explicit.txt` contains the explicitly installed Arch packages.

This repository intentionally excludes credentials, VPN state, browser profiles,
SSH keys, keyrings, and other secrets.
