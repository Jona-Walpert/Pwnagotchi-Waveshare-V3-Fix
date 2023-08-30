# Pwnagotchi-Waveshare-V3-Fix
Quick fix guide for Waveshare-E-paper hat 2.13 Inch.


##How to fix
To make the display wotk you need to download this WS V3 fixed OS version of the panagotchi
You can downlaod the OS Here: [OS Download Link](https://ia601507.us.archive.org/view_archive.php?archive=/25/items/pwnagotchi_1.5.5_WSV3Patched/pwnagotchi_1.5.5_WSV3Patched.rar)
The easiest way to flash the Image is by using the [raspberry pi imager](https://www.raspberrypi.com/software/)
After Flashing add the config.toml file, wich you can also find in this repository. In that config.toml file you should change the Whitlist `network-SSID` and `another Newtork-SSID` to your own home netowk-SSID so your pwnagotchi wont deauth your own devices. If you want you can keep the grid enabled (`main.plugins.grid.enabled = true`). If not change that setting to _"false"_.
Same thing with the grid repport. If you enabled the grid, then you should put the same SSIDs in, same as before. IF you want to use the web gui then you can put your desired username and password instead of `username` and `password`. If you dont plann on using the web gui then you can delete all those lines that start with `ui.web`

## Final step
Now you can put your micro sd card back into your raspberry pi.
If you want too know how to acces the web gui, you can follow along this video

You are ready to go. Power it up and enjoy...

