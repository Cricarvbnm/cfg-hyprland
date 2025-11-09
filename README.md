# Hyprland Configuration

Hyprland configuration in nixos. Prefer configuring in hyprlang.

## Config Path

Hyprland configuration is in ./hypr. Configurations are in drop-in directory.

## Content

Core Components

- Bar: waybar
- Notification: swaync
- Clipboard: copyq
- Menu: wofi
- Terminal Emulator: kitty
- Locker: hyprlock
- Wallpaper: hyprpaper
- Idle: hypridle

Other Components

- Browser: Firefox
- Torrent Manager: qBittorrent-enhanced
- Plugins:
  - hyprexpo (workspace overview)

## Note

Hyprlock and hypridle configurations are not in this repository.

Hyprlock is included for keybindings.

Hypridle is started as a systemd service.

Configurations for the components are not included.
Some are in other repositories.
