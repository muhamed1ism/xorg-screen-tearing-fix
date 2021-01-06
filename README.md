# xorg-screen-tearing-fix

Make new X11 configuration directory

$ mkdir -p /etc/X11/xorg.conf.d/


Create new configuration file "20-intel.conf"

$ sudo nano /etc/X11/xorg.conf.d/20-intel.conf


Put the configuration written in first-option, save the file and restart X11 session
If it doesn't work and you still have screen tearing then try second option

Edit: Even better option is to use modesetting driver. Just delete xf86-video-intel package.
