# Linux Config

## Hyprland

### Install packages

```
sudo pacman -S hyprland uswm micro foot firefox git waybar hypridle \
ttf-liberation ttf-dejavu noto-fonts noto-fonts-emoji ttf-roboto ttf-opensans \
pipewire pipewire-audio pipewire-alsa pipewire-pulse pipewire-jack wireplumber \
bluez bluez-utils \
grim slurp
```

### Nvidia

https://wiki.hyprland.org/Nvidia/

### Waybar and Hypridle

```
systemctl --user enable --now waybar.service
systemctl --user start --now waybar.service
systemctl --user enable --now hypridle.service
systemctl --user start --now hypridle.service
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

### Bluetooth

```
systemctl enable bluetooth.service
systemctl start bluetooth.service
bluetoothctl
scan on
devices
pair MAC_address
trust MAC_address
connect MAC_address
exit
```
