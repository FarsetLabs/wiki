Assumptions
===========

You've got a stock Pi up and running and are vaguely familiar with the command line

Pre-Install
===========

sudo nano /etc/hostname  
This will open an editor to let you change the hostname of your pi. Change it to something memorable like your full name or your dogs name, then press Ctrl+X then Y to save it. Then reboot your Pi

Install
=======

cd; mkdir src; cd src;  
Get yourself to a source directory to play in

curl <https://raw.github.com/adafruit/Adafruit-WebIDE/alpha/scripts/install.sh> | sudo sh  
Download the WebIDE installation files from Adafruit (this may take some time) and run them as the boss (sudo turns you into the root user)

sudo service adafruit-webide.sh start  
Starts the WebIDE service on port 80 by default

On your pi or another computer open your web browser to <http://><hostname> and Adafruit will walk you through the set-up.

Beyond this point it's so well documented it's not worth talking about.
