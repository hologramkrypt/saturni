<h1 align=center>
  Installation Guide
</h1>

This guide covers the installation of all necessary dependencies and tools for this build, specifically designed for Fedora 42 systems.

### Table of contents
* [System specifications](#system-specs)
* [Required repositories](#required-repositories)
* [Dependencies](#dependencies)
  * [Optional dependencies](#optional-dependencies)
* [Configuration](#notes-on-configuring-the-system)

---

### System specs

|     🪐        |   🚀                                             |
| ------------- | -------------------------------------------------|
|    GPU        |   GeForce RTX 3080                              |
|    CPU        |   Intel Core i9-10900K @ 5.30 GHz               |
|    MEMORY     |   32GB DDR4                                     |
|    STORAGE    |   11TB Server + 2TB SSD + 1TB HDD               |
|    TERMINAL   |   Kitty                                          |
|    OS         |   Fedora Linux 42                               |
|    WM         |   Hyprland 0.50.1                               |
|    SHELL      |   Bash                                           |

---

### Required repositories

```bash
# RPM Fusion
sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

# Hyprland Utilities
sudo dnf copr enable solopasha/hyprland
```

---

### Dependencies

> **⚠️ Note:**  
> Substituting dependencies may break the build or result in missing features.

| Program                                                                    | Purpose                 |
|----------------------------------------------------------------------------|-------------------------|
| bash                                                                       | Shell                   |
| [copyq](https://github.com/hluk/CopyQ/releases/tag/v9.0.0)                | Clipboard tool          |
| [fastfetch](https://github.com/fastfetch-cli/fastfetch/blob/dev/README.md) | System info grabber     |
| [feh](https://feh.finalrewind.org/)                                       | Image viewer            |
| [grim](https://man.archlinux.org/man/grim.1.en)                           | Screenshot tool         |
| [hyprland](https://wiki.hypr.land/Getting-Started/Master-Tutorial/)       | Window manager          |
| [hyprlock](https://github.com/hyprwm/hyprlock/)                           | Lockscreen              |
| [kitty](https://sw.kovidgoyal.net/kitty/)                                 | Terminal                |
| [mpv](https://mpv.io/installation/)                                       | Video player            |
| [nvim](https://neovim.io/)                                                | Text editor             |
| [nwg-look](https://nwg-piotr.github.io/nwg-shell/nwg-look.html)           | GTK theming agent       |
| [rofi](https://github.com/davatorium/rofi)                                | Application launcher    |
| [sddm](https://github.com/sddm/sddm)                                      | Login manager           |
| [swaybg](https://github.com/swaywm/swaybg/blob/master/README.md)          | Wallpaper renderer      |
| [swaync](https://www.mankier.com/1/swaync)                                | Notification center     |
| [swww](https://github.com/LGFae/swww/blob/main/README.md)                 | Wallpaper changing tool |
| [thunar](https://github.com/neilbrown/thunar)                             | File manager            |
| [wallust](https://codeberg.org/explosion-mental/wallust)                  | Color manager           |
| [waybar](https://github.com/Alexays/Waybar/wiki/Examples)                 | Taskbar                 |
| [wlogout](https://github.com/ArtsyMacaw/wlogout/blob/master/README.md)    | Logout menu             |

**Note:** Certain dependencies can be substituted for alternatives (e.g., *swaybg* can be replaced with *hyprpaper* or *feh*). Consult the [Configuration README](https://github.com/hologramkrypt/saturni/blob/master/configs/README.md) for more information.

Most dependencies can be installed via command line:

```bash
sudo dnf install copyq fastfetch feh grim hyprland kitty nvim nwg-look rofi swaybg hyprlock swaync thunar wallust waybar wlogout swww sddm
```
> *This command will not install everything - some packages may need manual installation*

<details>
  <summary>Optional dependencies</summary>

> **⚠️ Note:**  
> These dependencies are optional, but recommended as they are integrated throughout the theme.

| Program                                                                                                               | Purpose                  |
|-----------------------------------------------------------------------------------------------------------------------|--------------------------|
| [blueman](https://wiki.archlinux.org/title/Blueman)                                                                  | Bluetooth manager        |
| [btop](https://www.tecmint.com/btop-system-monitoring-tool-for-linux/)                                               | Resource monitor         |
| [cava](https://github.com/nerdnoise/cava)                                                                            | Audio visualizer         |
| [chafa](https://hpjansson.org/chafa/)                                                                                | ASCII/ANSI art renderer  |
| [cmatrix](https://www.cyberciti.biz/open-source/command-line-hacks/matrix-digital-rain-on-linux-macos-unix-terminal/) | Matrix terminal effect   |
| [htop](https://www.geeksforgeeks.org/linux-unix/htop-command-in-linux-with-examples/)                               | System monitor           |
| [hypridle](https://github.com/hyprwm/hypridle)                                                                       | Idle daemon              |
| [Kvantum](https://github.com/tsujan/Kvantum/blob/master/Kvantum/INSTALL.md)                                          | Qt theme manager         |
| [nm-applet](https://wiki.archlinux.org/title/NetworkManager)                                                         | Network tray indicator   |
| [pavucontrol](https://www.freedesktop.org/software/pulseaudio/pavucontrol/)                                          | Audio control GUI        |
| [xsettingsd](https://wiki.archlinux.org/title/Xsettingsd)                                                            | GTK settings daemon      |
| [zed](https://zed.dev/)                                                                                              | Alternative text editor  |

```bash
sudo dnf install blueman btop cava chafa cmatrix htop kvantum nm-applet pavucontrol xsettingsd zed
```

</details>

---

### Notes on configuring the system

Consult the [Configuration README](https://github.com/hologramkrypt/saturni/tree/master/configs#readme) for detailed per-program configuration instructions. Most configurations should work out of the box with the provided dotfiles.
