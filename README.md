# Dotfiles
## Paths
Following directories and files should be located in specified locations:
- hypr: ~/.config/
- hyprpanel: ~/.config/
- palettes: ~/.config/
- rofi: ~/.config/
- power-lines: /usr/share/sddm/themes/
- sddm.conf: /etc/
- kitty: ~/.config/
## hyprland.conf
To use rofi, hyprlock, hyprpaper and hyprpanel you need to add following lines to your hyprland.conf:
### rofi
```
$menu = rofi -show drun -theme ~/.config/rofi/launcher.rasi
```
### hyprlock
```
$screenlock = hyprlock

bind = $mainMod, L, exec, $screenlock
```
### hyprpaper
```
exec-once = hyprpaper
```
### hyprpanel
```
exec-once = hyprpanel
```
