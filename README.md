# osd_countdown

A countdown which uses the X On-Screen Display library for Linux OS desktops

Usage example:

`osd_countdown --wait 66 --message "Time out!" --font "-*-nimbus mono-*-*-*-*-70-*-*-*-*-*-*-*"`

The default font is freemono. To correctly choose the desired font, it's recomendable to use the  
application **xfontsel**:
1. Execute the command: `xfontsel -print`
2. Choose an available font
3. Press the *quit* button, you'll get the name of the font at the terminal console.
4. Include the name of this font when executing osd_countdown. Don't forget quoting the name of the  
font if it has spaces.

---
To compile, type 'make'.  
To install, type 'make install'.  

For help, osd_countdown -h.  Simple enough.
