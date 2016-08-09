# Screentest
1) Show info about device's resolutions. It shows CSS resolution, device screen ratio, physical resolution.

2) It displays range in which you are.

# Description
Sometimes it useful to see what resolution do you have on your devices. What breakpoints we need for this device and how it will work on it.

This simple html with small JS helps. Just put it somewhere on the web and open
on your device.

You could set an array of breakpoints. There are three points and four ranges.

Examples:
```
var breakpoints = [768, 1024, 1256];
```
In such case there are 4 ranges: 0 - 768, 768 - 1024, 1024 - 1256, 1256+

For Bootstrap v4:
```
// Bootstrap v4 alpha, http://v4-alpha.getbootstrap.com/layout/overview/
// Without Extra small devices (543px)
var breakpoints = [767, 991, 1199];
```

For Desktops you can resize your screen and see what range do you have right now.
