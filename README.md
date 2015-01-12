# NovaShell
A GNOME Shell theme focused on simplicity

**Works with Gnome 3.14**  
You'll find legacy versions [here](http://gnome-look.org/content/show.php?content=151522)  


## Normal installation
* Extract the zip-file and put the NovaShell-directory into `~/.themes` or install via gnome-tweak-tool (Theme > Shell-Theme)
* Select NovaShell with `gnome-tweak-tool` (You'll need the user-themes-extension)


## Installation as default theme
NovaShell will be the **default** theme for all users and gdm!  
* copy NovaShell-directory into `/usr/share/themes/`
* rename /usr/share/gnome-shell/theme to `/usr/share/gnome-shell/theme.original`  
  `$ sudo mv /usr/share/gnome-shell/theme /usr/share/gnome-shell/theme.original`
* create a symbolic link to `/usr/share/gnome-shell/theme`  
  `$ sudo ln -s /usr/share/themes/NovaShell/gnome-shell /usr/share/gnome-shell/theme`
* log out and log in again
