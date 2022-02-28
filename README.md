# docker-setup
My docker compose file showing the containers I have running in my home automation setup.

## Containers:
* App Daemon
  * Image: acockburn/appdaemon
* Duck DNS
  * Image: ghcr.io/linuxserver/duckdns
* Home Assistant, my choice of a home automation hub. 
  * Image: homeassistant/raspberrypi3-homeassistant:stable
* Mosquitto
  * Image: eclipse-mosquitto  
* Pi-Hole
  * Image: pihole/pihole:latest
* Portainer, A docker UI
  * Image: portainer/portainer-ce
* SWAG (Secure Web Application Gateway), A container combining Nginx and Let's encrypt. 
  * Image: ghcr.io/linuxserver/swag
* Wireguard
  * Image: lscr.io/linuxserver/wireguard
* Zigbee2MQTT
  * Image: koenkk/zigbee2mqtt