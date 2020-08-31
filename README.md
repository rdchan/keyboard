# keyboard
qmk files and such for my lily58
![Peripherals](/images/full.jpg)

# updates

Custom OLED Display!
I finally got around to fixing the oled connections. I like seeing what the community is doing with their oled screens, but I'm perfectly content with just static images. My philosophy is that my eyes should be on my monitors, not looking down at my keyboard for information. The screens are just for the cool factor for me. That being said, I like the lily58 logo, but don't really care to print out what layer is active. So I put some other logos that I think are neat. Used high resolution images as a template and traced them in GIMP to then generate a bmp. I used [Joric's QMK Logo Editor](joric.github.io/qle) to help convert from the bmp to hex that I could put in the firmware. I like the vertical look better, but haven't checked if it correctly rotates on auto-detection of primary/secondary half.

![Custom Logo](/images/triplelogo.bmp)

Here's what it looks like on the keeb

![Triple Logo](/images/lefthalf.jpg)

First update was adding an encoder to the default keymap. I used the chuan keymap files for reference and liked the PageUp and PageDown features. They integrate nicely with firefox (hold ctrl and use encoder to scroll through tabs!). 
I'd like to add a couple more layers, using space and enter with tap/hold and the standard raise/lower for actually changing layers (persistent akin to caps lock). One of these layers would be some sort of media layer, where the encoder could be used for volume. Sometimes you have to mouse-click to select a chat window before using PageUp and PageDown. Emulating mouse clicks could be interesting. I don't want to emulate mouse movement, I don't think it'd beat a real mouse. Trackball integration would be neat though...
