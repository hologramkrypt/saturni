# saturni

I use this every day on my main rig. This repository contains the **core configuration** of my system.

---

## Clone Repository

```bash
git clone https://github.com/hologramkrypt/saturni.git
cd saturni
```

---

## 🛠️ Installation Guide

> **⚠️ Note:**  
> Substituting dependencies may break the build or result in missing features.

### 📦 Core Dependencies

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
  <summary>🧩 Optional Dependencies</summary>

| Program     | Purpose                  |
|------------ |------------------------- |
| btop        | Resource monitor         |
| cava        | Terminal visualizer      |
| cmatrix     | Terminal matrix effect   |
| htop        | System monitor           |
| Kvantum     | Theme manager            |
| pavucontrol | Audio device mixer       |
| xsettings   | GTK settings             |

#### Install Optional Dependencies

```bash
sudo dnf install cava btop htop cmatrix
```

</details>

---

## Theming

More information can be found in the [assets README.md](https://github.com/hologramkrypt/saturni/tree/main/assets#readme).

> This configuration is highly flexible. Feel free to use your own wallpapers, icons, and tweaks to personalize the experience.

I do recommend checking out [Gnome Look](https://www.gnome-look.org/browse?cat=135&ord=rating) for some cool themes. Just drop them into your *~/.themes* directory. 
Icons go in the *~/.icons* directory.

> _Note: Cursor file packs go into the ~/.icons directory._

---

## ✅ To-Do

- [ ] Beautify config structure
- [ ] Add delight to the experience when all tasks are complete 😄

---

## Notes & Credits

This build is inspired by and largely based on  
👉 [JaKooLit's Hyprland Dots](https://github.com/JaKooLit/Hyprland-Dots)

---
