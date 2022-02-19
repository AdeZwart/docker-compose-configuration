# docker-setup
My docker compose file showing the containers I have running in my home automation setup.

## Containers:
* Portainer, A docker UI
  * Image: portainer/portainer-ce
* Home Assistant, my choice of a home automation hub. 
  * Image: homeassistant/raspberrypi3-homeassistant:stable
* SWAG (Secure Web Application Gateway), A container combining Nginx and Let's encrypt. 
  * Image: ghcr.io/linuxserver/swag
* Duck DNS
  * Image: ghcr.io/linuxserver/duckdns
* Pi-Hole
  * Image: pihole/pihole:latest
* Mosquitto
  * Image: eclipse-mosquitto
* Zigbee2MQTT
  * Image: koenkk/zigbee2mqtt
* Wireguard
  * Image: lscr.io/linuxserver/wireguard