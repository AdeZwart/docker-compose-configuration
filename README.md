# docker-setup
My docker compose file showing the containers I have running in my home automation setup.

## Containers:
* Portainer, A docker UI
  * Image: portainer/portainer-ce
* Home Assistant, my choice of a home automation hub. 
  * Image: homeassistant/raspberrypi3-homeassistant:stable
* SWAG (Secure Web Application Gateway), A container combining Nginx and Let's encrypt. 
  * Image: linuxserver/swag
* Influx DB
  * Image: influxdb
* Grafana
  * Image: grafana/grafana
* Pi-Hole
  * Image: pihole/pihole:latest