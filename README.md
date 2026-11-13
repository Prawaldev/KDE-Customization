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

> [!NOTE]
> These configurations are primarily customized for my KDE Plasma environment on CachyOS. Your experience may vary depending on your distribution, desktop environment, and installed packages.
>
> Some configurations might work perfectly fine on other desktop environments, while others may require a few adjustments. In particular, **Waybar, Kitty, and Fastfetch** may need some changes.
>
> I haven't used many desktop environments myself, so I can't guarantee compatibility with every DE.

## Before Using

> [!WARNING]
> Don't blindly copy everything without checking the configuration paths first.
>
> **Remember to change the username in the configuration files.**
>
> For example, in my Fastfetch configuration:
>
> ```json
> "source": "/home/prawalcachy/Pictures/hk.png"
> ```
>
> `prawalcachy` is my Linux username. Replace it with your own:
>
> ```json
> "source": "/home/your_username/Pictures/hk.png"
> ```
>
> Also check other hardcoded paths before applying the configurations.

## A Small Tip

> [!TIP]

> Take whatever you like, change the colors, adjust the modules, rearrange things, and make it yours. These are personal configurations, not strict rules for how a Linux desktop should look.

---

<p align="center">
  Made for my own desktop, shared for anyone who finds it useful.
  <br><br>
  
</p>