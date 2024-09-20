# How-do-I-enable-Scroll-Lock-enable-keyboard-backlight-in-linux

<h4><strong>== IT's working for me below ==</strong></h4>
<p>If you just modify the&nbsp;</p>
<p><code>/usr/share/X11/xkb/symbols/pc</code></p>
<p>you should use a command like&nbsp;</p>
<p><code>sudo gedit /usr/share/X11/xkb/symbols/pc</code></p>
<p>and add the line&nbsp;</p>
<p><code>modifier_map Mod3 { Scroll_Lock };</code></p>
<p><code>inside the xkb_symbols "pc105" {</code></p>
<p><i>Remember to restart or log out-log in. It's enough.</i></p>
<br>

How do I enable Scroll Lock &amp; enable keyboard backlight in linux

![image](https://github.com/user-attachments/assets/fef0b3f7-84ca-4a18-93d2-f126166e0641)

