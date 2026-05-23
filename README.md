# Kosmos Dotfiles
My personal Hyprland dotfiles, built around a Tokyo Night color scheme with gold and orange accents.
![Preview](https://github.com/user-attachments/assets/6b5904ac-5d21-4a5e-9d7b-f618aae0b0ec)
## Stack
| Component | Tool |
|-----------|------|
| Compositor | [Hyprland](https://hyprland.org) |
| Bar | [Waybar](https://github.com/Alexays/Waybar) |
| Launcher | [Wofi](https://hg.sr.ht/~scoopta/wofi) |
| Notifications | [Mako](https://github.com/emersion/mako) |
| Terminal | [Kitty](https://sw.kovidgoyal.net/kitty/) |
| File Manager | [fren](https://github.com/TheCrabeVariable/fren) (AUR) |
| Music Daemon | [MPD](https://musicpd.org) + [rmpc](https://github.com/wez/rmpc) |
| System Info | [Fastfetch](https://github.com/fastfetch-cli/fastfetch) |
| Discord Client | [Vesktop](https://github.com/Vencord/Vesktop) |
| Idle/Lock | Hypridle + Hyprlock |
| Wallpaper | Hyprpaper |
| Tablet Driver | [OpenTabletDriver](https://github.com/OpenTabletDriver/OpenTabletDriver) (AUR) |
## Theme
- **Background:** `#1a1b26`
- **Surface:** `#2a2b36`
- **Foreground:** `#e5e1cf`
- **Accent (Gold):** `#FFD600` / `#FFD700`
- **Accent (Orange):** `#f19618`
- 
All configurations follow this consistent palette across every component.
## Screenshots
![Desktop](https://github.com/user-attachments/assets/bcaadb91-1ed3-4c40-81d0-e6dc7482ccc4)
![Music](https://github.com/user-attachments/assets/9e6d5a13-a0f9-4d61-9554-cd1aabe0c5c9)
![Launcher](https://github.com/user-attachments/assets/f4a50954-1076-436c-9488-f9dc83d52318)
![Notifications & Sysinfo](https://github.com/user-attachments/assets/149429c0-c3a0-4464-bb20-12f89b98f741)
## Dependencies
**Hyprland ecosystem:**
```
hyprland hyprpaper hypridle hyprlock
hyprlang hyprgraphics hyprutils
hyprpolkitagent xdg-desktop-portal-hyprland
```
**From config (all Arch packages):**
```
waybar wofi mako kitty mpris mpd-mpris mpd rmpc fastfetch
```
**Optional:**
```
power-profile-daemon  (Arch)
opentabletdriver      (AUR)
fren                  (AUR)
```
## Installation
Clone the repo and symlink the configs:
```bash
git clone https://github.com/TheCrabevariable/Kosmos-Dotfiles.git
cd Kosmos-Dotfiles
stow Dotfiles
```
Alternatively, copy individual files from `Dotfiles/` into `~/.config/`.
## Keybindings
| Key | Action |
|-----|--------|
| `SUPER + Q` | Launch kitty |
| `SUPER + E` | Launch fren (file manager) |
| `SUPER + R` | Wofi app launcher |
| `SUPER + C` | Close window |
| `SUPER + V` | Toggle float |
| `SUPER + F` | Toggle fullscreen |
| `SUPER + Z` | Region screenshot (hyprshot) |
| `SUPER + S` | Toggle scratchpad |
| `SUPER + 1-0` | Switch workspace |
| `SUPER + SHIFT + 1-0` | Move window to workspace |
| `SUPER + M` | Exit Hyprland |
## Hardware
- Don't forget to remake the monitors with your options
---
Feel free to steal anything you like. Open an issue or PR if you have questions or suggestions.







