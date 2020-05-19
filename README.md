# Installation
- paste `candy-icons` into `usr/share/icons`
- paste `Sweet-Dark` into `usr/share/themes`
- paste folder into `etc/regolith/styles/custom`
- `regolith-look set custom`
- `regolith-look refresh`
- set `ZSH_THEME="af-magic"` in `~/.zshrc`
- `sudo apt install rxvt`
- make changes to `~/.config/regolith/i3/config`:
	* `bindsym $mod+Return exec /usr/bin/urxvt # /usr/bin/x-terminal-emulator`
	* `smart_gaps invers_outer # on`
	* add `i3bar_command i3bar --transparency` to bar configuration
- paste `.Xdefaults` into `~`
- paste `colorschemes` into `~/.config/ranger`
- in `rc.conf` change `set colorscheme custom # default`
- comment `Theme = black_theme` and uncomment `XTermTheme = transparent-background` in `~/.moc/config`

# Resources
- https://www.gnome-look.org/p/1305251/ (candy-icons Icon Theme)
- https://www.gnome-look.org/p/1253385/ (Sweet-Dark GTK Theme)

