<h1 align=center>
  Installation Guide
</h1>

This will go through installing all the necessary dependencies and tools utilized throughout the build. Reminder that this is build for a Fedora 42 system.

### Table of contents
* [My hardware](#System-specs)
* [Required repositories](#Required-repositories)
* [Dependencies](#Dependencies)
  * [Optional dependencies](#Optional-dependencies)
* [Configuration](#Notes-on-configuring-the-system)

---

### System specs

|     🪐        |   🚀          |
| ------------- | -------------------------------------------------|
|    GPU        |   Geforce RTX 3080                               |
|    CPU        |   Intel Core i9-9900k                            |
|    MEMORY     |   32GB DDR4                                      |
|    STORAGE    |   11 TB Server + 2 TB SSD + 1 TB HDD             |
|    TERMINAL   |   Kitty                                          |
|    OS         |   Fedora Linux 42                                |
|    WM         |   Hyprland 0.50.1                                |
|    SHELL      |   Fish 4.0.2                                     |

---

### Required repositories

```

```

---

### Dependencies

> **⚠️ Note:**  
> Substituting dependencies may break the build or result in missing features.

| Program                                                        | Purpose                 |
|----------------------------------------------------------------|------------------------ |
| bash                                                           | Shell                   |
| [copyq](https://github.com/hluk/CopyQ/releases/tag/v9.0.0)     | Clipboard tool          |
| [fastfetch](https://github.com/fastfetch-cli/fastfetch/blob/dev/README.md) | System info grabber     |
| [feh](https://feh.finalrewind.org/)                            | Image viewer            |
| [grim](https://man.archlinux.org/man/grim.1.en)                | Screenshot tool         |
| [hyprland](https://wiki.hypr.land/Getting-Started/Master-Tutorial/)  | Window manager          |
| [kitty](https://sw.kovidgoyal.net/kitty/)                      | Terminal                |
| [nvim](https://neovim.io/)                                     | Text editor             |
| [nwg-look](https://nwg-piotr.github.io/nwg-shell/nwg-look.html)  | GTK theming agent       |
| [rofi](https://github.com/davatorium/rofi)                     | Application launcher    |
| [swaybg](https://github.com/swaywm/swaybg/blob/master/README.md)    | Wallpaper renderer      |
| [hyprlock](https://github.com/hyprwm/hyprlock/)                | Lockscreen              |
| [swaync](https://www.mankier.com/1/swaync)                     | Notification center     |
| [thunar](https://github.com/neilbrown/thunar)                  | File manager            |
| [wallust](https://codeberg.org/explosion-mental/wallust)       | Color manager           |
| [waybar](https://github.com/Alexays/Waybar/wiki/Examples)      | Taskbar                 |
| [wlogout](https://github.com/ArtsyMacaw/wlogout/blob/master/README.md)   | Alternative logout menu |
| [swww](https://github.com/LGFae/swww/blob/main/README.md)      | Wallpaper changing tool |
| [sddm](https://github.com/sddm/sddm)                           | Login manager           |


  Please note that certain dependencies will work in place of others, ie. *swaybg* can be substituted for *hyprpaper* or *feh*. Please consult the [Configuration README](https://github.com/hologramkrypt/saturni/blob/master/configs/README.md) for more info
  <p> Most dependencies can be installed through the command line like this: </p>

```bash
sudo dnf install copyq fastfetch feh grim hyprland kitty nvim rofi swaybg hyprlock swaync thunar wallust waybar wlogout swww sddm
```

<details>
  
  <summary> Optional dependencies </summary>
  
<p></p>

> **⚠️ Note:**
> These dependencies are optional, however I do recommend looking into them as they are integrated throughout my theme

| Program                                                    | Purpose                  |
|------------------------------------------------------------|------------------------- |
| [btop](https://www.tecmint.com/btop-system-monitoring-tool-for-linux/)        | Resource monitor         |
| [cava](https://github.com/nerdnoise/cava)                                     | Terminal visualizer      |
| [cmatrix](https://www.cyberciti.biz/open-source/command-line-hacks/matrix-digital-rain-on-linux-macos-unix-terminal/)                                                                 | Terminal matrix effect   |
| [htop](https://www.geeksforgeeks.org/linux-unix/htop-command-in-linux-with-examples/)        | System monitor           |
| [Kvantum](https://github.com/tsujan/Kvantum/blob/master/Kvantum/INSTALL.md)   | Theme manager            |
| [pavucontrol](https://www.freedesktop.org/software/pulseaudio/pavucontrol/)   | Audio device mixer       |
| [xsettingsd](https://wiki.archlinux.org/title/Xsettingsd)                     | GTK settings             |
| [zed](https://zed.dev/)                                                       | Alternative text editor  |

</details>

---

### Notes on configuring the system

 


