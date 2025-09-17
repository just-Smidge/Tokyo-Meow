# Tokyo-Meow - A Gnome rice tutorial by just-smidge
<screenshot>

# Links & credits
r/unixporn post: <br>
wallpaper: unknown (if you know of or are the creator please let me know so i can creddit you)


# Programs
## pacman repo
### Gnome tweaks
Arch: sudo pacman -S gnome-tweaks

### 7z
Arch: sudo pacman -S p7zip

### Flatpak ⚠️only install if you dont already have it⚠️
Arch: sudo pacman -S flatpak

### Discover ⚠️only install if you dont have the gnome software store⚠️
Arch: sudo pacman -S discover

### Misc packages
Arch: sudo pacman -S imagemagick optipng findutils

## Flathub
### Gear lever
<a href="https://flathub.org/en/apps/it.mijorus.gearlever">gear lever flathub</a>

## Appimage
### Pling store
<a href="https://www.pling.com/p/1972991/">Pling store pling</a>
once downloaded open gear lever and click the + in the top left

find the downloaded file in the file browser gear lever opens
eg: pling-store-x.x.x-x-x86-64.AppImage (insted of x it will show the programs version number)

unlock the appimage

finaly click "move to the app menu"

now you can launch pling store

# Gnome shell extentions

# How to install shell extention configs

# Plings
if pling store is asking for remote interaction and the popup wont go away just ignor the popup and bring focus back to the pling store
you will have to use the side scroll bar to navigate up and down if this happens

### Cursor: <a href="https://www.pling.com/p/1932768">Simp1e Cursors</a>
click install and find the file named
File name: Simp1e-Tokyo-Night.tar.xz

### Icons: <a href="https://www.pling.com/p/1187019">DarK</a>
⚠️download this file normaly, do not let pling auto install⚠️
click download and select the file

once downloaded cd into the location of the file
eg: cd ~/Downloads/DarK-icons-master/

allow the script to run as a program
eg: chmod +x build_svg.sh

then run build_svg.sh
eg: ./build_svg.sh

after thats done building cd into the built directory

alow the script changecolor.sh to run
eg: chmod +x changecolor.sh

then run changecolor.sh
eg: ./changecolor.sh

you will be asked for 2 colors in hex (also knows as #RRGGBB)
the 1st color is #7da6ff
the 2nd color is #1f2335

once the script is done open the DarK-icons-master folder location in your file explorer
eg: ~/Downloads/DarK-icons-master/

ctrl-c or cut the DarK-svg folder

navagate to your home directory 
eg: ~

find a folder named .icons if you dont already have this folder create it
eg: ~/.icons/

paste the DarK-svg folder into the .icons folder

open gnome tweaks and in the apperances tab set icons to Dark-svg

# gnome tweaks settings



core extra multilib
