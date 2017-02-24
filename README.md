# mbit-keynote
Control your Keynote presentation with a BBC micro:bit using [node-bbc-microbit](https://github.com/sandeepmistry/node-bbc-microbit)

## Prerequisites

Flashing micro:bit firmware

 1. Save hex file from [firmware folder](firmware/) to computer.
 1. Connect micro:bit to computer using USB cable.
 1. Copy hex file to micro:bit disk drive.
 1. Calibrate magnetometer, by rotating micro:bit around in a circle.

## Usage

* Install module dependencies
```
npm install
```

* Run in a terminal 
```
node index.js
```

* Control your presentation using the micro:bit's buttons. 
 1. Button A - previous slide.
 1. Button B - start the presentation, and next slide.

