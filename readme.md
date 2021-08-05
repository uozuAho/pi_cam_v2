# WiFi security / monitoring camera, using a Raspberry Pi Zero W

Version 2! See V1 [here](https://github.com/uozuAho/pi_cam_v1).

# to do
- images of finished product, any issues?

# parts list
- [Raspberry Pi Zero W](https://www.raspberrypi.org/pi-zero-w/)
- [night vision camera + ir LEDs](https://core-electronics.com.au/raspberry-pi-camera-board-night-vision-adjustable-focus-lens-5mp.html)
- [camera cable](https://core-electronics.com.au/raspberry-pi-zero-camera-adapter.html)
    - make sure to get a cable with a smaller connector at one end for the
      raspberry pi zero
- [generic 'jiffy box' enclosure](https://core-electronics.com.au/ub5-82lx54wx30hmm-grey-abs-jiffy-box.html)
    - 83x54x30mm
- [camera tripod](https://core-electronics.com.au/the-pi-hut-flexible-tripod.html)
- UNC nut: ? 1/4 inch, 20tpi
- SD card: class 10 16gb
- [PSU: 5v 2.5A usb micro b](https://core-electronics.com.au/raspberry-pi-3-power-supply.html)

# software
- [Raspberry Pi OS Lite](https://www.raspberrypi.org/software/operating-systems/)
  - Setup instructions [here](https://github.com/uozuAho/pi_stuff/blob/main/setup.md)

# usage
I used [termux](https://termux.com/) to log into the raspberry pi and start the
video stream, and [VLC for Android](https://www.videolan.org/vlc/download-android.html)
to watch the stream. This made it easy to position the camera.

- [video stream script](https://github.com/uozuAho/pi_stuff/blob/main/video_stream.sh)
- [video record script](https://github.com/uozuAho/pi_stuff/blob/main/video_record_loop.sh)
- [scan for motion script](https://github.com/uozuAho/pi_stuff/blob/main/video_scan.sh)
