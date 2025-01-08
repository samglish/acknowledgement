## acknowledgement
# `Aircrack-ng`
Aircrack-ng: is a suite of wireless network monitoring software whose primary use is to "crack" WEP and WPA keys of WIFI networks.

### some features
* `aircrack-ng:`static WEP and WAP-PSK key breaker (new breaker type: PTW);
* `airdecap-ng:` decryptor of captured WEP/WAP files;
* `airdriver-ng:`allows to patch drivers, for example for the case of rtl8187, which is useful for doing packet injection;
* `aireplay-ng:`packet injection program;
* `airmon-ng:`allows you to enable/disable the monitor mode of a wifi card. In this mode the wifi card acts as an "observer" of the network;
* `airodump-ng:` 802.11 packet capture program;

# `Kismet`
Kismet is a free software network detection, sniffer, and intrusion detection system for 802.11 wireless networks.

`Kismet` works with network cards that support monitor mode, and any 802.11 protocol (802.11a, 802.11b, 802.11g, and 802.11n).

It runs on Linux, FreeBSD, NetBSD, OpenBSD, and Mac OSX.

<hr>

1. Aircrack-ng
user:root
```bash
airmon-ng check kill
```