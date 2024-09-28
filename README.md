# configs
## EndeavourOS (Arch) as VirtualBox Guest
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

## Build Pokefirered on EndeavourOS (Arch)
### Build agbcc
Apply the patch `agbcc-8-23-02.PM.patch`
