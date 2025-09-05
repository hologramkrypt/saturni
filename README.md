<h2 align=center> Saturni for Hyprland
</h2>

## Directory
-  [Introduction](#Introduction)
-  [Installation](#Installation)
-  [Theming](#Theming)
-  [To-Do](#To-Do)
-  [Attributions](#Attributions)

## Introduction

This repository contains the **core configuration** files of my workstation.
I run Fedora Workstation 42 with Hyprland. Please reference the Fedora wiki, as well as the Hyprland wiki for more information on configuring.
This is simply what i use on the day to day. Because of that it is a constant work in progress.

---

## Clone Repository

```bash
git clone https://github.com/hologramkrypt/saturni.git
cd saturni
```

---

## Installation

> **⚠️ Note:**  
> Substituting dependencies may break the build or result in missing features.

### Core Dependencies

| Program   | Purpose                 |
|---------- |------------------------ |
| bash      | Shell                   |
| copyq     | Clipboard tool          |
| fastfetch | System info grabber     |
| feh       | Image viewer            |
| grim      | Screenshot tool         |
| hyprland  | Window manager          |
| kitty     | Terminal                |
| nvim      | Text editor             |
| nwg-look  | GTK theming agent       |
| rofi      | Application launcher    |
| swaybg    | Wallpaper renderer      |
| hyprlock  | Lockscreen              |
| swaync    | Notification center     |
| thunar    | File manager            |
| wallust   | Color manager           |
| waybar    | Taskbar                 |
| wlogout   | Alternative logout menu |
| swww      | Wallpaper changing tool |


#### 🔧 Install Core Dependencies

```bash
sudo dnf install hyprland kitty nautilus grim copyq waybar rofi feh swaybg swaync wallust wlogout swaylock nwg-look fastfetch nvim
```

> _Note: If certain programs like `nwg-look` or `swww` are not available in your distro's repository, you may need to build them manually._

---

<details>
  <summary> Optional Dependencies </summary>

| Program     | Purpose                  |
|------------ |------------------------- |
| btop        | Resource monitor         |
| cava        | Terminal visualizer      |
| cmatrix     | Terminal matrix effect   |
| htop        | System monitor           |
| Kvantum     | Theme manager            |
| pavucontrol | Audio device mixer       |
| xsettings   | GTK settings             |
| zed         | Alternative text editor  |

#### Install Optional Dependencies

```bash
sudo dnf install cava btop htop cmatrix
```

</details>

---

## Theming

More information can be found in the [assets README.md](https://github.com/hologramkrypt/saturni/tree/main/assets#assets).

> This configuration is highly flexible. Feel free to use your own wallpapers, icons, and themes to personalize the experience. All configs should meld with basically any color scheme.

I do recommend checking out [Gnome Look](https://www.gnome-look.org/browse?cat=135&ord=rating) for some cool themes. Just drop them into your *~/.themes* directory. 
Icons go in the *~/.icons* directory.

> _Note: Cursor file packs go into the ~/.icons directory._

---

## To-Do

- [ ] Optimize config structure
- [x] Wallust configuration for cava

---

## Attributions

This build is inspired by and largely based on  
👉 [JaKooLit's Hyprland Dots](https://github.com/JaKooLit/Hyprland-Dots)

---
