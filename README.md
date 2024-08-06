# UM980_RPI_Hat_RtkBase

### Raspbian compatible RtkBase software for Unicore UM98x, Bynav M2x and Spetentrio Mosaic X5

Based on RtkBase

## Easy installation:
+ Connect your Unicore or Bynav receiver to your raspberry pi/orange pi/....

+ Open a terminal and:

  ```bash
  wget https://raw.githubusercontent.com/GNSSOEM/UM980_RPI_Hat_RtkBase/main/install.sh
  chmod +x install.sh
  ./install.sh
  ```
+ RTFM

## Two phase installation:

+ ./install.sh -1 for part of installation without receiver
+ ./install.sh -2 for part of installation with receiver

## main feature, added to RtkBase

+ Use Unicore, Bynav or Septentrio receiver
+ Full configure for receiver and Raspberry Pi
+ If mount and password are both TCP use TCP-client instead of NTRIP-server
+ Setup base position to receiver
+ Timeout for PPP-solution is extended to 36 hours
+ Default settings is adopted to Unicore, Bynav or Septentrio receiver, onocoy.com and rtkdirect.com
+ Windows RTK & HAS utilitis for precise resolving rtkbase position
+ Zeroconf configuration as rtkbase.local in the local network
+ Then speed changed in main settings, speed of receiver will be changing too
+ Configuring WiFi via an Windows application  (not only on first boot)
+ Adding users via an Windows application  (not only on first boot)
+ �omplete documentation with lots of pictures

## License:
UM980_RPI_Hat_RtkBase is licensed under AGPL 3 (see [LICENSE](./LICENSE) file).

UM980_RPI_Hat_RtkBase uses [RtkBase](https://github.com/Stefal/rtkbase) (GPL v3)
