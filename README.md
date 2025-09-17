# Tokyo-Meow - A Gnome rice tutorial by just-smidge
<screenshot>

# Links & credits
r/unixporn post:<br>
wallpaper: unknown (if you know of or are the creator please let me know so i can creddit you)

# Fonts
### fira code
Arch: sudo pacman -S ttf-fira-code ttf-firacode-nerd

# Programs
## pacman repo
### Gnome tweaks
Arch: sudo pacman -S gnome-tweaks

### cava
Arch: sudo pacman -S cava

### fastfetch
Arch: sudo pacman -S fastfetch

### kitty
Arch: sudo pacman -S kitty

### zed
Arch sudo pacman -S zed

### git
Arch: sudo pacman -S git

### paru 
Arch: sudo pacman -S paru

### 7z
Arch: sudo pacman -S p7zip

### Flatpak ⚠️only install if you dont already have it⚠️
Arch: sudo pacman -S flatpak<br>
then reboot

### Discover ⚠️only install if you dont have the gnome software store⚠️
Arch: sudo pacman -S discover

### Misc packages
Arch: sudo pacman -S imagemagick optipng findutils

## AUR
### lavat
paru -S lavat-git<br>
or<br>
yay -S lavat-git

## Flathub
### Gear lever
<a href="https://flathub.org/en/apps/it.mijorus.gearlever">gear lever flathub</a>

### extension manager
<a href="https://flathub.org/en/apps/com.mattjakeman.ExtensionManager">extension manager flathub</a>

## Appimage
### Pling store
<a href="https://www.pling.com/p/1972991/">Pling store pling</a><br>
once downloaded open gear lever and click the + in the top left

find the downloaded file in the file browser gear lever opens<br>
eg: pling-store-x.x.x-x-x86-64.AppImage (insted of x it will show the programs version number)

unlock the appimage

finaly click "move to the app menu"

now you can launch pling store

# Gnome shell extentions
### Blur my Shell

### Boost Volume

### clock smart display

### Customise clock on lock screen

### Dash to Panel

### Dim background windows

### drive activity indicator

### just perfection

### launch new instance

### lockscreen extension

### notification banner reloaded

### notification timeout

### privacy indicators accent color

### rounded corners

### rounded window corners reborn

### tiling shell

### user themes

### window is ready notification remover

# How to install shell extention configs

# Plings
open the pling store app<br>
if pling store is asking for remote interaction and the popup wont go away just ignor the popup and bring focus back to the pling store<br>
you will have to use the side scroll bar to navigate up and down if this happens

### Cursor: Simp1e Cursors
<a href="https://www.pling.com/p/1932768">Simp1e Cursors</a><br>
click install and find the file named<br>
File name: Simp1e-Tokyo-Night.tar.xz

### Icons: DarK
<a href="https://www.pling.com/p/1187019">DarK</a><br>
⚠️download this file normaly, do not let pling auto install⚠️<br>
click download and select the file

once downloaded cd into the location of the file<br>
eg: cd ~/Downloads/DarK-icons-master/

allow the script to run as a program<br>
eg: chmod +x build_svg.sh

then run build_svg.sh<br>
eg: ./build_svg.sh

after thats done building cd into the built directory

alow the script changecolor.sh to run<br>
eg: chmod +x changecolor.sh

then run changecolor.sh<br>
eg: ./changecolor.sh

you will be asked for 2 colors in hex (also knows as #RRGGBB)<br>
the 1st color is #7da6ff<br>
the 2nd color is #1f2335

once the script is done open the DarK-icons-master folder location in your file explorer<br>
eg: ~/Downloads/DarK-icons-master/

ctrl-c or cut the DarK-svg folder

navagate to your home directory 
eg: ~

find a folder named .icons if you dont already have this folder create it<br>
eg: ~/.icons/

paste the DarK-svg folder into the .icons folder

open gnome tweaks and in the apperances tab set icons to Dark-svg

# github
### tokyo night GTK theme
<a href="https://github.com/Fausto-Korpsvart/Tokyonight-GTK-Theme">Tokyonight-GTK-Theme</a><br>
in the terminal git clone this repo<br>
eg: git clone https://github.com/Fausto-Korpsvart/Tokyonight-GTK-Theme.git

once downloaded cd into Tokyonight-GTK-Theme/themes<br>
eg: cd ~/Tokyonight-GTK-Theme/themes

enable the script to run<br>
eg: chmod +x install.sh

run the script with the special peramiters<br>
eg: ./install.sh -l macos

then enable flatpak apps to work with the theme by running these commands<br>
eg: sudo flatpak override --filesystem=$HOME/.themes<br>
eg: sudo flatpak override --filesystem=$HOME/.icons<br>
eg: flatpak override --user --filesystem=xdg-config/gtk-4.0<br>
eg: sudo flatpak override --filesystem=xdg-config/gtk-4.0

# gnome tweaks settings
open tweaks and navigate to the apperances tab

in the apperances tab<br>
set cursor to Simp1e-Tokyo-Night<br>
set icons to DarK-svg if you havnt already<br>
set shell to Tokyonight-Dark<br>
setlegacy application to Tokyonight-Dark

go to the windows tab<br>
and set maximise and minimise to off under the titlebar actions heading<br>
as well as making sure that placement is set to right

under click actions set center new windows to on

and under window focus set focus on hover as selected<br>
and make sure raise window when focused is set to off

finaly open fonts<br>
set interface text to FiraCode Nerd Font<br>
set document text to Adwaita Sans<br>
and set Monospace text to FiraCode Nerd Font

# finishing up
at last download this github repo<br>
eg: git clone https://github.com/just-Smidge/Tokyo-Meow.git


core extra multilib
