# Dotfiles - SleoNiiX

Welcome to my dotfiles repository!  
This repo stores my configs for ricing my PC, mainly Hyprland, Waybar, and bash tweaks.

---

## 📋 Contents

- Hypr config (`~/.config/hypr`)  
- Waybar config (`~/.config/waybar`)  
- Bash config (`~/.bashrc`)  

---

## 🚀 Installation

These are manual steps so you keep control over what you want to apply.

### 1. Clone the repo

```bash
git clone https://github.com/SleoNiiX/dotfiles.git
cd dotfiles
```

### 2. Copy config files

```bash
# Backup your current configs first if needed!

mkdir -p ~/.config/hypr
cp -r hyprland/* ~/.config/hypr/

mkdir -p ~/.config/waybar
cp -r waybar/* ~/.config/waybar/

cp bash/bashrc ~/.bashrc
```

### 3. Install dependencies

Make sure you have these installed:
 - hyprland
 - waybar
 - pywal (for dynamic colors, see below)
 - hyprpaper (wallpaper manager for Hyprland)
 - hyprlock (screen locker compatible with Hyprland)
 - bash (of course!)

On EndeavourOS / Arch:
```bash
sudo pacman -S hyprland waybar pywal hyprpaper hyprlock
```

### 4. Using Pywal
If you want dynamic colors on your Waybar and other apps:
```bash
wal -i /path/to/your/wallpaper.jpg
```

---

## 🛠 My insparation

Go check them, they explain better than me :
 https://github.com/elifouts/Dotfiles

---

> Enjoy ;)
