Assumptions
===========

You've got a stock Pi up and running and are vaguely familiar with the command line

Pre-Install
===========

`sudo nano /etc/hostname`

This will open an editor to let you change the hostname of your pi. Change it to something memorable like your full name or your dogs name, then press Ctrl+X then Y to save it. Then reboot your Pi

Install
=======

Get yourself to a source directory to play in:

```sh
cd
mkdir src
cd src

```


Download the WebIDE installation files from Adafruit:
`curl "https://raw.github.com/adafruit/Adafruit-WebIDE/alpha/scripts/install.sh" | sudo sh`

Starts the WebIDE service on port 80 by default
`sudo service adafruit-webide.sh start`

On your pi or another computer open your web browser to http://<hostname> and Adafruit will walk you through the set-up.

Beyond this point it's so well documented it's not worth talking about.
