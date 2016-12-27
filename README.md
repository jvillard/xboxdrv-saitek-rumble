# xboxdrv config file for "Saitek Rumble" gamepad

This is a set of options for
[xboxdrv](https://pingus.seul.org/~grumbel/xboxdrv/) to emulate an Xbox
controller from a "Saitek Rumble" controller (see picture of
[front](./front.jpg) and [back](./rear.jpg) of the controller to decide
whether this is your controller or not).

To use:

```lang=sh
./start_xboxdrv.sh
```

Known bug: it takes a few seconds for the controller to be detected by the
script. Wait until you see events from the controller in the console in
reaction to button presses (eg `EV_ABS ABS_Y 107`).

Tested with xboxdrv version 0.8.8 on Debian stretch.
