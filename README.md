# xorg-input-mtrack-config
My config file to make MacBook trackpads behave nicely under Linux


Install mtrack:  
`sudo apt-get install xserver-xorg-input-mtrack`
 
If that doesn't work (I got the broken packages error), use Ubuntu Software Center to install one of the Transitional packages (e.g. trusty for 14.04).

Then:  
`sudo vi /etc/X11/xorg.conf.d`

Paste in the contents of my [xorg.conf.d](https://raw.githubusercontent.com/JimSangwine/xorg-input-mtrack-config/master/xorg.conf.d)

Finally:  
`sudo restart lightdm`

See here for mtrack options: https://github.com/BlueDragonX/xf86-input-mtrack 
