# Largarto KDE theme
Lagarto, a KDE theme openSUSE color palette. 

# Overview
<p align="center">
  <img src="https://s10.postimg.org/dvqid79sp/splash.png" alt="Preview Lagarto"/>
</p>

<p align="center">
  <img src="https://s10.postimg.org/6j8pbs9i1/Sem_t_tulo.png" alt="Preview Lagarto"/>
</p>

<p align="center">
  <img src="https://s10.postimg.org/s5npsuxsp/Sem_t_tulo1.png" alt="Preview Lagarto"/>
</p>

# Based and modified
- Splashscreen from [Arc KDE](https://github.com/PapirusDevelopmentTeam/arc-kde)
- Plymouth from [GnomeGecko](https://plus.google.com/u/0/111682190684743279128/posts/6UjfioLwYeh?cfem=1)
- Theme, wallpaper and icons [from Nomad](https://github.com/nomad-desktop/nomad-plasma-look-and-feel), [Adapta](https://github.com/adapta-project) and [Aex Nomad](https://github.com/Madkita/Plasma-Themes/tree/master/Aex%20Nomad)

Inspiraded by [Erdlowe GTK Theme](https://github.com/DarthWound/erdlowe-gtk-theme).

# Installation

Made for Leap 42.3.

```
$ git clone https://github.com/ViniciusBRodrigues/Largarto-KDE-theme.git
$ cd Largarto-KDE-theme/
$ cp -r Lagarto $HOME/.local/share/plasmalook-and-feel/
$ cp -r Lagarto-reptilia $HOME/.local/share/desktoptheme/
$ sudo cp Lagarto.colors /usr/share/color-schemes/
$ sudo cp wallpaper.png /usr/share/wallpapers/
$ sudo cp lockscreen.png /usr/share/wallpapers/
$ sudo cp -r KDELagarto /usr/share/plymouth/themes/
$ sudo plymouth-set-default-theme -R KDELagarto
```

Open System Setings and choose the Wallpaper, Lockscreen, Color Scheme, Window Decoration, Splash Screen and Desktop Theme.

# To do

- [ ] Improve Lagarto.colors
- [ ] Icon theme
- [ ] Dark version
