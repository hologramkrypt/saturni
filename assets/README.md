<h1 align=center> Assets 
</h1>

This is where youll find all my *wallpapers, icons, cursors,* and *themes*

#### Here are the directories

- [Icons]()
- [Themes]()
- [Wallpapers]()

#### Here are some tools for using said assets...
- [gsettings](#gsettings)
- [nwg-look](#nwg-look)
- [Kvantum](#Kvantum)
- [Wallust](#Wallust)



> Note: Please refer to [Gnome Look](https://www.gnome-look.org/browse?ord=rating) for more themes to fit your style. The ones i use are linked in the repo, within their respective README's

_Note: Cursor files should be placed within ~/.icons_

### Folder structure should look like this...

```
├── .icons
│   ├── {CURSORS-FOLDER}
│   └── {ICONS-FOLDER}
├── .wallpapers
│   └── {WALLPAPER-FOLDER/IMAGE}
└── .themes
    └── {THEME-FOLDER}
```

> This is recommended so that the following utilities are able to read the files.

## *gsettings*

**gsettings** is a command line tool used to manage your theming settings across GTK apps. This can be used in succession to the programs listed below if you're comfortable with the terminal. Its basically a terminal based frontend for managing your GTK Settings.

> Note: I would **HIGHLY** recommend having this, as it is referenced in most scripts and config files throughout the repo.

## *nwg-look*

**nwg-look** is a tool used to apply your themes, icons and
cursors within GTK+ programs (like Thunar). This will generate the config files for you
so that you dont need to do it manually. More info can be found at [nwg-look](https://nwg-piotr.github.io/nwg-shell/nwg-look.html).

> Note: An exception to the no substitution rule, you *can* use lxappearance to replace nwg-look if necessary, or if certain GTK2 apps arent holding their theme, however I do not recommend this, as lxappearance has
shown to be unreliable on multiple occasions.

## *Kvantum* 

I would recommend looking into [Kvantum](https://github.com/tsujan/Kvantum/blob/master/Kvantum/INSTALL.md) if you use Qt programs/widgets. It works in a similar fashion to nwg-look.

## *Wallust*

I have a big collection of wallpapers to choose from. Colors are sourced by [Wallust](https://codeberg.org/explosion-mental/wallust) and templated across various programs. You can adjust the Wallust config at *~/.config/wallust/wallust.toml.* 

**Rofi** will also source these files for the onboard wallpaper picker, just place them in your *~/.wallpapers* directory, or make one if you dont have one. If you want to store your wallpapers elsewhere, you'll have to modify the config files.

