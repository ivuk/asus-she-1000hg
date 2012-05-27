## asus-she-1000hg  ##

A couple (two, exactly :) ) of scripts that enable toggling of ASUS' Super Hybrid Engine to performance or powersaving mode.

The original versions of the scripts came from [here] (http://idolinux.blogspot.com/2012/01/fedora-16-xfce-on-eee-pc.html), these are modified versions that work for me. Standard YMMV *disclaimer* is implied.

You should already have *eeepc_laptop* kernel module loaded, otherwise the scripts will do nothing. The *99asus_superhe_power* script should be placed in the */etc/pm/power.d/* directory, and the *99asus_superhe_sleep* should be placed in the */etc/pm/sleep.d/* directory. Make sure that the scripts are executable.
