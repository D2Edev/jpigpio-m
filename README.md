# jpigpio-m

A fork from [jpigpio](https://github.com/nkolban/jpigpio) library.

What's added:

* project mavenized
* native C lib is included in jar and loaded automatically if requested

## Pls, note

* Your app should have root privileges to work with Pigpio class (which uses native lib)
* Otherwise use PigpioSocket which communicates with [pigpiod](http://abyz.me.uk/rpi/pigpio/pigpiod.html)

