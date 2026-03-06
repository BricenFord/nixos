# Hyprland Config Guide

## If using Nvidia

https://wiki.hypr.land/Nvidia/

## Must have programs

notification daemon - mako  
pipewire - pipewire & wireplumber  
XDG desktop portal - xdg-desktop-portal-hyprland  
authentication agent - hyprpolkitagent  
Qt wayland support - qt5-wayland & qt6-wayland  
font - sans-serif

## Monitors (changes by monitor layout)

https://wiki.hypr.land/Configuring/Monitors/

List available monitors:  
hyprctl monitors all

Monitor config:  
ex: monitor = name, resolution, position (use 0x0), scale (use 1)

## Pick utilities (check hypr ecosystem)

https://wiki.hypr.land/Useful-Utilities/

## Cursors

https://wiki.hypr.land/FAQ#how-do-i-change-me-mouse-cursor

## Themes

Install nwg-look

## Force apps to use Wayland

You can check whether an app is running in xwayland or not with:  
hyprctl clients

## Launching Hyprland

Type start-hyprland (do not use sudo)