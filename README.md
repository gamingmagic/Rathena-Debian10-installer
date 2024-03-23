# rAthena Installer

Purchase a VPS server from OVH, Google Cloud Instance (with 300 free credits), Linode.com (with 200 free credits), ExtraVM.com, or Magnificathosting.com.

Operating System Requirements: Debian 11

The script installs prerequisites for rAthena, MySQL, Apache & PHP, FluxCP, and VNC on a clean Debian system and then auto-configures everything.

## Installation

To open SSH via Putty, follow these steps:

1. Once you successfully log in to the terminal, switch to root access:
   
   ```
   sudo su root
   ```

2. Then, enter the following command:
   
   ```
   apt-get update && apt-get -y install curl && cd /home && curl -o fenrir -L https://raw.githubusercontent.com/gamingmagic/installer/master/fenrir && sh fenrir
   ```

## Tutorial

For a visual guide, watch this tutorial: [Full Video](https://youtu.be/l2rM8se5wi8)

## Discord Channel

Join our Discord Channel for support and discussions: [Discord Invite Link!](https://discord.gg/pyzWeeJz3T)

##Other Links:
Connecting to your rAthena Server using New client: [Full Video](https://www.youtube.com/watch?v=ulCkVJWO5Vk)
Viewing or Using rAthena Server in VNCVIEWER: [Full Video](https://www.youtube.com/watch?v=QSz73gbWxAA)

## Credits

This installer is based on the installation guide provided by [rAthena](https://github.com/rathena/rathena/wiki/installations) and Crying-Akkarin. Special thanks to the rAthena for their contributions to the Ragnarok Private community.
