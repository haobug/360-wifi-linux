360-wifi-linux
==============

Setting up [360 Mobile WIFI] (http://wifi.360.cn/) on Linux

(1) It has been tested on ubuntu 12.04 (kernel version < 3.4.0).

(2) Linux has a bug of USB 3.0 driver (dmesg | grep "ERROR no room on ep ring"). If it does not work on USB 3.0 slots, you can try the following workaround:

    a. Insert an old USB device (USB 2.0) into the USB slot and then remove it

    b. Insert 360 Mobile WIFI into the slot

    c. Run the script

(3) This script does *not* work for the second version of the 360 wifi


