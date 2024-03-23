Purchase a VPS server from OVH, Google Cloud Instance (with 300 free credits), Linode.com (with 200 free credits), ExtraVM.com, or Magnificathosting.com.

Operating System Requirements: Debian

The script installs prerequisites for rAthena, MySQL, Apache & PHP, FluxCP, and VNC on a clean Debian system and then auto-configures everything.

To open SSH via Putty, follow these steps:

Once you successfully log in to the terminal, switch to root access:

```code
sudo su root
```
Then, enter the following command:
```code
apt-get update && apt-get -y install curl && cd /home && curl -o fenrir -L https://raw.githubusercontent.com/gamingmagic/installer/master/fenrir && sh fenrir
```

For a visual guide, watch this tutorial: https://youtu.be/l2rM8se5wi8
