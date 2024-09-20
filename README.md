# How-do-I-enable-Scroll-Lock-enable-keyboard-backlight-in-linux
How do I enable Scroll Lock &amp; enable keyboard backlight in linux
![image](https://github.com/user-attachments/assets/fef0b3f7-84ca-4a18-93d2-f126166e0641)

**== IT's working for me below ==**

If you just modify the
/usr/share/X11/xkb/symbols/pc

you should use a command like
sudo gedit /usr/share/X11/xkb/symbols/pc

and add the line
 modifier_map Mod3   { Scroll_Lock };
 
inside the
xkb_symbols "pc105" {

Remember to restart or log out-log in. It's enough.
