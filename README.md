# Clash Premiun Installer

Simple clash premiun core installer with full tun support for Linux.



### Usage

1. Install dependencies **git**, **nftables**, **iproute2**

2. Clone repository

   ```bash
   git clone https://github.com/tom-snow/clash-premium-installer.git
   cd clash-premium-installer
   ```

3. Download clash core [link](https://github.com/Dreamacro/clash/releases/tag/premium)

4. Extract core and rename it to `./clash` (the clash core should in the 'clash-premium-installer' folder)

5. Edit `./scripts/clash.service` and set your `CLASH_URL` (note that subscribe address shouldn't have "&" symbol, if it have, you should convert it to a short url)

6. Run Installer

   ```bash
   ./installer.sh install
   ```


<br/><br/><br/>
**If you do not set clash subscribe link or want to change clash subscribe link, Please edit `/usr/lib/systemd/system/clash.service` . When finished please run `systemctl daemon-reload`**

### Clash web

[clash.razord.top](http://clash.razord.top/)