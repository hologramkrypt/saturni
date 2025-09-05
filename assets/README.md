<h1 align=center>Assets</h1>

This section contains all my **wallpapers, icons, cursors, and themes**. These are my personal choices; feel free to experiment and find what works best for you.

---

### What I Use

- [Icons](https://github.com/hologramkrypt/saturni/blob/8bfdc7fb72d86a5eeec35403eeb1fffff1f34946/assets/.icons/README.md)  
- [Themes](https://github.com/hologramkrypt/saturni/blob/8bfdc7fb72d86a5eeec35403eeb1fffff1f34946/assets/.themes/README.md)  
- [Wallpapers](https://github.com/hologramkrypt/saturni/blob/8bfdc7fb72d86a5eeec35403eeb1fffff1f34946/assets/.wallpapers/README.md)  

---

### Tools for Managing Assets

- [xsettingsd](#xsettingsd)  
- [nwg-look](#nwg-look)  
- [Kvantum](#kvantum)  
- [Wallust](#wallust)  

> **Tip:** For additional themes, see [Gnome Look](https://www.gnome-look.org/browse?ord=rating). The ones I use are linked above.

_Note: Cursor files should be placed within `~/.icons`._

---

### Recommended Folder Structure

```
├── .icons
│   ├── {CURSORS-FOLDER}
│   └── {ICONS-FOLDER}
├── .wallpapers
│   └── {WALLPAPER-FOLDER/IMAGE}
└── .themes
    └── {THEME-FOLDER}
```

> Following this structure ensures that all utilities can properly read your files.

---

## xsettingsd

**xsettingsd** is a command-line tool to manage GTK/X11 theming settings across applications.  
It is lightweight, terminal-friendly, and referenced in scripts throughout this repository.

> **Recommendation:** Keep this installed; it is essential for consistent GTK behavior on Wayland/X11.

---

## nwg-look

**nwg-look** applies themes, icons, and cursors for GTK+ programs (like Thunar).  
It automatically generates necessary configuration files so manual edits are unnecessary.

More info: [nwg-look official page](https://nwg-piotr.github.io/nwg-shell/nwg-look.html)

> **Note:** You can use `lxappearance` as a fallback for GTK2 apps, but it is less reliable and not recommended.

---

## Kvantum

[Kvantum](https://github.com/tsujan/Kvantum/blob/master/Kvantum/INSTALL.md) is a Qt theme engine.  
It works similarly to nwg-look for GTK, allowing consistent styling across Qt applications.

---

## Wallust

Wallust extracts colors from your wallpaper collection and applies them across multiple programs.  
Config file: `~/.config/wallust/wallust.toml`

**Integration:**

- Place wallpapers in `~/.wallpapers` for Rofi wallpaper picker support.  
- For custom locations, update Wallust config paths.  
- Templates allow dynamic color schemes based on wallpapers.
