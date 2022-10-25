*Modifications after fresh fedora-i3 installation*

# 1. remove packages

azote
nano
i3lock
dmenu

# 2. add required repositories

flathub (flatpka)
google chrome stable
docker cd stable
rpm fusion for fedora 36 free
rpm fusion for fedora 36 nonfree

# 2. install packages

## basic functionality & workspace

i3blocks 
python3-i3ipc
xsetroot
rofi
scrot
lxpolkit
lxappearance
arandr
autorandr
highlight
powerline-fonts
ranger
pasystray
blueman
xfce4-power-manager
xev
xprop
sysstat
lm_sensors

## media players

firefox
google chrome
w3m
mpv
spotify (flatpak)
cmus
evince
mupdf
zathura
zathura-plugins-all
zathura-pdf-mupdf

## media utilities

audacity
scribus
inkscape
gimp
musescore
transmission-gtk
nicotine+
soundconverter
imagemagick

## devtools, systools & nettools
ncdu
perl-File-MimeInfo
vim
neovim
syncthing
git
docker-ce
VirtualBox
VirtualBox-guest-additions
htop
kubernetes
minikube (loose package)
flatseal (flatpak)
postman (flatpak)
visual studio code (flatpak)
eclipse IDE (flatpak)

## productivity
libreoffice
xarchiver
discord
anki
sdcv
keepassxc
jabref (flatpak)
teams-for-linux (flatpak)
solanum (flatpak)

## media library mgmt
beets
calibre

# Provisioning & configuration

## .bashrc
history improvements
autocompletion
aliases
ranger() to prevent nested instances

## vim 
.vimrc airline and solarized theme
airline powerline fonts

## lightdm
laptop-only.sh
lightdm.conf display-setup-script

## i3wm
modular config
autorandr settings

## fonts
iosevka slab and iosevka nerd fonts

## custom scripts
get backup scripts

## additional services
power manager service
syncthing service

## other programs
sync firefox
copy calibre configuration

