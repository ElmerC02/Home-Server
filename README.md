# Home-Server
Documenting the creation of my Home Server and everything that will be added into it to make my life infinitely easier.

This Home Server will be ran on a Raspberry Pi 5, 8 GB Model. Will look to upgrade to cluster if it gets overwhelming, but this should be fine for now.

# STEP 1 - Set Up Raspberry Pi for headless connection
1. Using this link: https://www.raspberrypi.com/software/ , I installed the Raspberry Pi imager onto my PC to flash RPi OS onto a 128 GB Micro SD Card. I ensured that my personal settings were applied to the SD card such as Wi-Fi SSID and Password, and enabled SSH connections to remotely connect to my server.
2. Once the SD Card was inserted and the device was powered on, I used the terminal on my PC to SSH onto the Raspberry Pi : ```Ssh tgmelmer@PiServer.local```
3. Connection was established, so I ran a command to enable VNC on the RaspberryPi: ```Sudo raspi-config``` > Interface Options > VNC > Enable.
4. I used VNCViewer by RealVNC (https://www.realvnc.com/en/connect/download/viewer/) to establish a VNC connection to the Raspberry Pi. I am now able to control the Home Server through other computers locally.
