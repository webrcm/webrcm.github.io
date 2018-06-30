# web-fusee-launcher
Fusee Launcher, in a browser! Forked from [web-fusee-launcher](https://github.com/atlas44/web-fusee-launcher) by atlas44.

# Description
This is a port of [fusee-launcher](https://github.com/reswitched/fusee-launcher) to JavaScript using WebUSB. This has been mildly tested and appears to work on Linux, Android (unrooted), OSX and ChromeOS. Today, this only works on Chrome because only Chrome implements WebUSB. It also does NOT work on Windows because the WebUSB Windows implementation does not allow sending the required USB packet.

# Try it out
Either use a web server to host the files (must be on https!) or you can try the [atlas44's demo](https://atlas44.s3-us-west-2.amazonaws.com/web-fusee-launcher/index.html).

We have a rehosted version at [switch.exploit.fortheusers.org](https://switch.exploit.fortheusers.org) as well.
