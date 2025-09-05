<h1 align=center>
Wallpapers
</h1>

- [Wallust](#Information-on-Wallust)
- []()
- []()


### Information on Wallust

##### Wallust config files will be located at...
```
├── .config
       ├── wallust
              ├── wallust.toml
              ├── templates
                     ├── colors-hyprland.conf
```

Wallust is a program that basically grabs the colors from an image. In the **.config** directory, you can find my wallust configuration. 

###### wallust.toml = configuration file
###### colors-hyprland.conf = template

<p>
  I have also created paths to run wallust whenever I change the wallpaper, which helps in maintaining a cohesive colorscheme without having to run wallust manually. Running wallust from the terminal will do the same thing, however there are certain rofi menus that will refresh wallust to the current wallpaper, as welkl as refreshing waybar, rofi, and nwg-look.
</p>

> You can create templates in *~/.config/wallust/templates* to be sourced by your programs. I have included some extra templates, however for individual cases you might need to build the template from scratch.

> IMPORTANT:  I would recommend tweaking the settings in *wallust.toml*. There are many that I have changed myself to maintain my dark color scheme, however if you like something else or find it too dark, check out the config file.
