<h1 align=center>
Wallpapers
</h1>

- [Wallpaper Display](#Displaying-the-wallpaper)
- [Wallust](#Information-on-Wallust)

### Dependencies

<h4 align=center>

| Program                                                            | Purpose                         |
|--------------------------------------------------------------------|---------------------------------|
| [swww](#swww)                                                      | Changing tool                   |
| [swaybg](#swaybg)                                                  | Wallpaper display               |
| [hyprpaper](#hyprpaper)                                            | Alternative wallpaper display   |
| [feh](#feh)                                                        | Alternative wallpaper display   |

</h4>


---


## Displaying the wallpaper

### swww

> swww is used in some scripts to change the values within other configs. You can find specifics within the *wallpaperselect.sh* or *Wallustswww.sh*

start by initilizing the daemon. (you can put this in your *hyprland.conf* so that it starts in the background)
```
swww-daemon
```
then pass it an image to display it.
```
swww img {$image}
```

### swaybg

> You can run swaybg when hyprland starts, like in *~/.config/hypr/configs/autoruns.conf*

```
swaybg --image {$image}
```

### hyprpaper

```
# Load an image into memory
preload = ~/.wallpapers/{image}

# Apply it to a specific monitor
wallpaper = monitor, ~/.wallpapers/{image}

# Or apply to all monitors without a set wallpaper
wallpaper = , ~/.wallpapers/{image}
```

### feh

> Like swaybg, you can run feh to display your wallpaper at startup from your hyprland config.

```
feh {$image} --bg-center
```

## Information on Wallust

##### Wallust config files will be located at...
```
├── .config
       ├── wallust
              ├── wallust.toml
              ├── templates
                     ├── colors-hyprland.conf
```

Wallust is a program that basically grabs the colors from an image. In the **.config** directory, you can find my wallust configuration. It is my favorite tool for customization in hyprland... 

###### wallust.toml = configuration file
###### colors-hyprland.conf = template

<p>
  I have also created paths to run wallust whenever I change the wallpaper, which helps in maintaining a cohesive colorscheme without having to run wallust manually. Running wallust from the terminal will do the same thing, however there are certain rofi menus that will refresh wallust to the current wallpaper, as welkl as refreshing waybar, rofi, and nwg-look.
</p>

> You can create templates in *~/.config/wallust/templates* to be sourced by your programs. I have included some extra templates, however for individual cases you might need to build the template from scratch.

> IMPORTANT:  I would recommend tweaking the settings in *wallust.toml*. There are many that I have changed myself to maintain my dark color scheme, however if you like something else or find it too dark, check out the config file.

