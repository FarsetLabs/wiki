AdvanceMAME is an arcade emulation platform, meaning that you can play thousands of retro games on your Pi (or other device; this stuff works on regular computers too!)

  
Assumes you're starting for an updated [Raspbian Wheezy](http://www.raspberrypi.org/downloads) configuration

Simple steps adapted from [here](http://blog.sheasilverman.com/2012/11/better-advancemame-debs-with-sound/) with the addition of some experience...

`$ cd ; mkdir src ; cd src ; wget <http://sheasilverman.com/rpi/raspbian/debs/advancemame-raspberrypi_1-1_armhf.deb> ; sudo dpkg -i advancemame-raspberrypi_1-1_armhf.deb`  
These commands take you to your home directory (/home/pi), create a directory called src (short for source) to keep things tidy, and to download the installation package (the .deb section) for Shea's customised AdvanceMAME setup, and then tells the pi to install it. The 'sudo' bit is the computer equivalent of saying 'please'... kinda...

`$ sudo usermod -a pi -G video`  
Within the operating system, there are users (i.e. people or identities using, controlling, or monitoring the system) and groups ('clubs' that those users are members of). Groups are a handy way of packaging and separating permissions for different types of hardware, and in this case, this command tells the pi to make the user 'pi' (you) a member of the video group. This is a safety measure just in case compatibility problems appear later...

`$ advmame`  
After all that, you're done. But you need to install some games first. That bit is coming up later...

**TODO Add Game ROMS and get started**
