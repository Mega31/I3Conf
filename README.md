# I3Conf
# A simple i3 config
You just need to have rofi and feh
## Fix for xbacklight(for controling brightness in i3 if you run into)
```bash
sudo nano /etc/X11/xorg.conf.d/20-video.conf
#In it copy this

Section "Device"
    Identifier  "Intel Graphics"
    Driver      "intel"
    Option      "Backlight"  "intel_backlight"
EndSection


```
