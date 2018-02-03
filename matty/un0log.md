
#### 2018-02-02 Flashing Un0rick oki

* Done! With the code, it works. I just need to rmmod ftdi_sio and usbserial before flashing with programmer from usb.

![](/matty/images/IMG_20180202_233901.jpg)

* CDONE is on, weak LED corresponds to 64Mhz signal (same in the dark)

![](/matty/images/IMG_20180202_233921.jpg)

* See [this repo](/matty/prog_flash/) which contains the hex/bin files, the ice40.xcf for as the programmer save, and prog to start the programmer without cumbersome kernel modules.
* Still having issues with the FTDI-SPI pinouts


#### 2018-02-01 Un0rick clock oki

* Clock is soldered again! And FTDI device magically appears in lsmod.

![](/matty/images/IMG_20180203_131837.jpg)

### 2018-01-26 -- The clock had to be removed!

Investigation showed no connection through USB.. a ftdi issue. Powers were OK.. but still nothing.

So what? __Clock!!__

I unfortunately destroyed the 12MHz clock.. well that's it =) I'll be waiting for the new one from digikey.


![](/matty/images/IMG_20180126_200809.jpg)

The clock has to be rotated by 90°

![](/matty/images/20180126--compare.png)


### 2018-01-23 -- More on the next session !

Let's have a first peek

![](/matty/images/IMG_20180115_194856.jpg)

This has reached a couple of days ago =)

Looks good - ice40 and ram look good. The high-level pulser footprint seems reversed. The 3.3V is on, 5V level looks good, seems good!


### 2017-12-15 Others

![](/include/uniBoard/unimatty-2a.png)

### 2017-11-19 First ideas

![](/include/uniBoard/unisimple.jpg)


## BORN !

![](/matty/images/arf.jpg)