<h1 align=center> Saturni for Hyprland
</h1>

## Directory
-  [Introduction](#Introduction)
-  [Installation](https://github.com/hologramkrypt/saturni/blob/master/github/INSTALL.md)
-  [Assets](https://github.com/hologramkrypt/saturni/blob/master/assets/README.md)
-  [Configuration](https://github.com/hologramkrypt/saturni/blob/master/configs/README.md)
-  [To-Do](#To-Do)
-  [Attributions](#Attributions)

## Introduction

This repository contains the **core configuration** files of my workstation.
I run Fedora Workstation 42 with Hyprland. Please reference the Fedora wiki, as well as the Hyprland wiki for more information on configuring.
This is simply what i use on the day to day. Because of that it is a constant work in progress.

<p>
  I recommend doing your research on the dependencies and repositories needed for this. There are certain items in the hyprland ecosystem such as "hyprpaper" and "hyprlock" that require hyprlands repo. There are certain things you can configure and swap out but it will usually break things.


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

Read [INSTALL.md](https://github.com/hologramkrypt/saturni/blob/master/github/INSTALL.md) for more information on installing dependencies and configuring the system.

---

## To-Do

- [ ] Optimize config structure
- [x] Wallust configuration for cava
- [ ] Optimize for github
- [ ] Optimize for templatability

---

## Attributions

This build is inspired by and largely based on  
👉 [JaKooLit's Hyprland Dots](https://github.com/JaKooLit/Hyprland-Dots)

---
