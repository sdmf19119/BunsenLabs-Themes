# BunsenLabs-Themes
Themes from BunsenLabs for use in ArchLabs

Only tested using libgtk-3.0 (3.22.8), YMMV.

Includes gtk-2.0/gtk-3.0, lightdm-gtk-greeter,
Openbox and xfce4-notifyd themes. The notification
theme is backwards compatible with xfce4-notifyd (0.2.4).

Some matching wallpapers are in my bunsen-wallpapers repository...  
https://github.com/hhhorb/bunsen-wallpapers

Bunsen-Blackish-Remix  
  
[![Screenshot_2017-03-09_11-44-34.md.png](https://cdn.scrot.moe/images/2017/03/09/Screenshot_2017-03-09_11-44-34.md.png)](https://scrot.moe/image/1wT76)

SoftWaves  
  
[![Screenshot_2017-03-07_21-40-27.md.png](https://cdn.scrot.moe/images/2017/03/08/Screenshot_2017-03-07_21-40-27.md.png)](https://scrot.moe/image/1wED0)

To remove GTK3's "overlay scrollbars" and their indicators...

In ~/.xsessionrc, add `export GTK_OVERLAY_SCROLLING=0`

In ~/.config/gtk-3.0/gtk.css, add...

```
/* Remove dotted lines from GTK+ 3 applications */
undershoot.top, undershoot.right, undershoot.bottom, undershoot.left { background-image: none; }
```

Also, I recommend installing gtk3-nocsd to give GTK3 applications a more uniform look...  
https://packages.debian.org/stretch/gtk3-nocsd
