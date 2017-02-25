# mbit-keynote
Control your Keynote presentation using the buttons of your micro:bit.

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

* Control your presentation using the buttons. 
 1. Button A - shows previous slide.
 1. Button B - starts the presentation, and shows next slide.

