# RaspBerry


- Image - [Raspberry Pi OS (32-bit) Lite]: https://www.raspberrypi.org/downloads/raspberry-pi-os/
- Write Image - [balenaEtcher] - https://www.balena.io/etcher/ 
- Or write Image - Raspberry Pi Imager for Windows (https://www.raspberrypi.org/downloads/)
- Copy files - [ssh] and [wpa_supplicant.conf] on SD root
- Open mRemoteNG-Portable-1.76.20.24669
- sudo apt update && sudo apt -y dist-upgrade
- sudo apt -y install docker docker-compose
- Add permission to Pi User to run Docker Commands - sudo usermod -aG docker pi
- sudo systemctl enable docker
- sudo systemctl start docker
- sudo shutdown -r now
- sudo apt install git
- sudo blkid
- sudo nano /etc/fstab
- UUID=2440726E40724698 /mnt/mydisk ntfs exec,rw,user
- mount -a
- df -h
- mount -o remount,rw /

#-----------------------
- Raspbian  - https://www.raspberrypi.org/downloads/raspbian
- InfluxDB  - https://portal.influxdata.com/downloads
- Grafana   - https://grafana.com/grafana/download?platform=arm
- OpenHab   - https://www.openhab.org/download



- WiFi      - https://www.raspberrypi.org/documentation/configuration/wireless/wireless-cli.md
- SSH       - https://www.raspberrypi.org/documentation/remote-access/ssh/
