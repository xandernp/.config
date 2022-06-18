to install for the i3 window manager and on arch linux: copy this command into your terminal,
```
sudo pacman -Syu feh firefox flameshot imwheel kitty lxappearance materia-gtk-theme neofetch numlockx papirus-icon-theme pavucontrol picom polybar pulseaudio rofi thunar thunderbird xfce4-power-manager && sudo rm -r ~/.config && cd && git clone https://github.com/xandernp/.config && sudo rm -r ~/.config/.git
```
and then restart i3 with 
```
super+shift+r
```
