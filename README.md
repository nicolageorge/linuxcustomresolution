# linuxcustomresolution
```
sudo vim /etc/gdm3/custom.conf
sudo vim /etc/gdm3/daemon.conf

uncomment WaylandEnable=false

/sbin/reboot

xrandr --listmonitors
xrandr --output Virtual1 --mode "2560x1440_60.00"
cvt 2560 1440
xrandr --newmode "2560x1440_60.00"  312.25  2560 2752 3024 3488  1440 1443 1448 1493 -hsync +vsync
xrandr --addmode Virtual1 2560x1440_60.00
xrandr --output Virtual1 --mode 2560x1440_60.00
```
