# Linux Config

## Hyprland

### Install packages

```
sudo pacman -S hyprland uswm micro foot firefox git waybar hypridle
```

### Nvidia

https://wiki.hyprland.org/Nvidia/

### Waybar and Hypridle

```
systemctl --user enable --now waybar.service
systemctl --user enable --now hypridle.service
```

### Git

```
git config --global user.name "John Smith"
git config --global user.email user@email.com
git config --global init.defaultBranch main
```
