SUR40 - Multi-Touch Table

- Install Ubuntu Desktop 16.04
- Get ReacTIVision (https://github.com/mkalten/reacTIVision)
- Get TUIO 11 Processing (https://github.com/mkalten/TUIO11_Processing)
- Get TUIO 11 C++ (https://github.com/mkalten/TUIO11_CPP)



Ubuntu (deb) Dependencies:

apt-get install build-essential libsdl2-dev libdc1394-22-dev libjpeg-turbo8-dev libsdl1.2-dev freeglut3-dev libusb-dev

# Build ReacTIVision
reacTIVision/linux $ make

# Build TUIO 11 C++
TUIO11_CPP $ make

# Run ./view
$ ./view

Seg fault:
usb_get_device_handle( ID_MICROSOFT, ID_SURFACE );
is returning NULL


