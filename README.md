# raspi-usb-ctl

Script for controlling the usb ports of the Pi 5, 2 usb 3.0 and usb 2.0.

In order to use the command 'usbctl' place the bash into /usr/local/bin/ .

Place the service file into /etc/systemd/system/.

The thing will initially disable the 4 ports and if you need one, just enable that port or enable all.

This is for security purpose, if you cant separate / lock away the device from unathorized ppl.

Usage:

sudo usbctl enable / disable a / all / 1 / 2 / 3 / 4

sudo usbctl status

Wait for few seconds to update, plug in a pendrive or keyboard and do 'lsusb'.

No need to restart anything or replug any device.

EDIT:

The ports are at least for me is the following on the image

![Raspberry_Pi_5_VS_Raspberry_Pi_4-3054459869](https://github.com/user-attachments/assets/5ed28bc5-66fb-4305-98c3-f4171af14eae)
