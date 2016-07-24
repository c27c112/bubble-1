# Bubble
### Setup Raspberry Pi with Rappbian Jessie Lite (headless mode)
#### Step 1: Run raspbianizer.sh
- Specify the correct device path to the fresh SD card (e.g. /dev/sdd, /dev/sde, or /dev/sdx)
- Check that the SD card does not have partitions
- Example:
```sh
dustea@cup:~ $ curl -kls "https://goo.gl/V9YHPL | sudo bash -s /dev/sdx"
```

#### Step 2: Boot-up Raspberry Pi using SD card & SSH
- Take out the CD card from your computer and put it in the Raspberry Pi
- Check that the Cat 5 cable connects between your router and the Raspberry Pi
- Ensure the USB holding your data is connected to the Pi before powering up
- Example:
```sh
dustea@cup:~ $ ssh pi@192.168.8.64
```

#### Step 3: Run install.sh script
```sh
pi@raspberrypi:~ $ curl -kls "https://goo.gl/YDto5p" | sudo bash
```

#### Appendix A: Router Configuration Notes
- Change the router address to 192.168.8.1
- Change the wifi address to a different one from the default, ##bubbleteacup1
- Change the SID to "Brightlink"
- IP Pool Start Address: 192.168.8.64
- IP Pool End Address: 192.168.8.100
- Add a static address and bind to the Raspberry Pi, 192.168.8.64
