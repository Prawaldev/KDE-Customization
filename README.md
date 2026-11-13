# KDE Customization


<p align="center">
  A simple collection of my personal Linux desktop configurations.
  <br>
  Customized and used with <b>CachyOS + KDE Plasma</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-CachyOS-1793D1?style=flat-square&logo=arch-linux&logoColor=white">
  <img src="https://img.shields.io/badge/Desktop-KDE%20Plasma-1D99F3?style=flat-square&logo=kde&logoColor=white">
  <img src="https://img.shields.io/badge/Configs-Personal-8A7FFF?style=flat-square&logo=linux&logoColor=white">
</p>

---

## About

Nothing too complicated here. Just my personal desktop customization that I use every day on **CachyOS with KDE Plasma**.

This repository contains the configurations, themes, and assets behind my setup. It's not intended to be a universal dotfiles collection or a one-size-fits-all desktop setup. It's simply what works perfectly for me.

## What's Included

| File / Directory | Description |
|:---|:---|
| `fastfetch/` | Fastfetch configuration and system information layout |
| `kitty/` | Kitty terminal configuration |
| `waybar/` | Waybar modules, styling, and layout |
| `wofi/` | Wofi launcher configuration |
| `fastfetch-image.png` | Image used for Fastfetch customization |
| `starship.toml` | Starship prompt configuration |
| `wallpaper.png` | Desktop wallpaper |

## Compatibility

<blockquote>
  <b>Note:</b> These configurations are primarily customized for my KDE Plasma environment on CachyOS. Your experience may vary depending on your distribution, desktop environment, and installed packages.
</blockquote>

Some configurations might work perfectly fine on other desktop environments, while others may require a few adjustments.

In particular, **Waybar, Kitty, and Fastfetch** may need some changes depending on your setup. I haven't used many desktop environments myself, so I can't guarantee compatibility or provide accurate instructions for every DE.

Feel free to modify things to suit your own environment.

## Before Using

<blockquote>
  <b>Warning:</b> Don't blindly copy everything without checking the configuration paths first.
</blockquote>

One important thing: **change the username in the configuration files.**

For example, in my Fastfetch configuration:

```json
"source": "/home/prawalcachy/Pictures/hk.png"
```

`prawalcachy` is my Linux username. You'll need to replace it with your own username and make sure the image exists at that location.

For example:

```json
"source": "/home/your_username/Pictures/hk.png"
```

Also check other hardcoded paths before applying the configurations.

## A Small Tip

You don't have to use the entire setup.

Take whatever you like, change the colors, adjust the modules, rearrange things, and make it yours. These are personal configurations.

---

<p align="center">
  Made for my own desktop, shared for anyone who finds it useful.
  <br><br>
  <sub>Built around CachyOS + KDE Plasma.</sub>
</p>