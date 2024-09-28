# configs
## EndeavourOS as VirtualBox Guest
### Make desktop resolution match window dimensions
```
sudo pacman -Syu
sudo pacman -S virtualbox-guest-utils
sudo systemctl enable vboxservice
sudo systemctl start vboxservice
reboot
```
```
xrandr --auto
```

