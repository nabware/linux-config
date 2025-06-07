# Linux Config

## Hyprland

### Install packages

```
sudo pacman -S hyprland uswm micro foot firefox git waybar hypridle \
pipewire pipewire-audio pipewire-alsa pipewire-pulse pipewire-jack wireplumber
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

### WirePlumber

```
wpctl status
wpctl set-default 54
```
