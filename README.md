# NixOS Configuration

Personal NixOS + Home Manager configuration.

> **Status:** Home Manager is not configured yet. Setting up Home Manager and per-application modules is the next step.

---

## Repo Layout

``` txt
nixos/
├── flake.nix
├── flake.lock
├── README.md
├── configuration.nix
├── home/
│   ├── home.nix
│   └── modules/
│       ├── hyprland.nix
│       ├── waybar.nix
│       └── packages.nix
└── dotfiles/
    ├── hypr/
    └── waybar/
```

## Usage

Apply the config from this repository:

```bash
nix flake update
sudo nixos-rebuild switch --flake .#de
sudo reboot
```
