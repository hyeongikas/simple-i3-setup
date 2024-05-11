# i3 Config Files

This repository contains my personal old i3 window manager configuration files. I don't remember all the dependancies I used.

## Installation

### Dependencies

Make sure you have the following dependencies installed:

- `i3-wm`: The window manager itself.
- `i3status`: A status bar for i3.
- `i3lock`: Screen locker for i3.
- `dmenu`
(- `rofi`: A window switcher, application launcher, and dmenu replacement.)

You can install them on Ubuntu/Debian based systems using:

```bash
sudo apt-get install i3-wm i3status i3lock rofi
```

You can install them on Arch Based Systems using:

```bash
sudo pacman -S i3-wm i3status i3lock rofi
```

or

```bash
sudo yay -S i3-wm i3status i3lock rofi
```


## Installation Process


1: Clone this repository:
```
git clone https://github.com/your-username/i3-config.git ~/.config/i3
```

2: Copy the config and i3status.conf files to the appropriate directories:
```
cp ~/.config/i3/config ~/.config/i3/config.backup  # Backup your existing i3 config file, if any
cp ~/.config/i3/i3-status.conf ~/.config/i3status.conf
```

3: Restart i3 for changes to take effect.
```
i3-msg restart
```

OR

CTRL + Shift + R


