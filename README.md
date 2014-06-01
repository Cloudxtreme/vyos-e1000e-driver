## Overview

This is e1000e device driver for VyOS.

__This module does not work properly yet.__

## How to build package.

    cd top_of_this_project
    debuild --set-envvar KSRC=/path/to/build-iso/pkgs/linux-image/debian/build/build-amd64-none-amd64-vyos/ -uc -us

## TODO

* Change module installation process for avoid build iso fail. 
* Rewrite debian/rules file properly. 

## Reference

* [Network Adapter Driver for PCI-E Gigabit Network Connections under Linux](https://downloadcenter.intel.com/Detail_Desc.aspx?lang=eng&amp;changeLang=true&DwnldId=15817)
