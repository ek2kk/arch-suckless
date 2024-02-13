Needed packages:
sudo pacman -S base-devel git neovim
git for cloning
neovim for configs
sudo pacman -Sy xorg-server xorg-xinit libx11 libxft webkit2gtk
xorg needed for dwm
.xinitrc:
  exec dwm
  .bashrc:
    startx
    
