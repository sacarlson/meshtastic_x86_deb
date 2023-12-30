This is an debian installable version of meshtasticd.
The binary executable was extracted from the docker release of meshtastic version 2.2.15.31c4693
The debian structure was mostly copied from the pi arm version of debian realease.
Install as you would any other debian file example sudo dpkg -i meshtastic_xxx.deb
to run just open terminal and and type "meshtasticd"
after it's running you can configure it like you would any other meshtastic device with the meshtastic phone app
in the phone app enter the IP address of the computer you are running meshtasticd on.
to find the ip address of your linux computer try ipconfig
Note you will have to restart the app after you set configuration.  it will note this in the debug data on the screen
This has been tested on Linux Mint 21.2 Victoria 64-bit
