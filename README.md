# NixOS Configuration

Personal **NixOS + Home Manager** configuration.

---

## Repo Layout

``` txt
nixos/
├── flake.nix
├── flake.lock
├── README.md
├── hosts/
│   └── <hostname>/
│       ├── configuration.nix
│       └── hardware-configuration.nix
├── home/
│   └── <username>/
│       ├── home.nix
│       └── modules/
│           ├── hyprland.nix
│           ├── waybar.nix
│           └── packages.nix
└── dotfiles/
    ├── hypr/
    └── waybar/
```
