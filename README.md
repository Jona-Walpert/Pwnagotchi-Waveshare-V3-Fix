# Pwnagotchi-Waveshare-V3-Fix
Quick fix guide for Waveshare-E-paper hat 2.13 Inch with the [Raspberry pi Zero W(H)](https://www.amazon.com/s?k=raspberry+pi+zero+wh&crid=26154PSP0IA2F&sprefix=%2Caps%2C161&ref=nb_sb_ss_recent_1_0_recent)

## !!Read everything before you start!!

## How to fix
To make the display work, you need to download this WS V3 fixed OS version of the Panagotchi.
You can download the OS here: [OS Download Link](https://ia601507.us.archive.org/view_archive.php?archive=/25/items/pwnagotchi_1.5.5_WSV3Patched/pwnagotchi_1.5.5_WSV3Patched.rar)
The easiest way to flash the image is by using the [Raspberry Pi Imager](https://www.raspberrypi.com/software/)

### Config
After flashing, add the config.toml file to the micro SD card, which you can also find in this repository. In that config.toml file, you should change the whitelist `network-SSID` and `another Network-SSID` to your own home network-SSID so your Pwnagotchi won't deauth your own devices. If you want, you can keep the grid enabled (`main.plugins.grid.enabled = true`). If not, change that setting to _"false"_.
The same thing applies to the grid report. If you enabled the grid, then you should put the same SSIDs in, as mentioned before. If you want to use the web GUI, you can use your desired username and password instead of `username` and `password` (Edit: changing login credentials didn't work for me. The default login credentials are "changeme" "changeme". If you don't plan on using the web GUI, you can delete all those lines that start with `ui.web`).

If you want to know how to access the web GUI, you can follow along with this [video](https://www.youtube.com/watch?v=km81ph7pZz8&t=1014s) after minute 14:09.

## final step
Now you can insert your micro SD card back into your Raspberry Pi.
You are ready to go. Power it up and enjoy!


![20230830_233324](https://github.com/Jona-Walpert/Pwnagotchi-Waveshare-V3-Fix/assets/98217482/5cfae935-961b-4dab-b932-2c8f7e5a5c28)


