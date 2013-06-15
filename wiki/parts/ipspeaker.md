# Speaker Nodes

The nodes signal using [SIP](http://en.wikipedia.org/wiki/Session_Initiation_Protocol). Any device capable of being an SIP endpoint can be a node. i.e a common IP phone. But for the purpose, it needs to be autoanswering.

We built a prototype node using [RaspberryPi](http://raspberrypi.org), it was cheaper than other alternatives.

## Configuring RaspberyPi as an IP speaker.

 1. Install [raspbian from here](http://www.raspberrypi.org/downloads)
 2. Follow [USB device check list](http://elinux.org/Rpi_USB_check-list) to remove glitches from the onboard audio.
 3. Install linphone and use the `linphone` headless deamon `linphonecsh` to recieve calls.
 4. Use the [following script to configure linphone](https://github.com/AriaCET/linphone-webconf).