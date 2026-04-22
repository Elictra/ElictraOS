# How to install ElictraOS!
First, You need some tools. Lets just set up a quick checklist.

* A USB stick atleast like, 4 gigabytes. Sd cards MIGHT work, but you might need BalenaEtcher on windows. Idk i've never done it.
* The ElictraOS .iso file
* On windows, Rufus. https://rufus.ie/en/
* On linux and MacOS, Use https://etcher.balena.io.

Ok. Now with that out of the way, Lets get onto the tutorial.

# WINDOWS TUTORIAL.

go to https://rufus.ie/en/ and download the file named rufus-(whatever version)p.exe
im using rufus-4.13p.exe.

Next, open it. If you see this, just hit Yes.
<img width="452" height="142" alt="image" src="https://github.com/user-attachments/assets/5c22a32e-2f8d-47c5-a832-213f14607115" />

Now you should see this menu that looks like this.
<img width="469" height="538" alt="image" src="https://github.com/user-attachments/assets/fbd80f6b-8160-488e-9768-0a4f8d121fb6" />

Plug in and / or select your Usb.
Next, press the select button on the right and choose your ElictraOS iso file.
now, lets get into some important stuff really quickly.

First of all, this thing doesnt matter.<img width="466" height="50" alt="image" src="https://github.com/user-attachments/assets/98df004b-4e4c-4319-8f8b-f26b32dde3be" />

This one here DOES matter.<img width="229" height="87" alt="image" src="https://github.com/user-attachments/assets/2501e3d7-822e-402c-94c3-0827f7deafbf" />
If you have an OLDER pc, 14-20 years, select MBR. If you have a NEWER pc, 0 - 14 years or so, select GPT.

these down here dont really matter too much.
<img width="465" height="147" alt="image" src="https://github.com/user-attachments/assets/33b0795d-6900-420e-a79d-157f91c1a51d" />


Now you should have something that looks like this.
<img width="466" height="580" alt="image" src="https://github.com/user-attachments/assets/2d4eac89-77cb-49b7-bb1f-0ccb7e20d673" />

Or this.
<img width="466" height="578" alt="image" src="https://github.com/user-attachments/assets/dcbfddd7-70f4-4af9-9020-d4b7b4589b61" />

Press start and say yes until you get the the options between iso mode and dd mode. and make sure if you are on an old pc, if it asks, write in dd mode. not iso mode if you are on a newer machine, press iso mode.
Wait for it to finish.


Next, take your usb and plug it into the machine that you are installing ElictraOS on. Keep in mind that if you dont know how to dualboot (im too lazy to add that to the guide), then your windows might be fully wiped if you dont watch a tutorial for that. if you DO want to dual boot windows and elictraos, look at a linux mint dualbooting tutorial. theres tons of them out there.

Now, once your usb is plugged into said machine, you have to open your boot menu. If you dont know how, look up "how to boot into (laptop name) boot menu".
Once you are IN your boot menu, select what you think your usb drive is.

once you boot, you should see a menu like this. Just select the TOP option.
<img width="1444" height="838" alt="image" src="https://github.com/user-attachments/assets/e7c0affe-b953-41fd-b5e7-db7b2f24bda3" />


When booting is done and you are at the desktop, open the Install ElictraOS app on the desktop, Also make sure you have wifi. If your wifi isnt working, look up "Linux Mint Wifi drivers (your laptop name)" and godspeed because i hope you can get the drivers to work.<img width="1444" height="844" alt="image" src="https://github.com/user-attachments/assets/7d5bc751-4abb-43c0-b9c8-eff400b20b39" />

follow all prompts and when done, reboot your device. You should be in ElictraOS!
If not, open your boot menu and choose "ubuntu micron" or something along the lines of that

Also please star this repo. this guide took me so long to make.

# Dear Linux and Mac users.
I cant really develop a guide for linux as the last one took too long and im lazy, and for fellow mac users, it depends on your machine, but getting custom os'es can be pretty hard, atleast from what ive heard.
Sorry.
