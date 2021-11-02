# archi3
i3config for Arch
Special thanks to https://github.com/addy-dclxvi/i3-starterpack

# Installation:
First, install i3wm 
sudo pacman -S i3-wm dunst i3lock i3status



compton hsetroot rxvt-unicode xsel rofi fonts-noto fonts-mplus xsettingsd lxappearance scrot viewnior

# Additional Arch Packages you probably want and fixes:
sudo pacman -S i3-wm dunst i3lock i3status
sudo pacman -S  compton hsetroot rxvt-unicode xsel rofi xsettingsd lxappearance scrot viewnior
sudo pacman -S dmenu
sudo pacman -S screenfetch
sudo pacman -S nitrogen
sudo pacman -S kdenlive
sudo pacman -S breeze
sudo pacman -S ffmpegthumbnailer
sudo pacman -S vlc
sudo pacman -S htop
sudo pacman -S a52dec faac faad2 flac jasper lame libdca libdv libmad libmpeg2 libtheora libvorbis libxv wavpack x264 xvidcore gstreamer0.10-plugins
sudo pacman -S flatpak

# Fix Potential Sound Issues Arch:
sudo pacman -S alsa-firmware

# Integrate AppImages
trizen -S appimagelauncher

# Edit configs: [Ctrl+H in file manager to view hidden files via GUI]
~/.config/i3/config
~/.config/i3status/config
