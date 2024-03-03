# web-fusee-launcher
Fusee Launcher, in a browser! Forked from [web-fusee-launcher](https://github.com/atlas44/web-fusee-launcher) by atlas44.

# Description
This is a web port of [fusee-launcher](https://github.com/reswitched/fusee-launcher) to JavaScript using WebUSB.

It works on Linux, Android (unrooted), OSX and ChromeOS. It does NOT work on Windows because the WebUSB Windows implementation does not allow sending the required USB packet.

# Try it out
Visit online at: https://webrcm.github.io

Original source code is at: [atlas44's demo](https://atlas44.s3-us-west-2.amazonaws.com/web-fusee-launcher/index.html).

# Linux Info
If you get can access denied error, create a file at `/etc/udev/rules.d/50-switch.rules` with the following contents:

```
SUBSYSTEM=="usb", ATTR{idVendor}=="0955", MODE="0664", GROUP="plugdev"
```