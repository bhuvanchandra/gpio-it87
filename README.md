## Introduction
---

### Building

Use the in-tree makefile to build the kernel module, make sure the kernel headers of the running
kernel are installed on the machine.

### Installing

Installing the kernel module:
```
# make install
```
NOTE: Installing will overwrite the kernel module already available on the machine.

### Auto loading the kernel module

To auto load the kernel module at boot run:

```
# echo 'gpio-it87' > /etc/modules-load.d/gpio-it87.conf
```
