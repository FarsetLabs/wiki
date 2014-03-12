Installation
============

Connect your LEDBorg to the PI **before you turn it on**

Once logged in, open a terminal:

``` {.bash}
mkdir -p ~/src/ledborg     #Create a directory to work in
cd ~/src/ledborg           # and move into it
# The next line downloads an interface between the Pi and the LEDBorg
# Which file to download depends on the board you are using
# Follow the instructions in the Package section of this webpage
# http://piborg.org/ledborg/install

wget -O setup.zip http://www.piborg.org/downloads/ledborg/raspbian-*********.zip
unzip setup.zip
chmod +x install.sh
./install.sh
```

After these steps, the light on the LEDBorg should now be blue. If it isn't, you may not have selected the correct interface package, so check back on [this page](http://piborg.org/ledborg/install) for the conditions.

From this point on, if you echo a set of three numbers between 0-2, it will be converted into an RGB colour on the LEDBorg, for example 000 is off, 222 is bright white, 200 is red, 110 makes a kind of purple (by mixing red and green light)

Check out the [LEDBorg examples page](http://piborg.org/ledborg/examples) for more advanced usages in a variety of languages
